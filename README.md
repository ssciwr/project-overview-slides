# Project Overview Slides

[![slides](https://ssciwr.github.io/project-overview-slides/slides-thumb.png)](https://ssciwr.github.io/project-overview-slides)

[Download as PDF](https://ssciwr.github.io/project-overview-slides/slides.pdf)

To add your project, copy and paste this markdown, add it to the end of slides/index.md, then edit:

```
---

# My Project

- *Project type:* Open Call / Funded / etc
- *Description:* One line project description
- *Developer time:* 2 PM / 1 year / etc
- *People:* Joe / Sarah / etc
- *Techstack:* C++ / Python / etc
- *Topic:* Feature development / Best practices / Performance engineering / etc

---

# My Project screenshot

![width:600px](body-eye-sync.jpg)

```

The first slide should follow the above format, the second slide can be anything.

## Marp

[Marp](https://marp.app/) slides are just markdown, with `---` to separate the slides.

## Local rendering

To render the slides locally:

```bash
npx @marp-team/marp-cli@latest -w slides
```

Then you can open slides/index.html in a browser and see the changes when you edit slides/index.md.
