# 第三部分：使用 Skaffold 构建和部署云原生 Spring Boot 应用

本节将主要关注使用 Skaffold 在本地(minikube 等)和远程集群( **GKE** )构建和部署 Spring Boot 应用。我们将探索如何使用谷歌开发的云代码，在您的集成开发环境中轻松构建和部署云原生应用。然后，我们将使用 Skaffold 构建一个 Spring Boot 应用并将其部署到一个托管的 Kubernetes 产品中，例如 **GKE** 。我们将进一步了解如何使用 Skaffold 和 GitHub Actions 创建生产就绪的 CI/CD 流水线。我们将通过结合 Skaffold 和 Argo 光盘来做一些实验，以实现 GitOps 风格的光盘工作流程。最后，我们将看看 Skaffold 的一些替代方案，并了解我们应该在工作流程中使用的 Skaffold 最佳实践。此外，我们将探讨使用 Skaffold 开发应用时最常见的陷阱/限制。最后，我们将总结我们在这本书中学到的东西。

在本节中，我们有以下章节:

*   [*第 7 章*](07.html#_idTextAnchor092)*使用云码插件*构建和部署 Spring Boot 应用
*   [*第 8 章*](08.html#_idTextAnchor099)*使用 skafold*将 Spring Boot 应用部署到谷歌 Kubernetes 引擎
*   [*第 9 章*](09.html#_idTextAnchor116)*使用 skafold*创建生产就绪的 CI/CD 流水线
*   [*第 10 章*](10.html#_idTextAnchor129)*探索 Skaffold 替代方案、最佳实践和陷阱*