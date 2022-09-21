# {TEMPLATE_SERVICE_NAME} Service Kotlin Client
Template generated client stubs in Kotlin for the gRPC service - {TEMPLATE_SERVICE_NAME} Service

![](logo/bh_grpc_kotlin.png)

## Overview

This directory contains a generated Kotlin client for the gRPC service - {TEMPLATE_SERVICE_HYPHEN_NAME}

- This repo was created using builder-hub from a starter template for gRPC and Kotlin.
- For more details on the starter template, see the [project on GitHub](https://github.com/builder-hub/starter-service-kotlin-client).

You can find detailed instructions for running the client below

## File organization

The starter sources are organized into the following top-level folders:

- [{TEMPLATE_SERVICE_HYPHEN_NAME}-service-models]({TEMPLATE_SERVICE_HYPHEN_NAME}-service-models): `.proto` files for generating the stubs
- [{TEMPLATE_SERVICE_HYPHEN_NAME}-service-client]({TEMPLATE_SERVICE_HYPHEN_NAME}-service-client): Kotlin clients based on regular stub artifacts

## Set up the project
<details>
  <summary>Clone the project</summary>

  Clone the project recursively cloning all submodules

  ```sh
  git clone git@github.com:{TEMPLATE_SERVER_REPO_OWNER}/{TEMPLATE_SERVICE_HYPHEN_NAME}-service-kotlin-client.git --recurse-submodules
  ```

  Navigate into the project:
  ```sh
  cd {TEMPLATE_SERVICE_HYPHEN_NAME}-service-kotlin-client
  ```
</details>

## Run the client on macOS

<details>
  <summary>Install Homebrew</summary>

  Download and install Homebrew:

  ```sh
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```
</details>
<details>
  <summary>Install JDK</summary>

  Install any version of JDK (8 preferred):

  ```sh
  brew install openjdk@8
  ```

  Add the installed version of JDK to your path through .zshrc or .bash_profile

  ```sh
  echo 'export PATH="/usr/local/opt/openjdk@8/bin:$PATH"' >> ~/.zshrc
  source ~/.zshrc
  ```

  or

  ```sh
  echo 'export PATH="/usr/local/opt/openjdk@8/bin:$PATH"' >> ~/.bash_profile
  source ~/.bash_profile
  ```
</details>
<details>
  <summary>Run the client</summary>

  Run the client which will make requests to the server using 50051 port:

  ```sh
  ./gradlew {TEMPLATE_SERVICE_HYPHEN_NAME}-service-client:start
  ```
</details>

[grpc.io Kotlin/JVM]: https://grpc.io/docs/languages/kotlin/
[Quick start]: https://grpc.io/docs/languages/kotlin/quickstart/
[Basics tutorial]: https://grpc.io/docs/languages/kotlin/basics/
