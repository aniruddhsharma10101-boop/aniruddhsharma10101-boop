<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile | Programming Languages</title>
    <!-- Devicon for programming icons -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css">
    <style>
        :root {
            --primary-color: #2d2d2d;
            --secondary-color: #58a6ff;
            --background-color: #0d1117;
            --card-bg: #161b22;
            --text-color: #c9d1d9;
            --accent-color: #238636;
        }

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

        header {
            display: flex;
            align-items: center;
            margin-bottom: 40px;
            padding: 20px 0;
            border-bottom: 1px solid #30363d;
        }

        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid var(--secondary-color);
            margin-right: 30px;
            object-fit: cover;
        }

        .header-text h1 {
            font-size: 2.5rem;
            margin-bottom: 5px;
            color: white;
        }

        .header-text p {
            font-size: 1.2rem;
            opacity: 0.8;
        }

        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 15px;
        }

        .social-links a {
            color: var(--text-color);
            font-size: 1.5rem;
            transition: color 0.3s;
        }

        .social-links a:hover {
            color: var(--secondary-color);
        }

        section {
            margin-bottom: 40px;
        }

        h2 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: white;
            border-left: 4px solid var(--accent-color);
            padding-left: 15px;
        }

        .about {
            background-color: var(--card-bg);
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
        }

        .skill-category {
            background-color: var(--card-bg);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .skill-category h3 {
            margin-bottom: 15px;
            color: var(--secondary-color);
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(80px, 1fr));
            gap: 15px;
        }

        .skill-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            transition: transform 0.3s;
        }

        .skill-item:hover {
            transform: translateY(-5px);
        }

        .skill-icon {
            font-size: 2.5rem;
            margin-bottom: 8px;
            color: var(--secondary-color);
        }

        .skill-name {
            font-size: 0.9rem;
            text-align: center;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
        }

        .project-card {
            background-color: var(--card-bg);
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s;
        }

        .project-card:hover {
            transform: translateY(-5px);
        }

        .project-content {
            padding: 20px;
        }

        .project-title {
            font-size: 1.2rem;
            margin-bottom: 10px;
            color: white;
        }

        .project-description {
            margin-bottom: 15px;
            font-size: 0.9rem;
        }

        .project-tech {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-bottom: 15px;
        }

        .tech-tag {
            background-color: var(--primary-color);
            color: var(--secondary-color);
            padding: 4px 8px;
            border-radius: 15px;
            font-size: 0.8rem;
        }

        .project-link {
            display: inline-block;
            color: var(--secondary-color);
            text-decoration: none;
            font-weight: 500;
        }

        .project-link:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            border-top: 1px solid #30363d;
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            header {
                flex-direction: column;
                text-align: center;
            }
            
            .profile-pic {
                margin-right: 0;
                margin-bottom: 20px;
            }
            
            .social-links {
                justify-content: center;
            }
            
            .skills-container,
            .projects {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <img src="https://avatars.githubusercontent.com/u/583231?v=4" alt="Profile Picture" class="profile-pic">
        <div class="header-text">
            <h1>Your Name</h1>
            <p>Full Stack Developer & Open Source Enthusiast</p>
            <div class="social-links">
                <a href="https://github.com/yourusername" aria-label="GitHub">
                    <i class="devicon-github-original"></i>
                </a>
                <a href="https://linkedin.com/in/yourusername" aria-label="LinkedIn">
                    <i class="devicon-linkedin-plain"></i>
                </a>
                <a href="https://twitter.com/yourusername" aria-label="Twitter">
                    <i class="devicon-twitter-original"></i>
                </a>
                <a href="mailto:youremail@example.com" aria-label="Email">
                    <i class="devicon-google-plain"></i>
                </a>
            </div>
        </div>
    </header>

    <section class="about">
        <h2>About Me</h2>
        <p>Hello! I'm a passionate software developer with expertise in multiple programming languages and technologies. I love building innovative solutions and contributing to open-source projects. When I'm not coding, you can find me reading tech blogs, hiking, or playing video games.</p>
        <p>I believe in continuous learning and sharing knowledge with the developer community. Feel free to explore my projects or get in touch with me!</p>
    </section>

    <section class="skills">
        <h2>Skills & Technologies</h2>
        <div class="skills-container">
            <div class="skill-category">
                <h3>Languages</h3>
                <div class="skills-grid">
                    <div class="skill-item">
                        <i class="devicon-javascript-plain colored skill-icon"></i>
                        <span class="skill-name">JavaScript</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-typescript-plain colored skill-icon"></i>
                        <span class="skill-name">TypeScript</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-python-plain colored skill-icon"></i>
                        <span class="skill-name">Python</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-java-plain colored skill-icon"></i>
                        <span class="skill-name">Java</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-cplusplus-plain colored skill-icon"></i>
                        <span class="skill-name">C++</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-go-plain colored skill-icon"></i>
                        <span class="skill-name">Go</span>
                    </div>
                </div>
            </div>

            <div class="skill-category">
                <h3>Frontend</h3>
                <div class="skills-grid">
                    <div class="skill-item">
                        <i class="devicon-react-original colored skill-icon"></i>
                        <span class="skill-name">React</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-vuejs-plain colored skill-icon"></i>
                        <span class="skill-name">Vue.js</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-angularjs-plain colored skill-icon"></i>
                        <span class="skill-name">Angular</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-html5-plain colored skill-icon"></i>
                        <span class="skill-name">HTML5</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-css3-plain colored skill-icon"></i>
                        <span class="skill-name">CSS3</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-sass-original colored skill-icon"></i>
                        <span class="skill-name">Sass</span>
                    </div>
                </div>
            </div>

            <div class="skill-category">
                <h3>Backend</h3>
                <div class="skills-grid">
                    <div class="skill-item">
                        <i class="devicon-nodejs-plain colored skill-icon"></i>
                        <span class="skill-name">Node.js</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-express-original skill-icon"></i>
                        <span class="skill-name">Express</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-django-plain colored skill-icon"></i>
                        <span class="skill-name">Django</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-flask-original skill-icon"></i>
                        <span class="skill-name">Flask</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-spring-plain colored skill-icon"></i>
                        <span class="skill-name">Spring</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-nginx-original colored skill-icon"></i>
                        <span class="skill-name">Nginx</span>
                    </div>
                </div>
            </div>

            <div class="skill-category">
                <h3>Tools & Others</h3>
                <div class="skills-grid">
                    <div class="skill-item">
                        <i class="devicon-docker-plain colored skill-icon"></i>
                        <span class="skill-name">Docker</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-git-plain colored skill-icon"></i>
                        <span class="skill-name">Git</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-amazonwebservices-plain colored skill-icon"></i>
                        <span class="skill-name">AWS</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-mysql-plain colored skill-icon"></i>
                        <span class="skill-name">MySQL</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-mongodb-plain colored skill-icon"></i>
                        <span class="skill-name">MongoDB</span>
                    </div>
                    <div class="skill-item">
                        <i class="devicon-linux-plain colored skill-icon"></i>
                        <span class="skill-name">Linux</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="projects-section">
        <h2>Featured Projects</h2>
        <div class="projects">
            <div class="project-card">
                <div class="project-content">
                    <h3 class="project-title">E-Commerce Platform</h3>
                    <p class="project-description">A full-stack e-commerce solution with React frontend and Node.js backend.</p>
                    <div class="project-tech">
                        <span class="tech-tag">React</span>
                        <span class="tech-tag">Node.js</span>
                        <span class="tech-tag">MongoDB</span>
                    </div>
                    <a href="#" class="project-link">View Project →</a>
                </div>
            </div>

            <div class="project-card">
                <div class="project-content">
                    <h3 class="project-title">Task Management App</h3>
                    <p class="project-description">A collaborative task management application with real-time updates.</p>
                    <div class="project-tech">
                        <span class="tech-tag">Vue.js</span>
                        <span class="tech-tag">Firebase</span>
                        <span class="tech-tag">Vuetify</span>
                    </div>
                    <a href="#" class="project-link">View Project →</a>
                </div>
            </div>

            <div class="project-card">
                <div class="project-content">
                    <h3 class="project-title">Weather Dashboard</h3>
                    <p class="project-description">A responsive weather dashboard that displays forecasts from multiple providers.</p>
                    <div class="project-tech">
                        <span class="tech-tag">JavaScript</span>
                        <span class="tech-tag">API</span>
                        <span class="tech-tag">Chart.js</span>
                    </div>
                    <a href="#" class="project-link">View Project →</a>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2023 Your Name. Made with ❤️ and <i class="devicon-devicon-plain"></i></p>
        <p>Icons provided by <a href="https://devicon.dev/" target="_blank">Devicon</a></p>
    </footer>
</body>
</html>
