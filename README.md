☕ Serenatto - Site de Cafeteria
Bem-vindo ao site da Serenatto, uma cafeteria fictícia feita com muito carinho e um toque de café! Feito como parte do curso da Alura, esse projeto usa HTML, CSS e JavaScript pra criar uma experiência moderna, bonita e responsiva.

🧰 Tecnologias usadas
HTML5

CSS3 (com Bootstrap)

JavaScript

🌗 Modo Noturno
Temos modo claro e modo escuro! É só ativar o botão que a mágica acontece. ✨
O JavaScript muda o tema via data-bs-theme, e o CSS cuida do resto.

js
Copiar
Editar
// Trecho JS que troca o tema
const inputCheck = document.querySelector('#modo-noturno')
const body = document.querySelector('body')

inputCheck.addEventListener('click', () => {
  const modo = inputCheck.checked ? 'dark' : 'light'
  body.setAttribute('data-bs-theme', modo)
})
🎨 Paleta de Cores
Usamos variáveis CSS com tons que combinam com café:

css
Copiar
Editar
--bege: #E6E0D6;
--marrom: #816D4F;
--marrom-claro: #B29463;
📸 Imagens e Banners
As seções principais usam banners com background-attachment: fixed, dando aquele efeito bonito de paralaxe.

📦 Organização
O projeto está dividido em:

index.html

style.css

script.js

Pasta assets/ com imagens e ícones

💡 Projeto feito para aprender
Esse site foi feito com base em um projeto da Alura para praticar conceitos como responsividade, variáveis CSS, modo noturno e Bootstrap.

