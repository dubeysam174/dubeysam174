# 💫 About Me:
I'm currently working on FluffyFriends (FullStack website for petCare)<br>Looking to collaborate on full-stack apps using Node.js & React<br>Currently learning authentication systems (JWT, security best practices) and TypeScript<br>Ask me about React, Node.js, REST APIs  
Not Perfect, Just Consistent


## 🌐 Socials:
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/_samarth_dubey_) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/samarthdubey30) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:dubeysamarth174@gmail.com) 

# 💻 Tech Stack:

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nodejs,express,mongodb,mysql,redis,docker,git,github,vscode,postman,cpp" />
</p>


name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    permissions:
      contents: write

    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: dubeysam174
          outputs: |
            dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=dubeysam174&limit=5&theme=dark&combine_all_yearly_contributions=true)

---
[![](https://visitcount.itsvg.in/api?id=dubeysam174&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
