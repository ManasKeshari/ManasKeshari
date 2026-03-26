<div align="center">

# Hi there, I'm Manas Keshari! 🚀
**BCA 6th Sem | Full-Stack Developer | Lucknow, India**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.herokuapp.com?font=Fira+Code+Mono;size=32&pause=1000&color=3776AB&center=true&lines=Full-Stack+Developer+%F0%9F%9A%80;Building+Production+APIs;FastAPI+%7C+Django+%7C+Next.js;AWS+%7C+React+%7C+Docker;Job-Ready+2026+%F0%9F%8F%86">
  <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.herokuapp.com?font=Fira+Code+Mono;size=32&pause=1000&color=3776AB&center=true&lines=Full-Stack+Developer+%F0%9F%9A%80;Building+Production+APIs;FastAPI+%7C+Django+%7C+Next.js;AWS+%7C+React+%7C+Docker;Job-Ready+2026+%F0%9F%8F%86">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code+Mono;size=32&pause=1000&color=3776AB&center=true&lines=Full-Stack+Developer+%F0%9F%9A%80;Building+Production+APIs;FastAPI+%7C+Django+%7C+Next.js;AWS+%7C+React+%7C+Docker;Job-Ready+2026+%F0%9F%8F%86" alt="typing svg">
</picture>

![Snake Animation](https://github.com/ManasKeshari/ManasKeshari/blob/output/github-contribution-grid-snake.svg)

</div>

## ✨ About Me
<p>
  <em>BCA Final Year building scalable APIs & full-stack apps. Open to IT/Telecom roles in Lucknow!</em>
</p>

- 🌱 FastAPI, Django, Next.js, AWS, Docker
- 💼 E-Commerce, Task SaaS, Chat APIs deployed live
- 🎮 Gaming & AI music on the side (Valorant, Suno AI)
- 📫 Reach me: [manaskeshari@email.com](mailto:manas@example.com)

## 🛠️ Animated Skills
```mermaid
graph TD
    A[Frontend<br/>Next.js React Svelte] --> B[Backend<br/>FastAPI Django Node.js]
    B --> C[Databases<br/>PostgreSQL MongoDB]
    C --> D[DevOps<br/>AWS Docker CI/CD]
    style A fill:#61DAFB
    style B fill:#00599C
    style C fill:#336791
    style D fill:#232F3E

name: Generate Snake
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
jobs:
  gen:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v4
    - name: generate
      uses: Platane/snk@v3
      with:
        github_user_name: ManasKeshari
        outputs: |
          output/github-contribution-grid-snake.svg
          output/github-contribution-grid-snake-dark.svg?palette=github-dark
    - uses: crazy-max/ghaction-github-pages@v4
      with:
        target_branch: output