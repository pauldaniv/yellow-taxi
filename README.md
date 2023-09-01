# yellow-taxi
Promotion project

Sample diagram:

```mermaid
stateDiagram-v2
    ProjectStart --> InfrastructureSetup
        InfrastructureSetup --> CI/CD
        InfrastructureSetup --> Terraform
            Terraform --> Kubernetes
                Kubernetes --> Kafka
                Kubernetes --> Zookeeper
                Kubernetes --> Redis
            Terraform --> AWS
                AWS --> RDS
                AWS --> CodeArtifact
                AWS --> ContainerRegistry
        InfrastructureSetup --> AutomationScripts
    ProjectStart --> FunctionaltityImplementation
        FunctionaltityImplementation --> Authentication
        FunctionaltityImplementation --> Statistic_calculation
    ProjectStart --> Testing
        Testing --> Manual
        Testing --> Unit
        Testing --> Performance
    ProjectStart --> Unplanned
    
```

