# new evening
 <h2>Create files and folders</h2>
 
|Markdown|`ldf`  |df
|--------|--|--
|       > строка№1 |  fgh|
> sdf
>1
> 2

==Here's== a sentence with a footnote. [^1]
Here's a sentence with a footnote. [^2]

term
: definition
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
 
``` html
<!DOCTYPE html>
<html>
<head>
    <title>Example HTML Page</title>
</head>
<body>
    <h1>Hello, world!</h1>
    <p>This is an example HTML page.</p>
</body>
</html>
```
[^1]: This is the footnote.

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
[^2]: This is the footnote.
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
