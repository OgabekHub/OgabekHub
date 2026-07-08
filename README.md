<h1 align="center">Hi 👋, I'm Your Name</h1>

### 📊 GitHub Stats

<p align="center">
<img src="https://github-stats-extended.vercel.app/api?username=OgabekHub&show_icons=true&hide_border=true&count_private=true&theme=radical" alt="GitHub Stats" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=OgabekHub&hide_border=true&theme=radical" alt="GitHub Streak" />
</p>

<p align="center">
<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=OgabekHub&layout=compact&hide_border=true&theme=radical" alt="Top Languages"/>
</p>

### 🐍 Contribution Snake

<details>
<summary>⚙️ <b>Snake animatsiyasini o'rnatish yo'riqnomasi</b> (ko'rish uchun bosing)</summary>

> 1. `OgabekHub/OgabekHub` reponi oching
> 2. `.github/workflows/snake.yml` faylini yarating:
> ```yaml
> name: Generate Snake
> on:
>   schedule:
>     - cron: "0 0 * * *"
>   workflow_dispatch:
> jobs:
>   generate:
>     runs-on: ubuntu-latest
>     steps:
>       - uses: Platane/snk@v3
>         with:
>           github_user_name: ${{ github.repository_owner }}
>           outputs: dist/github-contribution-grid-snake.svg?palette=github-dark
>       - uses: crazy-max/ghaction-github-pages@v3
>         with:
>           target_branch: output
>           build_dir: dist
>         env:
>           GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
> ```

</details>

<p align="center">
<img src="https://raw.githubusercontent.com/OgabekHub/OgabekHub/output/github-contribution-grid-snake.svg" alt="Snake animation"/>
</p>

---

<p align="center"><img src="https://komarev.com/ghpvc/?username=OgabekHub&label=Profile%20Views&color=7c5cfc&style=for-the-badge" alt="Profile Views"/></p>

---
<p align="center"><i>Generated with ❤️ using <a href="https://github-readme-generator-zeta.vercel.app" target="_blank">GitHub README Generator</a>. Star the repository on <a href="https://github.com/OgabekHub/github-readme-generator" target="_blank">GitHub</a>! ⭐</i></p>