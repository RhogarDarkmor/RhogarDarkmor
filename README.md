<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ayslan Hugo - Perfil GitHub</title>
    <style>
        /* Variáveis de cores */
        :root {
            --primary-color: #2d4cc8;
            --secondary-color: #6c757d;
            --accent-color: #ff6b6b;
            --background-color: #f8f9fa;
            --card-background: #ffffff;
            --text-color: #333333;
            --light-text: #6c757d;
            --border-color: #dee2e6;
        }

        /* Reset e estilos base */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--background-color);
            color: var(--text-color);
            line-height: 1.6;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        /* Cabeçalho */
        header {
            text-align: center;
            padding: 30px 20px;
            background: linear-gradient(135deg, var(--primary-color), #1e2f78);
            color: white;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        .tagline {
            font-size: 1.2rem;
            margin-bottom: 15px;
            font-weight: 300;
        }

        /* Seções */
        section {
            background-color: var(--card-background);
            border-radius: 10px;
            padding: 25px;
            margin-bottom: 25px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08);
        }

        h2 {
            color: var(--primary-color);
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid var(--border-color);
        }

        h3 {
            color: var(--secondary-color);
            margin: 15px 0 10px;
        }

        /* Sobre mim */
        .about-list {
            list-style-type: none;
        }

        .about-list li {
            margin-bottom: 12px;
            padding-left: 25px;
            position: relative;
        }

        .about-list li:before {
            content: "•";
            color: var(--primary-color);
            font-weight: bold;
            position: absolute;
            left: 0;
        }

        /* Tecnologias */
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .skill-category {
            background-color: rgba(45, 76, 200, 0.05);
            padding: 15px;
            border-radius: 8px;
        }

        .skill-category h3 {
            color: var(--primary-color);
            text-align: center;
            margin-bottom: 15px;
        }

        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
        }

        .skill-tag {
            background-color: var(--primary-color);
            color: white;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.9rem;
        }

        /* Linha do tempo */
        .timeline {
            position: relative;
            padding-left: 30px;
        }

        .timeline:before {
            content: '';
            position: absolute;
            left: 0;
            top: 5px;
            bottom: 5px;
            width: 4px;
            background-color: var(--primary-color);
            border-radius: 2px;
        }

        .timeline-item {
            margin-bottom: 25px;
            position: relative;
        }

        .timeline-item:before {
            content: '';
            position: absolute;
            left: -33px;
            top: 5px;
            width: 16px;
            height: 16px;
            border-radius: 50%;
            background-color: var(--primary-color);
            border: 3px solid var(--card-background);
        }

        .timeline-year {
            font-weight: bold;
            color: var(--primary-color);
            margin-bottom: 5px;
        }

        /* Estatísticas */
        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .stat-card {
            background-color: rgba(45, 76, 200, 0.05);
            padding: 20px;
            border-radius: 8px;
        }

        .stat-card h3 {
            text-align: center;
            margin-bottom: 15px;
            color: var(--primary-color);
        }

        .stat-item {
            display: flex;
            justify-content: space-between;
            padding: 8px 0;
            border-bottom: 1px solid var(--border-color);
        }

        .stat-item:last-child {
            border-bottom: none;
        }

        /* Contato */
        .contact-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .contact-link {
            display: flex;
            align-items: center;
            text-decoration: none;
            color: var(--primary-color);
            font-weight: 500;
            padding: 10px 20px;
            border: 1px solid var(--primary-color);
            border-radius: 30px;
            transition: all 0.3s ease;
        }

        .contact-link:hover {
            background-color: var(--primary-color);
            color: white;
            transform: translateY(-2px);
        }

        /* Responsividade */
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            .skills-container, .stats-container {
                grid-template-columns: 1fr;
            }
            
            .contact-links {
                flex-direction: column;
                align-items: center;
            }
            
            .contact-link {
                width: 100%;
                justify-content: center;
            }
        }

        /* Destaques */
        .highlight {
            color: var(--accent-color);
            font-weight: 600;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ayslan Hugo</h1>
        <p class="tagline">Desenvolvedor em formação | Graduando em Sistemas de Informação</p>
        <p class="tagline">Apaixonado por tecnologia e soluções criativas</p>
    </header>

    <section id="about">
        <h2>Sobre mim</h2>
        <ul class="about-list">
            <li>Formado em Técnico em Informática (2021)</li>
            <li>Cursando Sistemas de Informação desde 2022, atualmente no 4º período</li>
            <li>Atuo como UI Designer na Enterprise Digital Lab desde 2021</li>
            <li>Aprendizado constante em Ruby on Rails desde 2021</li>
            <li>Entusiasta de metodologias ágeis, usuário de Visual Studio Code e focado em trabalhos em equipe</li>
        </ul>
    </section>

    <section id="skills">
        <h2>Tecnologias e Ferramentas</h2>
        <div class="skills-container">
            <div class="skill-category">
                <h3>Desenvolvimento</h3>
                <div class="skills-list">
                    <span class="skill-tag">Ruby on Rails</span>
                    <span class="skill-tag">JavaScript</span>
                    <span class="skill-tag">HTML5</span>
                    <span class="skill-tag">CSS3</span>
                    <span class="skill-tag">Python</span>
                </div>
            </div>
            <div class="skill-category">
                <h3>Banco de Dados</h3>
                <div class="skills-list">
                    <span class="skill-tag">PostgreSQL</span>
                    <span class="skill-tag">SQLite</span>
                    <span class="skill-tag">MySQL</span>
                </div>
            </div>
            <div class="skill-category">
                <h3>Ferramentas</h3>
                <div class="skills-list">
                    <span class="skill-tag">Git</span>
                    <span class="skill-tag">VS Code</span>
                    <span class="skill-tag">Figma</span>
                    <span class="skill-tag">GitHub</span>
                </div>
            </div>
        </div>
    </section>

    <section id="timeline">
        <h2>Linha do Tempo</h2>
        <div class="timeline">
            <div class="timeline-item">
                <div class="timeline-year">2021</div>
                <p>Conclusão do Técnico em Informática e início dos estudos em Ruby on Rails.</p>
            </div>
            <div class="timeline-item">
                <div class="timeline-year">2022</div>
                <p>Início da graduação em Sistemas de Informação e ingresso como UI Designer na Enterprise Digital Lab.</p>
            </div>
            <div class="timeline-item">
                <div class="timeline-year">2023</div>
                <p>Continuação da graduação em Sistemas de Informação (4º período atualmente) e aprofundamento em desenvolvimento web.</p>
            </div>
            <div class="timeline-item">
                <div class="timeline-year">Hoje</div>
                <p>Focado no desenvolvimento com Ruby on Rails e na construção de projetos pessoais para expandir meu portfólio.</p>
            </div>
        </div>
    </section>

    <section id="stats">
        <h2>Estatísticas do GitHub</h2>
        <div class="stats-container">
            <div class="stat-card">
                <h3>Estatísticas do Perfil</h3>
                <div class="stat-item">
                    <span>Commits:</span>
                    <span class="highlight">116</span>
                </div>
                <div class="stat-item">
                    <span>Repositórios:</span>
                    <span class="highlight">9</span>
                </div>
                <div class="stat-item">
                    <span>Seguidores:</span>
                    <span class="highlight">6</span>
                </div>
                <div class="stat-item">
                    <span>Seguindo:</span>
                    <span class="highlight">12</span>
                </div>
            </div>
            <div class="stat-card">
                <h3>Linguagens Mais Usadas</h3>
                <div class="stat-item">
                    <span>Ruby:</span>
                    <span class="highlight">45%</span>
                </div>
                <div class="stat-item">
                    <span>HTML/CSS:</span>
                    <span class="highlight">30%</span>
                </div>
                <div class="stat-item">
                    <span>JavaScript:</span>
                    <span class="highlight">15%</span>
                </div>
                <div class="stat-item">
                    <span>Python:</span>
                    <span class="highlight">10%</span>
                </div>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Onde me encontrar</h2>
        <div class="contact-links">
            <a href="https://github.com/ayslanhugo" class="contact-link">GitHub</a>
            <a href="https://linkedin.com/in/ayslanhugo" class="contact-link">LinkedIn</a>
            <a href="mailto:ayslanhugo@example.com" class="contact-link">E-mail</a>
            <a href="https://instagram.com/ayslanhugo" class="contact-link">Instagram</a>
        </div>
    </section>
</body>
</html>
