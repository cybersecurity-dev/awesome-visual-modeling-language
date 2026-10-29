<div align="center">

# **`Awesome`** Visual Modeling [Language](https://wikipedia.org/wiki/Unified_Modeling_Language)
</div>

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]()
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)]()

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefence"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
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

[🔼 Back to top](#awesome-visual-modeling-language)
