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
</style>

### 🌟 About Me
- 🎓 Computer Science and Engineering student at University of Petroleum and Energy Studies, India
- 💻 Full Stack Developer with experience in C++, Java, Node.js, MongoDB, AWS, and more
- 🚀 Passionate about Cloud Computing, DevOps, and creating innovative web solutions

### 🛠️ Skills
- **Languages**: C++, Java, JavaScript
- **Web Development**: HTML, CSS, Bootstrap, Node.js, React
- **Databases**: MongoDB, SQL
- **Tools & Technologies**: Git, GitHub, Docker, AWS, Heroku

### 💼 Projects
<!-- Add your top repositories with links and descriptions -->
- CataComb: Efficient data storage solution.
- BlockPharm: Blockchain-based pharmaceutical supply chain portal.
- Service-Setu: B2B website for an intuitive user experience.
- Extractor: AWS-based text extraction tool for handwritten documents.

### 📊 GitHub Activity
<!-- Add a dynamically generated commit chart using a service like https://github.com/ashutosh00710/github-readme-activity-graph -->
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Saumya-Purohit&theme=xcode" alt="GitHub Activity Chart" width="600"/>
</p>

### 🎮 Play a Game!
<p>Let's play rock-paper-scissors! Choose your move:</p>
<button onclick="play('rock')">Rock</button>
<button onclick="play('paper')">Paper</button>
<button onclick="play('scissors')">Scissors</button>
<p id="result"></p>

<script>
function play(userChoice) {
  const choices = ['rock', 'paper', 'scissors'];
  const computerChoice = choices[Math.floor(Math.random() * choices.length)];
  
  let result;
  
  if (userChoice === computerChoice) {
    result = 'It\'s a tie!';
  } else if (
    (userChoice === 'rock' && computerChoice === 'scissors') ||
    (userChoice === 'paper' && computerChoice === 'rock') ||
    (userChoice === 'scissors' && computerChoice === 'paper')
  ) {
    result = 'You win!';
  } else {
    result = 'You lose!';
  }
  
  document.getElementById('result').innerHTML = `Computer chose ${computerChoice}. ${result}`;
}
</script>

### 📫 Contact Me
- Email: saumyapurohit97@gmail.com
- LinkedIn: saumya-purohit-a9765a240
