<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rajesh N - Full Stack Developer</title>
    <style>
        :root {
            --bg-color: #0d1117;
            --card-bg: #161b22;
            --text-main: #c9d1d9;
            --text-muted: #8b949e;
            --accent: #58a6ff;
            --border: #30363d;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            font-family: Verdana, sans-serif; /* VERDANA APPLIED HERE */
            line-height: 1.6;
            display: flex;
            justify-content: center;
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 900px;
            width: 100%;
            display: flex;
            flex-direction: column;
            gap: 24px;
        }

        /* --- Header Section --- */
        header {
            text-align: center;
            padding: 40px 0 20px;
        }

        h1 {
            font-size: 2rem;
            color: #fff;
            margin-bottom: 10px;
            font-weight: 700;
        }

        h3 {
            color: var(--text-muted);
            font-weight: 400;
            font-size: 1.1rem;
        }

        /* --- Badges --- */
        .top-bar {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
            margin-bottom: 20px;
        }

        .badge {
            display: inline-flex;
            align-items: center;
            text-decoration: none;
        }

        /* --- Sections Generic --- */
        section {
            background: var(--card-bg);
            border: 1px solid var(--border);
            border-radius: 8px;
            padding: 24px;
        }

        h2 {
            font-size: 1.2rem;
            color: #fff;
            margin-bottom: 20px;
            border-left: 4px solid var(--accent);
            padding-left: 10px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* --- Connect Section --- */
        .social-links {
            display: flex;
            gap: 20px;
            justify-content: flex-start;
        }

        .social-links a {
            display: block;
        }

        /* --- Tool Icons (Horizontal Styling, NO HOVER) --- */
        .tech-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: flex-start;
            align-items: center;
        }

        .tech-icon {
            width: 50px;
            height: 50px;
            display: flex;
            align-items: center;
            justify-content: center;
            /* NO HOVER EFFECTS APPLIED HERE */
        }

        .tech-icon img {
            width: 100%;
            height: 100%;
            object-fit: contain;
        }

        /* --- GitHub Stats Grid --- */
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .stat-card {
            background: rgba(255,255,255,0.02);
            border-radius: 6px;
            padding: 10px;
            overflow: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .full-width {
            grid-column: 1 / -1;
        }

        /* --- Trophy Section (Relocated) --- */
        .trophy-container {
            text-align: center;
            background: var(--card-bg);
            border: 1px solid var(--border);
            border-radius: 8px;
            padding: 24px;
        }

        .trophy-container img {
            max-width: 100%;
            height: auto;
        }

        /* Responsive */
        @media (max-width: 600px) {
            h1 { font-size: 1.5rem; }
            .tech-grid { justify-content: center; }
            .social-links { justify-content: center; }
        }
    </style>
</head>
<body>

    <div class="container">
        
        <header>
            <h1>Hi 👋, I'm Rajesh N</h1>
            <h3>A passionate full stack developer from India</h3>
            
            <div class="top-bar">
                <!-- Profile Views -->
                <a href="#" class="badge">
                    <img src="https://komarev.com/ghpvc/?username=rajeshnraj2004&label=Profile%20views&color=0e75b6&style=flat" alt="rajeshnraj2004" />
                </a>
                <!-- Twitter Placeholder -->
                <a href="https://twitter.com/" target="blank" class="badge">
                    <img src="https://img.shields.io/twitter/follow/?logo=twitter&style=for-the-badge" alt="" />
                </a>
            </div>
        </header>

        <section>
            <h2>Connect with me</h2>
            <div class="social-links">
                <a href="https://instagram.com/iamrajesh.30" target="blank">
                    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="iamrajesh.30" height="30" width="40" />
                
            </div>
        </section>

        <section>
            <h2>Languages and Tools</h2>
            <!-- Horizontal Flex Container for Icons -->
            <div class="tech-grid">
                
                <div class="tech-icon">
                    <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> 
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> 
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> 
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> 
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://expressjs.com" target="_blank" rel="noreferrer"> 
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> 
                        <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> 
                        <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://cloud.google.com" target="_blank" rel="noreferrer"> 
                        <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> 
                        <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> 
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> 
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> 
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> 
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://nodejs.org" target="_blank" rel="noreferrer"> 
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://www.php.net" target="_blank" rel="noreferrer"> 
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://www.python.org" target="_blank" rel="noreferrer"> 
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> 
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://reactnative.dev/" target="_blank" rel="noreferrer"> 
                        <img src="https://reactnative.dev/img/header_logo.svg" alt="reactnative" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://redux.js.org" target="_blank" rel="noreferrer"> 
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="redux" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> 
                        <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> 
                        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" /> 
                    </a> 
                </div>

                <div class="tech-icon">
                    <a href="https://unity.com/" target="_blank" rel="noreferrer"> 
                        <img src="https://www.vectorlogo.zone/logos/unity3d/unity3d-icon.svg" alt="unity" /> 
                    </a> 
                </div>

            </div>
        </section>

        <section>
            <h2>GitHub Stats</h2>
            <div class="stats-grid">
                <!-- Top Languages -->
                <div class="stat-card">
                    <img src="https://github-readme-stats.vercel.app/api/top-langs?username=rajeshnraj2004&show_icons=true&locale=en&layout=compact&bg_color=161b22&title_color=58a6ff&text_color=c9d1d9&icon_color=58a6ff&border_color=30363d" alt="rajeshnraj2004" />
                </div>

                <!-- General Stats -->
                <div class="stat-card">
                    <img src="https://github-readme-stats.vercel.app/api?username=rajeshnraj2004&show_icons=true&locale=en&bg_color=161b22&title_color=58a6ff&text_color=c9d1d9&icon_color=58a6ff&border_color=30363d" alt="rajeshnraj2004" />
                </div>

                <!-- Streak Stats (Full Width) -->
                <div class="stat-card full-width">
                    <img src="https://github-readme-streak-stats.herokuapp.com/?user=rajeshnraj2004&&background=161b22&stroke=30363d&ring=58a6ff&fire=58a6ff&currStreakNum=fff&currStreakLabel=fff&sideLabels=8b949e&sideNums=fff&dates=8b949e" alt="rajeshnraj2004" />
                </div>
            </div>
        </section>

        <!-- Trophy Section MOVED HERE (After Stats) -->
        <div class="trophy-container">
            <h2>Trophies</h2>
            <a href="https://github.com/ryo-ma/github-profile-trophy" target="_blank">
                <img src="https://github-profile-trophy.vercel.app/?username=rajeshnraj2004&column=4&margin-w=8&margin-h=8&no-bg=true&no-frame=true" alt="rajeshnraj2004" />
            </a>
        </div>

    </div>

</body>
</html>
