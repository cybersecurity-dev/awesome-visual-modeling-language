<div align="center">

```mermaid
flowchart TB
    UML["Unified Modeling Language<br/>(UML) Diagram Taxonomy"]

    UML --> STRUCTURE["Structure Diagrams<br/>Represent the static organization of a system"]
    UML --> BEHAVIOR["Behavior Diagrams<br/>Represent system behavior and change over time"]

    %% =====================================================
    %% STRUCTURE DIAGRAMS
    %% =====================================================

    STRUCTURE --> CLASS["Class Diagram"]
    STRUCTURE --> OBJECT["Object Diagram"]
    STRUCTURE --> COMPONENT["Component Diagram"]
    STRUCTURE --> COMPOSITE["Composite Structure Diagram"]
    STRUCTURE --> PACKAGE["Package Diagram"]
    STRUCTURE --> DEPLOYMENT["Deployment Diagram"]
    STRUCTURE --> PROFILE["Profile Diagram"]

    CLASS --> CLASS_LEGEND["Legend: Classes, attributes,<br/>operations, and relationships"]
    CLASS --> CLASS_EXAMPLE["Example: Customer places Order;<br/>Order contains Product"]

    OBJECT --> OBJECT_LEGEND["Legend: Object instances and<br/>their values at a specific time"]
    OBJECT --> OBJECT_EXAMPLE["Example: customer1:Customer<br/>linked to order101:Order"]

    COMPONENT --> COMPONENT_LEGEND["Legend: Software components,<br/>interfaces, and dependencies"]
    COMPONENT --> COMPONENT_EXAMPLE["Example: Mobile App uses<br/>Authentication Service and API"]

    COMPOSITE --> COMPOSITE_LEGEND["Legend: Internal structure of a<br/>classifier using parts and ports"]
    COMPOSITE --> COMPOSITE_EXAMPLE["Example: PaymentProcessor contains<br/>Validator, Gateway, and Logger"]

    PACKAGE --> PACKAGE_LEGEND["Legend: Packages and dependencies<br/>between model groups"]
    PACKAGE --> PACKAGE_EXAMPLE["Example: UI package depends on<br/>Service and Domain packages"]

    DEPLOYMENT --> DEPLOYMENT_LEGEND["Legend: Hardware nodes, execution<br/>environments, and deployed artifacts"]
    DEPLOYMENT --> DEPLOYMENT_EXAMPLE["Example: Web application deployed<br/>on server connected to database"]

    PROFILE --> PROFILE_LEGEND["Legend: UML extensions using<br/>stereotypes, tags, and constraints"]
    PROFILE --> PROFILE_EXAMPLE["Example: Cybersecurity profile with<br/>Malware, Asset, and Threat stereotypes"]

    %% =====================================================
    %% BEHAVIOR DIAGRAMS
    %% =====================================================

    BEHAVIOR --> USECASE["Use Case Diagram"]
    BEHAVIOR --> ACTIVITY["Activity Diagram"]
    BEHAVIOR --> STATE["State Machine Diagram"]
    BEHAVIOR --> INTERACTION["Interaction Diagrams<br/>Specialized behavior diagrams"]

    USECASE --> USECASE_LEGEND["Legend: Actors, system functions,<br/>and actor-system relationships"]
    USECASE --> USECASE_EXAMPLE["Example: Customer logs in,<br/>places order, and makes payment"]

    ACTIVITY --> ACTIVITY_LEGEND["Legend: Actions, decisions,<br/>parallel paths, and workflows"]
    ACTIVITY --> ACTIVITY_EXAMPLE["Example: Receive APK, extract features,<br/>classify sample, report result"]

    STATE --> STATE_LEGEND["Legend: States, events, transitions,<br/>guards, and state actions"]
    STATE --> STATE_EXAMPLE["Example: File moves from<br/>Unknown to Scanned to Classified"]

    %% =====================================================
    %% INTERACTION DIAGRAMS
    %% =====================================================

    INTERACTION --> SEQUENCE["Sequence Diagram"]
    INTERACTION --> COMMUNICATION["Communication Diagram"]
    INTERACTION --> OVERVIEW["Interaction Overview Diagram"]
    INTERACTION --> TIMING["Timing Diagram"]

    SEQUENCE --> SEQUENCE_LEGEND["Legend: Time-ordered messages<br/>between actors and objects"]
    SEQUENCE --> SEQUENCE_EXAMPLE["Example: User -> App -> API -> Database<br/>during authentication"]

    COMMUNICATION --> COMMUNICATION_LEGEND["Legend: Object links and<br/>numbered exchanged messages"]
    COMMUNICATION --> COMMUNICATION_EXAMPLE["Example: Scanner, FeatureExtractor,<br/>and Classifier exchange messages"]

    OVERVIEW --> OVERVIEW_LEGEND["Legend: High-level control flow<br/>between multiple interactions"]
    OVERVIEW --> OVERVIEW_EXAMPLE["Example: Detection workflow combines<br/>scan, analysis, and reporting sequences"]

    TIMING --> TIMING_LEGEND["Legend: State or value changes<br/>along a time axis"]
    TIMING --> TIMING_EXAMPLE["Example: Request, processing,<br/>timeout, and response over time"]

    %% =====================================================
    %% TAXONOMY RELATIONSHIP
    %% =====================================================

    INTERACTION -. "contains" .-> SEQUENCE
    INTERACTION -. "contains" .-> COMMUNICATION
    INTERACTION -. "contains" .-> OVERVIEW
    INTERACTION -. "contains" .-> TIMING

    %% =====================================================
    %% STYLES
    %% =====================================================

    classDef root fill:#7f1d1d,color:#ffffff,stroke:#450a0a,stroke-width:4px;
    classDef category fill:#c2410c,color:#ffffff,stroke:#7c2d12,stroke-width:3px;
    classDef interaction fill:#d97706,color:#ffffff,stroke:#92400e,stroke-width:3px;
    classDef structural fill:#dbeafe,color:#172554,stroke:#2563eb,stroke-width:2px;
    classDef behavioral fill:#dcfce7,color:#14532d,stroke:#16a34a,stroke-width:2px;
    classDef interactionDiagram fill:#fef3c7,color:#78350f,stroke:#d97706,stroke-width:2px;
    classDef legend fill:#f3f4f6,color:#111827,stroke:#6b7280,stroke-width:1px;
    classDef example fill:#faf5ff,color:#581c87,stroke:#9333ea,stroke-width:1px,stroke-dasharray:5 3;

    class UML root;
    class STRUCTURE,BEHAVIOR category;
    class INTERACTION interaction;

    class CLASS,OBJECT,COMPONENT,COMPOSITE,PACKAGE,DEPLOYMENT,PROFILE structural;
    class USECASE,ACTIVITY,STATE behavioral;
    class SEQUENCE,COMMUNICATION,OVERVIEW,TIMING interactionDiagram;

    class CLASS_LEGEND,OBJECT_LEGEND,COMPONENT_LEGEND,COMPOSITE_LEGEND legend;
    class PACKAGE_LEGEND,DEPLOYMENT_LEGEND,PROFILE_LEGEND legend;
    class USECASE_LEGEND,ACTIVITY_LEGEND,STATE_LEGEND legend;
    class SEQUENCE_LEGEND,COMMUNICATION_LEGEND,OVERVIEW_LEGEND,TIMING_LEGEND legend;

    class CLASS_EXAMPLE,OBJECT_EXAMPLE,COMPONENT_EXAMPLE,COMPOSITE_EXAMPLE example;
    class PACKAGE_EXAMPLE,DEPLOYMENT_EXAMPLE,PROFILE_EXAMPLE example;
    class USECASE_EXAMPLE,ACTIVITY_EXAMPLE,STATE_EXAMPLE example;
    class SEQUENCE_EXAMPLE,COMMUNICATION_EXAMPLE,OVERVIEW_EXAMPLE,TIMING_EXAMPLE example;
```
# **`Awesome`** Visual Modeling [Language](https://wikipedia.org/wiki/Unified_Modeling_Language) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]()
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)]()

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

## 📖 Contents
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)


## UML Diagram

```mermaid
flowchart LR
    UML["UML Diagram Taxonomy"]

    UML --> STRUCTURE["Structure Diagrams"]
    UML --> BEHAVIOR["Behavior Diagrams"]

    STRUCTURE --> CLASS["Class"]
    STRUCTURE --> OBJECT["Object"]
    STRUCTURE --> COMPONENT["Component"]
    STRUCTURE --> COMPOSITE["Composite Structure"]
    STRUCTURE --> PACKAGE["Package"]
    STRUCTURE --> DEPLOYMENT["Deployment"]
    STRUCTURE --> PROFILE["Profile"]

    BEHAVIOR --> USECASE["Use Case"]
    BEHAVIOR --> ACTIVITY["Activity"]
    BEHAVIOR --> STATE["State Machine"]
    BEHAVIOR --> INTERACTION["Interaction Diagrams"]

    INTERACTION --> SEQUENCE["Sequence"]
    INTERACTION --> COMMUNICATION["Communication"]
    INTERACTION --> OVERVIEW["Interaction Overview"]
    INTERACTION --> TIMING["Timing"]

    classDef root fill:#b71c1c,color:white,stroke:#7f0000,stroke-width:3px;
    classDef main fill:#ef6c00,color:white,stroke:#a63f00,stroke-width:2px;
    classDef subgroup fill:#f9a825,color:#212121,stroke:#b27300,stroke-width:2px;
    classDef leaf fill:#fff8e1,color:#212121,stroke:#d89b00;

    class UML root;
    class STRUCTURE,BEHAVIOR main;
    class INTERACTION subgroup;
    class CLASS,OBJECT,COMPONENT,COMPOSITE,PACKAGE,DEPLOYMENT,PROFILE leaf;
    class USECASE,ACTIVITY,STATE,SEQUENCE,COMMUNICATION,OVERVIEW,TIMING leaf;
```

##

### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-visual-modeling-language/graphs/contributors)!

### License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

[🔼 Back to top](#awesome-visual-modeling-language-)
