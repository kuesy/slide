# SlideWithGitHubPages
Markdownでスライド書いて、自分のGitHubで管理して、自分のGitHub Pagesで表示します。

## Description
- Slideを作る際に、Markdownで書いて自分のGitHubで管理するして、自分のGitHub Pagesで表示できます
  - reveal.js version 3.5.0を使用（[index.html](https://raw.githubusercontent.com/hakimel/reveal.js/a6ecbfa73272977d04e107f878a6afbfd17c6869/index.html)でリクエストパラメーターで渡されたスライドを表示できるようにしただけ）
- 通常、reveal.jsを使用する場合、毎回HTML部が必要となりますが、リクエストパラメーターでMarkdownのパスを指定すればスライドが表示されるようにしています

## Demo
- http://kuesy.github.io/slide/index.html?slide=example/slide1.md
- http://kuesy.github.io/slide/index.html?slide=example/slide2.md

## print-pdf
- URL末尾に「&print-pdf」を付与して表示。
