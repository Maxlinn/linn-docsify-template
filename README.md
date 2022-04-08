# Homepage

Set up you markdown files site in one minute.
Your :star: will be high praise for my efforts, thank you!

## Usage

- Use this repository as template.
  - You'll get a `main` branch with those files
    - `index.html`, settings, **must modify, at least modify `!!!` commented settings**.
    - `README.md`, default page of your site, **change it to yours**.
    - `.nojekyll`, ignore it.
    - `_navbar.md, _sidebar.md, _footer.md`, **change it yo yours**.
  - That's all, docsify is just as simple as you see it.
- Go to repository settings, set github pages work on `main` branch.

## Features

- Full text search.
  - Implement by frontend. Discover documents by hyperlinks in the document you viewed(like a web spider), **not always contains all documents in valut**, and **search index refreshes every one day**.
- Dark Mode.
- LaTeX, mermaid.js, code highlight support.
- Custom font settings.
- User experience enhancement.
  - Copy code button.
  - Pangu, add Space to Chinese and English overlap.
  - Collapsable nested sidebar.
- Support tab syntax, see examples in syntax test below.

## Reminder

- Every `README.md` will serve as the default page of this folder level, including this one. So don't hesitate to delete this `README.md` to create your own homepage!


## Markdown Syntax Test

~~deleted~~

==hightlight==

$a^2+b^2=c^2$

$$
a^2+b^2=c^2
$$

:star:

```mermaid
sequenceDiagram
Alice->John: Hello John, how are you?
loop every minute
    John-->Alice: Great!
end
```

```python
for i in range(42):
    print("calm down")
```

```markdown
<!-- tabs:start -->
#### **English**
Hello!
#### **French**
Bonjour!
#### **Italian**
Ciao!
<!-- tabs:end -->
```

<!-- tabs:start -->
#### **English**
Hello!
#### **French**
Bonjour!
#### **Italian**
Ciao!
<!-- tabs:end -->