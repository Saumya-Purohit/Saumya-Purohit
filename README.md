<!-- Replace with your personal information -->
<h1 align="center">Hi there! <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px"> I'm Saumya Purohit</h1>

<h3 align="center">A passionate Full Stack Developer from India</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/saumya-purohit-a9765a240/"><img src="https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/saumya-purohit-a9765a240/"/></a>
  <a href="https://github.com/Saumya-Purohit"><img src="https://img.shields.io/badge/-GitHub-black?style=flat-square&logo=Github&logoColor=white&link=https://github.com/Saumya-Purohit"/></a>
  <a href="https://saumya-purohit.netlify.app/"><img src="https://img.shields.io/badge/-Portfolio-9cf?style=flat-square&link=https://saumya-purohit.netlify.app/"/></a>
</p>

<p align="center">
  <img class="profile-pic" src="https://media.giphy.com/media/ASd0Ukj0y3qMM/giphy.gif" alt="Coding" width="400"/>
</p>

<style>
.profile-pic {
  animation: spin 5s linear infinite;
}

@keyframes spin {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

.skill-item:hover {
  transform: scale(1.1);
  transition: all 0.2s ease-in-out;
}
</style>

### 🌟 About Me
- 🎓 Computer Science and Engineering student at University of Petroleum and Energy Studies, India
- 💻 Full Stack Developer with experience in C++, Java, Node.js, MongoDB, AWS, and more
- 🚀 Passionate about Cloud Computing, DevOps, and creating innovative web solutions

## My Contribution Snake
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

  env:
    # a github token is required to fetch the contribution calendar from github API
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>

## GitHub Stats
!Saumya's GitHub stats


### 📊 GitHub Activity
<!-- Add a dynamically generated commit chart using a service like https://github.com/ashutosh00710/github-readme-activity-graph -->
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Saumya-Purohit&theme=xcode" alt="GitHub Activity Chart" width="600"/>
</p>



### 📫 Contact Me
- Email: saumyapurohit97@gmail.com
- LinkedIn: saumya-purohit-a9765a240
