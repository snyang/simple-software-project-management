# Software Development Guidelines

## Documents
- Design
- Use Case
- Database Design
## Coding
- Basic Knowledge
- Java
- CSharp
- Python
- Unit Tests
  Unit testing is a key of software quality.
  A main problem of writing unit tests is either very little unit tests or too much unit tests.
  To define when developers should write unit test is necessary.
  - Avoid write unit tests for POJO
  - Do only test interface
    We should only write unit tests for interfaces of a specific layer.
  - Avoid to test any internal/private things
    Most unit tests components provide ability to test some internal things, like how many times a method be invoked, private fields variables etc.
    Avoid to test these things. When a new feature is added, it is easy to break these cases.
- Java Script
- Type Script
## Architecture
- Infrastructure
  - Authentication/Authorization
  - Data Access
  - Exception
  - Export
  - Globalization
  - Home
  - Import
  - Instrument
  - Layers
  - Localization
  - Logging
  - Login
  - Navigation
  - Performance
  - Presentation
  - Print
  - Report
  - Security Model
  - 3rd party tools
    Low Price/Good community/Quick update/Popular/More Stars/Open Source
  - 3rd party components
  - Validation
  - Helpers
    - String
    - File
    - Html
    - XML
    - JSON
    - Regular Expression
    - SQL
    - Converter
- Logging
- Exception
- Layers
  - Entity
    - POJO style classes
    - Do not reference any projects
    - Avoid to reference 3rd party components
    - Support OR Mapping if need
    - Support serialize(JSON) if need
    - Avoid auto generated
    - An Entity support any query results