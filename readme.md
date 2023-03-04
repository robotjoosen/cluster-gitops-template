# Cluster GitOps Template

This repository part of a cluster setup consisting of a management and git-ops repository.

- [Cluster Management](https://github.com/robotjoosen/cluster-management-template)
- [Git-ops Repository](https://github.com/robotjoosen/cluster-gitops-template)

# Terminology

| Name        | Kustomize terms | Description                                                                                         |
|-------------|-----------------|-----------------------------------------------------------------------------------------------------|
| Environment | Variant         | An environment contains collection of application with bespoke configuration for a specific cluster |
| Manifest    | Base / Resource | Collection of resources for an application linked together in a kustomization                       |
| Mixin       | Overlay         | A reusable manifest that can be applied to multiple applications                                    |
| Change      | Overlay         | A change is a piece of code that can be promoted across environments                                |
