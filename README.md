### Olá! Eu sou o Yuri Silva dos Santos


- 🔭 Amante da Tecnologia.
- 🌱 Estudante de Análise e Desenvolvimento de Sistemas 2° Semestre
- 🍷 Focado e Super Disciplinado
- Você tem poder sobre sua mente – não sobre eventos externos
 <div align="center">
  <a href="https://github.com/davidluiz91">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=yuridubi12&show_icons=true&theme=cobalt&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yuridubi12&layout=compact&langs_count=7&theme=cobalt"/>
</div>
 
<div style="display: inline_block"><br>
  <img align="center" alt="David-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="David-React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
  <img align="center" alt="David-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="David-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" />
  
  <img align="center" alt="David-figma" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" />
  <img align="center" alt="David-figma" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" />
  <img align="center" alt="David-figma" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sass/sass-original.svg" />
  <img align="center" alt="David-figma" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" />
  <img align="center" alt="David-figma" height="30" width="40"src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original-wordmark.svg" />
<img align="center" alt="David-figma" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ruby/ruby-original.svg" />
<img align="center" alt="David-figma" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" />
<img align="center" alt="David-figma" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/illustrator/illustrator-plain.svg" />
<img align="center" alt="David-figma" height="30" width="40"  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" />
<img align="center" alt="David-figma" height="30" width="40"  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/photoshop/photoshop-plain.svg" />
          
          
          
          
          
          
          
          
          
  
          
          
  </div>
  
##

<div> 

  <a href="https://www.instagram.com/dub.bugs/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "yuridubi14@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/yuri-silva-dos-santos-b5998b1a0/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  
</div>
 name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: jussaraalves
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  

