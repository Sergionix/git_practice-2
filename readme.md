# new evening
``` cpp
const marked = require('marked');
const hljs = require('highlight.js');

// Используйте highlight.js для подсветки синтаксиса
marked.setOptions({
  highlight: function (code) {
    return hljs.highlightAuto(code).value;
  }
});

const markdownText = '```javascript\nfunction sayHello() {\n  console.log("Hello, world!");\n}\n```';
const htmlText = marked(markdownText);
console.log(htmlText);
```
```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of Alice: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?

```
```mermaid
flowchart TB
    c1-->a2
    subgraph one
    a1-->a2
    end
    subgraph two
    b1-->b2
    end
    subgraph three
    c1-->c2
    end
```
## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$
