<h1><b id="typewriter"></b></h1>
<script>
const phrases = [
    "Eu sou o André O. Marcal 👨‍💻",
    
];
let currentPhrase = 0;
let currentChar = 0;
let isDeleting = false;
let loopStart = 0;
const typewriter = document.getElementById('typewriter');

function type() {
    const phrase = phrases[currentPhrase];
    if (!isDeleting) {
        typewriter.innerHTML = phrase.substring(0, currentChar + 1);
        currentChar++;
        if (currentChar === phrase.length) {
            setTimeout(() => isDeleting = true, 1200);
            setTimeout(type, 1200);
            return;
        }
    } else {
        typewriter.innerHTML = phrase.substring(0, currentChar - 1);
        currentChar--;
        if (currentChar === 2) { // "Eu"
            isDeleting = false;
            currentPhrase = (currentPhrase + 1) % phrases.length;
            setTimeout(type, 800);
            return;
        }
    }
    setTimeout(type, isDeleting ? 60 : 100);
}
type();
</script>

<div align="left">

  
🔭 <b>Eu sou Desenvolvedor Web...</b>

📚 Academico em Analise e Desenvolvimento de Sistema 3/5..

💬 E como objetivo futuramente quero atuar trabalhando como full stack..

🌱 Estou estudando Web Design e UI/UX Design para uma boa desenvoltura em meus projetos..

</div>

<h1>Redes Sociais</h1>
<div align="left">
  
  <a href="https://www.linkedin.com/in/andre-mar%C3%A7al-b506b7329/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"  />
  </a>
  <a href="https://api.whatsapp.com/send?phone=5585996485562" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/whatsapp/default.svg" width="52" height="40" alt="whatsapp logo"  />
  </a>
  <a href="mailto:andremarcal.dev@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg" width="52" height="40" alt="gmail logo"  />
  </a>
  <a href="https://www.facebook.com/andre.oliveira.marcal" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/facebook/default.svg" width="52" height="40" alt="facebook logo"  />
  </a>
  <a href="https://www.instagram.com/invites/contact/?igsh=uml4t9x8n2do&utm_content=sd4l4rj" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/instagram/default.svg" width="52" height="40" alt="instagram logo"  />
  </a>
</div>



<br>
<br>
<div align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=Marcal-Andre&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=pt-br&hide_border=false&order=1" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Marcal-Andre&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" height="150" alt="languages graph"  />
</div>
<br>

  <div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40px" alt="html5 logo"  />_
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" height="40" alt="bootstrap logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="40" alt="php logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="mysql logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" height="40" alt="firebase logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=aws" height="40" alt="amazonwebservices logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" height="40" alt="azure logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" height="40" alt="figma logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" alt="github logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" alt="git logo"  />
