# Blackdagger Default YAML Files
This repository consists of YAML files that are created to be used in [Blackdagger](https://github.com/ErdemOzgen/blackdagger) tool.
These YAML files are designed to perform basic and simple tasks and show you the basic format and mechanisms of Blackdagger YAML files. You can find the descriptions of each step in the YAML files.


# Blackdagger: Cyber Workflow Automation Framework
Blackdagger is a single binary tool that is capable of managing and automating complex workflows for various purposes. To improve the experience of users while using Blackdagger, various repositories that contains tested YAML files for complex workflows, easy-to-setup infrastructure for CART and DevSecOps purposes are suggested by the team. With major additions to these repositories, everything that makes Blackdagger better is collected under a framework called Blackdagger: Cyber Workflow Automation Framework.

The framework consist of 5 components:

- [**Blackdagger:**](https://github.com/ErdemOzgen/blackdagger) Core of the framework for orchestrating the components and workflows
- [**Blackcart:**](https://github.com/ErdemOzgen/blackcart) A specialized Docker container optimized for Continuous Automated Red Teaming (CART) and DevSecOps pipeline tasks.
- **Blackdagger YAMLs (this repository):** Pre-tested [example](https://github.com/ErdemOzgen/blackdagger-default) workflows, demonstrating real-world [DevSecOps](https://github.com/ErdemOzgen/blackdagger-devsecops) and [CART](https://github.com/ErdemOzgen/blackdagger-cart) use-cases, facilitating quick adoption and adaptation.
- [**Blackdagger Github Infra :**](https://github.com/ErdemOzgen/blackdagger-github-infra) A suite of advanced workflows utilizing GitHub Actions infrastructure for enhanced defense evasion techniques, scalability, and performance.
- [**Blackdagger Web Kit :**](https://github.com/ErdemOzgen/blackdagger-web-kit) A browser extension integrating all core functionalities, enabling direct interaction and execution of Blackdagger workflows from within the browser.

<p align="center">
  <img src="https://github.com/ErdemOzgen/blackdagger/blob/main/assets/images/framework_diagram.png" width="500" alt="framework-diagram">
</p>

Each component is compatible with each other to run on **any environment, for any case and as easy, fast and effective as possible.** The framework also enables adding, removing or modifying components to add extra features for new purposes.


# Features Provided With These YAMLs
- An example of a basic workflow with a useful DAG structure
- The format of conditional YAML files
- An example for passing values between steps
- An example to show you the YAML stopper
- An example to show you how to write files
- Pulling desired YAMLs from our collection
- Running an example HTTP request and jq query to show you various modifiable parameters
- Running GoTTY service

# Contributing
- If you encounter with a problem while using these YAML files
- If you think there should be a YAML file for a default action
- If you have a comment or idea about default YAMLs

Please do not hesitate to contact us, open an issue or a pull request. We welcome any and all contributions!

