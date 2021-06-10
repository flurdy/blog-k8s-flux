
# Blog on K8s with Flux


* Host your own blog
* on Kubernetes
* using gitops with Flux

## Author

* Ivar Abrahamsen
  * flurdy.com
  * twitter.com/flurdy

### Presentation

[flurdy.github.io/blog-k8s-flux/](https://flurdy.github.io/blog-k8s-flux/)

#### Presentation source

[github.com/flurdy/blog-k8s-flux](https://github.com/flurdy/blog-k8s-flux)

### Build

Build Node app if needed:

`docker build -t flurdy/blog-k8s-flux .`

### Run

Either as a static web pages

`open index.html`

Or as a Node app with speakers notes and timers.
This uses docker-compose to run images build above.

`docker-compose up`

Press `s` to open *speaker's view*

### Presentation software

[reveal.js](https://revealjs.com)


## License

Creative Commons Attribution 4.0 International License

Copyright (C) 2021 Ivar Abrahamsen https://flurdy.com

### reveal.js

MIT licensed

Copyright (C) 2011-2021 Hakim El Hattab, https://hakim.se
