# Examples

This repo contains a collection of KCL examples, the documents are at [here](https://kcl-lang.io/docs/user_docs/guides/).

## Prerequisite

+ Firstly, download and install [KCL](https://kcl-lang.io/docs/user_docs/getting-started/install), [kpm](https://kcl-lang.io/docs/user_docs/guides/package-management/installation) and [kcl-openapi](https://kcl-lang.io/docs/tools/cli/openapi/quick-start) according to the instructions, and then prepare a Kubernetes environment.
+ Secondly, learn KCL [user guide](https://kcl-lang.io/docs/user_docs/guides/) and [tour](https://kcl-lang.io/docs/reference/lang/tour) documents.

## Samples

| Sample                                          | Description                                                                                                                               |
| ----------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| [Confuguration](./configuration/)               | KCL configuration examples, including simple key value pairs and dynamic parameters.                                                      |
| [Validation](./validation/)                     | KCL data validation examples, including writing KCL files to validate JSON, YAML, and other data.                                         |
| [Abstraction](./abstraction/)                   | KCL abstract examples, including using application models to abstract Docker Compose and Kubernetes resources.                            |
| [Data Integration](./data-integration/)         | KCL data integration examples, including integrating JSON and YAML data.                                                                  |
| [Automation](./automation/)                     | KCL automation examples, including how to use the KCL API to automatically modify and delete configurations.                              |
| [Package Management](./package-management/)     | KCL package management examples, including how to use kpm to manage your KCL project, e.g., add dependencies, publish packages, and more. |
| [Kubernetes](./kubernetes/)                     | KCL Kubernetes examples, including how to use KCL to generate, validate and mutate Kubernetes resources.                                  |
| [CI/CD Integrations](./ci-integration/)         | KCL CI/CD integration examples, including Github actions, Gitlab CI, etc.                                                                 |
| [GitOps](./gitops/)                             | KCL GitOps examples.                                                                                                                      |
| [Konfig](https://github.com/KusionStack/konfig) | KCL Konfig examples, including a mono repository of the infra and app configuration with KCL                                              |

## Testing

Run all examples

```bash
./test.sh
```
