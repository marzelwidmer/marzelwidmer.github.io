# README

[Creating a Blog with Hugo and Github in 10 minutes](https://www.youtube.com/watch?v=LIFvgrRxdt4)

```bash
git clone git@github.com:marzelwidmer/resume.git
```

```bash
cd resume
```

```bash
hugo new site marcelwidmer
```

```bash
cd marcelwidmer
```

```bash
cd themes
```

```bash
git clone https://github.com/niklasbuschmann/contrast-hugo.git
```

```bash
cd ..
```

```bash
vi hugo.toml
```

```bash
baseURL = 'https://marzelwidmer.github.io/'
languageCode = 'en-us'
title = 'Resume - Marcel Widmer'
theme = 'contrast-hugo'
```

```bash
hugo new posts/myposts.md
```

```bash
vi content/posts/myposts.md
```

+++
title = 'Myposts'
date = 2024-02-17T12:42:12+01:00

# draft = true

+++

```kotlin
fun foo() : String {
    val bar = "Foo Bar"
    return bar
}
```

```bash
hugo server
```

```bash
git submodule add -b main git@github.com:marzelwidmer/marzelwidmer.github.io.git public
```

```bash
hugo -t contrast-hugo
```

```bash
cd public/
```

```bash
git add . && git commit -m 'chore: test publishing' && git push
```
