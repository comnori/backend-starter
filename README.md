# Backend Starter Template

## Java Edition

`devcontainer`의 Template과 Features 그리고 `GitHub`의 Template을 사용하여 Java Backend 개발을 빠르게 시작할 수 있습니다.

인력 및 장비의 추가 및 장비 또는 운영체제의 변경 등 개발 환경을 구성해야 할 때 번거로움을 해결할 수 있습니다. 또한, 개발 환경의 변경 이력의 추적이 가능합니다.

미리 정의된 개발 환경을 사용하고 공유할 수 있어, 모든 개발자가 동일한 개발 환경에서 작업을 시작할 수 있습니다. 이를 통해 협업이 원활해지고 개발 환경에 대한 일관성을 유지할 수 있습니다.

- 장점
  - 동일한 VSCODE 초기 설정
  - 동일한 VSCODE 확장 기능 초기 설정
  - 동일한 JDK 버전 및 OS 사용
  - 개발환경 변경 추적 가능

## Installation

1. Docker or [Docker Desktop](https://www.docker.com/products/docker-desktop/)
2. [Visual Studio Code](https://code.visualstudio.com/) and Extensions
    - [Dev Containers](vscode:extension/ms-vscode-remote.remote-containers)
    - [Docker](vscode:extension/ms-azuretools.vscode-docker)

## Getting start

1. git clone
```shell
> git clone --depth 1 https://github.com/comnori/backend-starter.git
```
2. change name in `devcontainer.json`
3. Constructed with [reference](#reference) to reference materials
4. devconatiner build

## Customizations

- Base : Ubuntu 22 LTS
- Features
  - Microsoft JDK 21
  - oh-my-zsh
  - NodeJS 20 LTS
    - For SonarLint

### VS Code

#### Extensions

- Requirments
  - Java
    - [Extension Pack for Java](vscode:extension/vscjava.vscode-java-pack)
    - [Gradle for Java](vscode:extension/vscjava.vscode-gradle)
    - [Spring Boot Extension Pack](vscode:extension/vmware.vscode-boot-dev-pack)
    - [Lombok Annotations Support for VS Code](vscode:extension/vscjava.vscode-lombok)
    - [Community Server Connectors](vscode:extension/redhat.vscode-community-server-connector)
    - [Checkstyle for Java](vscode:extension/shengchen.vscode-checkstyle)
    - [XML](vscode:extension/redhat.vscode-xml)
    - [YAML](vscode:extension/redhat.vscode-yaml)
    - [SQL Notebook](vscode:extension/cmoog.sqlnotebook)
  - Git
    - [GitLens](vscode:extension/eamodio.gitlens)
    - [git-graph](vscode:extension/mhutchie.git-graph)
  - Appearance
    - [One Dark Pro](vscode:extension/zhuangtongfa.material-theme)
    - [Material Icon Theme](vscode:extension/PKief.material-icon-theme)
    - [indent-rainbow](vscode:extension/oderwat.indent-rainbow)
    - [Better Comments](vscode:extension/aaron-bond.better-comments)
  - Code Assist
    - [Inline Parameters for VSCode](vscode:extension/liamhammett.inline-parameters)
    - [Error Lens](vscode:extension/usernamehw.errorlens)
  - Analysis
    - [SonarLint](vscode:extension/SonarSource.sonarlint-vscode)
  - Todo
    - [Todo Tree](vscode:extension/Gruntfuggly.todo-tree)
  - File format
    - [EditorConfig](vscode:extension/EditorConfig.EditorConfig)
  - Template
    - [Folder Templates](vscode:extension/Huuums.vscode-fast-folder-structure)

#### Settings

|Options|Value|
|-|-|
|Default terminal|ohmyzsh|
|formatOnSave|true|
|source.fixAll|true|
|source.organizeImports|true|

### etc

## Troubleshooting

[WSL 2 consumes massive amounts of RAM and doesn't return](https://github.com/microsoft/WSL/issues/4166)
- [wslconfig](https://devblogs.microsoft.com/commandline/windows-subsystem-for-linux-september-2023-update/#automatic-memory-reclaim)

## Reference

- [Developing inside a Container](https://code.visualstudio.com/docs/devcontainers/containers)
- [Development Containers](https://containers.dev/)
- [Introduction to dev containers](https://docs.github.com/en/codespaces/setting-up-your-project-for-codespaces/adding-a-dev-container-configuration/introduction-to-dev-containers)

