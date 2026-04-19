# platform-apps

Configuracoes reutilizaveis de componentes cross/plataforma.

O `platform-gitops` decide quais componentes entram em cada cluster. Este repositorio guarda os values e configuracoes consumidos por essas Applications.

Estrutura inicial:

```text
istio/
  values/
    dev/
    uat/
    prod/
```

Cada ambiente tem values separados para:

```text
base.yaml
istiod.yaml
ingressgateway.yaml
```
