# yellow-taxi
Promotion project

Sample diagram:

```mermaid
stateDiagram-v2
    ProjectStart --> CI/CD
    ProjectStart --> FunctionaltityImplementation
    FunctionaltityImplementation --> Login/Logout
    FunctionaltityImplementation --> Client
    FunctionaltityImplementation --> API
    ProjectStart --> AWS_SETUP
    ProjectStart --> Testing
    Testing --> Manual
    Testing --> Unit
    Testing --> E2E
    Testing --> Performance
    ProjectStart --> Unplanned
    
```

