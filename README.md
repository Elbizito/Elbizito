# 💼 Portfólio - Gabriel Lins

Este é meu portfólio pessoal como Desenvolvedor Web Frontend, desenvolvido com HTML, CSS e um toque de JavaScript. Projeto criado para apresentar minhas habilidades e experiências como estudante de Análise e Desenvolvimento de Sistemas.

---

## ✨ Sobre Mim

Sou Gabriel Lins, estudante de ADS com 17 anos, apaixonado por desenvolvimento web e UX/UI Design. Estou sempre em busca de novos desafios e aprendizados, com foco em tecnologias frontend e interfaces modernas.

---

## 🚀 Tecnologias Utilizadas

- HTML5
- CSS3

---

## 🌐 Visualizar Online

🔗 Acesse meu portfólio no GitHub Pages:  
**https://seuusuario.github.io/portfolio**

---

## 💻 Códigos do Projeto

<details>
<summary><strong>📄 index.html</strong></summary>

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Perfil - Desenvolvedor Web</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <div class="container">
        <header class="header">
            <div class="profile-info">
                <h1>Gabriel Lins</h1>
                <p class="title">Desenvolvedor Frontend | Formado em ADS</p>
                <p class="age">17 anos • SENAI - Análise e Desenvolvimento de Sistemas</p>
                <p class="description">Iniciante apaixonado por desenvolvimento web, com foco em frontend e interesse crescente em UX/UI Design.</p>
                <div class="social-links">
                    <a href="https://github.com/Elbizito" target="_blank"><i class="fab fa-github"></i></a>
                    <a href="https://linkedin.com/in/gabriel-lins-358239351" target="_blank"><i class="fab fa-linkedin"></i></a>
                    <a href="mailto:gabriellinssoares@gmail.com"><i class="fas fa-envelope"></i></a>
                </div>
            </div>
            <div class="profile-img">
                <img src="perfillins.png" alt="Gabriel Lins">
            </div>
        </header>

        <section class="about">
            <h2><i class="fas fa-user"></i> Sobre Mim</h2>
            <p>
                Técnico de Análise e Desenvolvimento de Sistemas pelo SENAI, com 17 anos e uma grande paixão por tecnologia. 
                Atualmente me especializando em desenvolvimento frontend, com interesse crescente em UX/UI Design. 
                Sempre em busca de novos conhecimentos e desafios no mundo do desenvolvimento web.
            </p>
        </section>

        <section class="skills">
            <h2><i class="fas fa-code"></i> Tecnologias</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <i class="fab fa-html5"></i>
                    <h3>HTML5</h3>
                    <div class="skill-bar"><div class="skill-progress" data-skill="75"></div></div>
                </div>
                <div class="skill-card">
                    <i class="fab fa-css3-alt"></i>
                    <h3>CSS3</h3>
                    <div class="skill-bar"><div class="skill-progress" data-skill="70"></div></div>
                </div>
                <div class="skill-card">
                    <i class="fab fa-js-square"></i>
                    <h3>JavaScript</h3>
                    <div class="skill-bar"><div class="skill-progress" data-skill="60"></div></div>
                </div>
                <div class="skill-card">
                    <i class="fab fa-python"></i>
                    <h3>Python</h3>
                    <div class="skill-bar"><div class="skill-progress" data-skill="45"></div></div>
                </div>
                <div class="skill-card">
                    <i class="fab fa-figma"></i>
                    <h3>Figma</h3>
                    <div class="skill-bar"><div class="skill-progress" data-skill="40"></div></div>
                </div>
                <div class="skill-card">
                    <i class="fa-solid fa-database"></i>
                    <h3>MySQL</h3>
                    <div class="skill-bar"><div class="skill-progress" data-skill="40"></div></div>
                </div>
                <div class="skill-card">
                    <i class="fa-brands fa-node"></i>
                    <h3>Node.js</h3>
                    <div class="skill-bar"><div class="skill-progress" data-skill="40"></div></div>
                </div>
                <div class="skill-card">
                    <i class="fab fa-react"></i>
                    <h3>React</h3>
                    <div class="skill-bar"><div class="skill-progress" data-skill="35"></div></div>
                </div>
            </div>
        </section>

        <section class="contact">
            <h2><i class="fas fa-envelope"></i> Contato</h2>
            <p>Interessado em projetos colaborativos ou oportunidades de aprendizado? Vamos conversar!</p>
            <div class="contact-buttons">
                <a href="mailto:gabriel.lins@gmail.com" class="btn primary"><i class="fas fa-envelope"></i> Email</a>
                <a href="https://linkedin.com/in/gabriel-lins-358239351" class="btn secondary" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
            </div>
        </section>
    </div>
    <script src="script.js"></script>
</body>
</html>
/* Estilos base, container, e fundo geral */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #0a0a0a;
    min-height: 100vh;
    color: #e5e5e5;
    line-height: 1.6;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 2rem;
}

/* Header estilizado com imagem e texto */
.header {
    background: rgba(20, 20, 20, 0.8);
    backdrop-filter: blur(10px);
    border-radius: 15px;
    padding: 2rem;
    margin-bottom: 2rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 2rem;
    box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
    border: 1px solid rgba(255, 255, 255, 0.1);
}

/* Cards de habilidades */
.skill-card {
    text-align: center;
    padding: 1.5rem;
    border-radius: 12px;
    background: rgba(30, 30, 30, 0.6);
    border: 1px solid rgba(255, 255, 255, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.skill-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 12px 40px rgba(79, 70, 229, 0.2);
}

.skill-bar {
    width: 100%;
    height: 8px;
    background: rgba(255, 255, 255, 0.1);
    border-radius: 10px;
    overflow: hidden;
}
.skill-progress {
    height: 100%;
    background: linear-gradient(90deg, #4f46e5, #7c3aed);
    border-radius: 10px;
    transition: width 2s ease;
    animation: fillBar 2s ease-in-out;
}

@keyframes fillBar {
    from { width: 0%; }
}
