# Tetris on Ainize

[![Run on Ainize](https://ainize.herokuapp.com/static/images/run_on_ainize_button.svg)](https://ainize.web.app/redirect?git_repo=github.com/Laeyoung/javascript-tetris)

### Step.1 Fork and Clone your imgproxy repo
```
git clone https://github.com/${YOUR-GITHUB-ID}/javascript-tetris.git

```

### Step.2 Docker build and push it to Docker Hub
```
docker build -t ${YOUR-DOCKER-HUB-ID}/javascript-tetris .
docker push ${YOUR-DOCKER-HUB-ID}/javascript-tetris
```

### Step.3 Sign up and apply beta test at [Ainize.ai](https://ainize.ai)

### Step.4 Deploy Tetris on Ainize ([Tutorial](https://ai-network.gitbook.io/ainize-tutorials/ainize/hello-world#ainize-steps))

1. Enter your Github repo url, `https://github.com/${YOUR-GITHUB-ID}/javascript-tetris`
2. Enter your dockerhub container id, `${YOUR-DOCKER-HUB-ID}/javascript-tetris`
3. Set port as 80.

### Step.5 Enjoy tetris

https://javascript-tetris.laeyoung.endpoint.ainize.ai/ (change __laeyoung__ to __your-ainize-ai__)

Javascript Tetris
=================

An HTML5 Tetris Game

 * [play the game](http://codeincomplete.com/projects/tetris/)
 * read a [blog article](http://codeincomplete.com/posts/2011/10/10/javascript_tetris/)
 * view the [source](https://github.com/jakesgordon/javascript-tetris)

>> _*SUPPORTED BROWSERS*: Chrome, Firefox, Safari, Opera and IE9+_

FUTURE
======

 * menu
 * animation and fx
 * levels
 * high scores
 * touch support
 * music and sound fx


License
=======

[MIT](http://en.wikipedia.org/wiki/MIT_License) license.


