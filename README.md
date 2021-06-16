
# Blog on K8s with Flux

Running your own blog,
on your own Kubernetes cluster,
managed with Flux, a gitops tool.

## Author

* Ivar Abrahamsen
  * [flurdy.com](https://flurdy.com)
  * [@flurdy](https://twitter.com/flurdy)

## Date

* Presented in June 2021.

### Presentation

[flurdy.github.io/blog-k8s-flux/](https://flurdy.github.io/blog-k8s-flux/)

#### Presentation source

[github.com/flurdy/blog-k8s-flux](https://github.com/flurdy/blog-k8s-flux)

## Tools

* [Jekyll](https://jekyllrb.com)
  <!-- * [Hugo](https://gohugo.io) -->
* [CircleCI](circleci.com)
  <!-- * [Github Actions](https://github.com/features/actions) -->
* [Quay](https://quay.io)
  <!-- * [Google Container Registry](https://cloud.google.com/container-registry/) -->
* [Digital Ocean](https://www.digitalocean.com)
  <!-- * [Google GKE](https://cloud.google.com/kubernetes-engine/) -->
* [Kubernetes](https://kubernetes.io)
* [Flux](https://fluxcd.io)
  <!-- * [Argo](https://argoproj.github.io) -->

## Run

### Static page

As a static web page

```
open index.html
```

Note, no timers or notes are available in this case.

### Node app

As a local Node.js app

```
npm install
npm start -- --port=8010
```

With speaker notes and timers.

Press `s` to open *speaker's view*

### Node Docker

Build and run Node app in Docker:

```
docker build -t flurdy/blog-k8s-flux .
docker compose up
```

## Presentation software

[reveal.js](https://revealjs.com)


## License

Creative Commons Attribution 4.0 International License

Copyright (C) 2021 Ivar Abrahamsen https://flurdy.com

### reveal.js

MIT licensed

Copyright (C) 2011-2021 Hakim El Hattab, https://hakim.se
