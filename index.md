---
layout: layout.html
title-part: Blog Main site
---

# {{ title-part }}

Hello and welcome to my blog this is where I discuss things around C++ and it's development as well as home for my modern [C++ tutorial](./tutorial).

```cpp
#include <print>

int main() { std::prinln("hello world"); }
```

```css
:root {
 --bg-primary: #1a1a1a;
 --bg-secondary: #2d2d2d;
 --text-primary: #ffffff;
 --text-secondary: #b0b0b0;
 --border-color: #404040;
 --accent-color: #66b3ff;
}

body {
 font-family: "Segoe UI", Roboto, sans-serif;
 background-color: var(--bg-primary);
 color: var(--text-primary);
 line-height: 1.6;
 transition: background-color 0.3s, color 0.3s;
}

main {
 max-width: 800px;
 margin: 0 auto;
 padding: 2rem;
}

aside {
  background-color: var(--bg-secondary);
  padding: 1rem;
  border-radius: 8px;
  border: 1px solid var(--border-color);
  margin-bottom: 2rem;
  float: left;
}

footer {
  text-align: center;
  padding: 1rem;
  border-top: 1px solid var(--border-color);
  margin-top: 2rem;
  color: var(--text-secondary);
  position: fixed;
  bottom: 0;
  width: 100%;
}

h1,
h2,
h3 {
 color: var(--text-primary);
 margin-top: 1.5rem;
 margin-bottom: 0.5rem;
}

article {
 background-color: var(--bg-secondary);
 padding: 1.5rem;
 margin-bottom: 2rem;
 border-radius: 8px;
 border: 1px solid var(--border-color);
}

a {
 color: var(--accent-color);
 text-decoration: none;
}

a:hover {
 text-decoration: underline;
}
```
