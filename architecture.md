# Architecture

![Architecture overview](<.gitbook/assets/Untitled Diagram.drawio.png>)

* Web
  * Link: [https://beta.k8s.diatomix.xyz/](https://beta.k8s.diatomix.xyz/)
  * Source: [https://github.com/Diatomix/Diatomix-frontend](https://github.com/Diatomix/Diatomix-frontend) (Beta branch is dev head)
  * CICD: github actions
  * Docker image: registry.k8s.aramid.finance/diatomix-web:1.2022.07.08-beta (private registry)
* Indexer
  * Runs in Kubernetes
  * Source: [https://github.com/scholtz/arc0017-indexer](https://github.com/scholtz/arc0017-indexer)
  * CICD: github actions
  * Docker image: [https://hub.docker.com/repository/docker/scholtz2/arc0017-indexer](https://hub.docker.com/repository/docker/scholtz2/arc0017-indexer)
* Charting api (in progress)
  * Runs in Kubernetes
  * Source: [https://github.com/scholtz/AsaCharts](https://github.com/scholtz/AsaCharts)
* GraphQL&#x20;
  * https://graphql.k8s.diatomix.xyz
  * https://graphql.k8s.diatomix.xyz/v1/graphql
  * [https://hub.docker.com/layers/graphql-engine/hasura/graphql-engine](https://hub.docker.com/layers/graphql-engine/hasura/graphql-engine) v2.8.0
* GraphQL ARC0014 authentication
  * [https://github.com/scholtz/HasuraAlgorandAuthWebHook](https://github.com/scholtz/HasuraAlgorandAuthWebHook)
  * [https://hub.docker.com/repository/docker/scholtz2/hasura-algorand-auth-web-hook](https://hub.docker.com/repository/docker/scholtz2/hasura-algorand-auth-web-hook)
