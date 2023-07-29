# Slater
<h1 align="center">Bem-vindo! eu sou o Gustavo_L</h1>
<h1 align="center">Welcome! I'm Gustavo_L</h1>

<h3 align="center">Ao iniciar um novo projeto no Git, você se questiona sobre a terminologia a ser utilizada: "Origem" ou "Main"? Qual é a melhor opção do ponto de vista histórico e inclusivo? Vamos refletir sobre isso juntos! 🤔</h3>

![visitors](https://visitor-badge.laobi.icu/badge?page_id=NotSlater)

# _STATUS_

<svg width="300" height="335" viewBox="0 0 300 335" fill="none" xmlns="http://www.w3.org/2000/svg" role="img"
    aria-labelledby="descId"> <!-- cada caixa é igual a (50 = (335-286)) -->
    <title id="titleId"></title> <!-- height="335" viewBox="0 0 300 335" -->
    <desc id="descId"></desc>
    <style>
        .header {
            font: 600 18px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #70a5fd;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
        }

        @supports(-moz-appearance: auto) {

            /* Selector detects Firefox */
            .header {
                font-size: 15.5px;
            }
        }

        @keyframes slideInAnimation {
            from {
                width: 0;
            }

            to {
                width: calc(100%-100px);
            }
        }

        @keyframes growWidthAnimation {
            from {
                width: 0;
            }

            to {
                width: 100%;
            }
        }

        .stat {
            font: 600 14px 'Segoe UI', Ubuntu, "Helvetica Neue", Sans-Serif;
            fill: #38bdae;
        }

        @supports(-moz-appearance: auto) {

            /* Selector detects Firefox */
            .stat {
                font-size: 12px;
            }
        }

        .bold {
            font-weight: 700
        }

        .lang-name {
            font: 400 11px "Segoe UI", Ubuntu, Sans-Serif;
            fill: #38bdae;
        }

        .stagger {
            opacity: 0;
            animation: fadeInAnimation 0.3s ease-in-out forwards;
        }

        #rect-mask rect {
            animation: slideInAnimation 1s ease-in-out forwards;
        }

        .lang-progress {
            animation: growWidthAnimation 0.6s ease-in-out forwards;
        }



        /* Animations */
        @keyframes scaleInAnimation {
            from {
                transform: translate(-5px, 5px) scale(0);
            }

            to {
                transform: translate(-5px, 5px) scale(1);
            }
        }

        @keyframes fadeInAnimation {
            from {
                opacity: 0;
            }

            to {
                opacity: 1;
            }
        }
    </style>



    <rect data-testid="card-bg" x="0.5" y="0.5" rx="4.5" height="99%" stroke="#e4e2e2" width="299" fill="#1a1b27"
        stroke-opacity="1" />


    <g data-testid="card-title" transform="translate(25, 35)">
        <g transform="translate(0, 0)">
            <text x="0" y="0" class="header" data-testid="header">Experiencias</text>
        </g>
    </g>

    <!-- Linguagem de Programação: C++ -->
    <g data-testid="main-card-body" transform="translate(0, 55)">
        <svg data-testid="lang-items" x="25">
            <g transform="translate(0, 0)">
                <g class="stagger" style="animation-delay: 450ms">
                    <text data-testid="lang-name" x="2" y="15" class="lang-name">C++</text>
                    <text x="215" y="34" class="lang-name">78.85%</text>

                    <svg width="205" x="0" y="25">
                        <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"></rect>
                        <svg data-testid="lang-progress" width="78.85%">
                            <rect height="8" fill="#f34b7d" rx="5" ry="5" x="0" y="0" class="lang-progress"
                                style="animation-delay: 750ms;" />
                        </svg>
                    </svg>

                </g>
            </g>
            <!-- Linguagem de Programação: JavaScript -->
            <g transform="translate(0, 40)">
                <g class="stagger" style="animation-delay: 600ms">
                    <text data-testid="lang-name" x="2" y="15" class="lang-name">JavaScript</text>
                    <text x="215" y="34" class="lang-name">45.10%</text>

                    <svg width="205" x="0" y="25">
                        <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"></rect>
                        <svg data-testid="lang-progress" width="45.10%">
                            <rect height="8" fill="#f1e05a" rx="5" ry="5" x="0" y="0" class="lang-progress"
                                style="animation-delay: 900ms;" />
                        </svg>
                    </svg>

                </g>
            </g>
            <!-- Linguagem de Programação: C# -->
            <g transform="translate(0, 80)">
                <g class="stagger" style="animation-delay: 750ms">
                    <text data-testid="lang-name" x="2" y="15" class="lang-name">C</text>
                    <text x="215" y="34" class="lang-name">79.26%</text>

                    <svg width="205" x="0" y="25">
                        <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"></rect>
                        <svg data-testid="lang-progress" width="79.26%">
                            <rect height="8" fill="#555555" rx="5" ry="5" x="0" y="0" class="lang-progress"
                                style="animation-delay: 1050ms;" />
                        </svg>
                    </svg>

                </g>
            </g>
            <!-- Linguagem de Programação: C# -->
            <g transform="translate(0, 120)">
                <g class="stagger" style="animation-delay: 900ms">
                    <text data-testid="lang-name" x="2" y="15" class="lang-name">C#</text>
                    <text x="215" y="34" class="lang-name">45.91%</text>

                    <svg width="205" x="0" y="25">
                        <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"></rect>
                        <svg data-testid="lang-progress" width="45%">
                            <rect height="8" fill="#178600" rx="5" ry="5" x="0" y="0" class="lang-progress"
                                style="animation-delay: 1200ms;" />
                        </svg>
                    </svg>

                </g>
            </g>
            <!-- Linguagem de Programação: HTML -->
            <g transform="translate(0, 160)">
                <g class="stagger" style="animation-delay: 1050ms">
                    <text data-testid="lang-name" x="2" y="15" class="lang-name">HTML</text>
                    <text x="215" y="34" class="lang-name">67.88%</text>

                    <svg width="205" x="0" y="25">
                        <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"></rect>
                        <svg data-testid="lang-progress" width="67%">
                            <rect height="8" fill="#e34c26" rx="5" ry="5" x="0" y="0" class="lang-progress"
                                style="animation-delay: 1350ms;" />
                        </svg>
                    </svg>

                </g>
            </g>
            <!-- Linguagem de Programação: HTML -->
            <g transform="translate(0, 200)">
                <g class="stagger" style="animation-delay: 1050ms">
                    <text data-testid="lang-name" x="2" y="15" class="lang-name">HACK.exe</text>
                    <text x="215" y="34" class="lang-name">99.99%</text>

                    <svg width="205" x="0" y="25">
                        <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"></rect>
                        <svg data-testid="lang-progress" width="99%">
                            <rect height="8" fill="#03f0fc" rx="5" ry="5" x="0" y="0" class="lang-progress"
                                style="animation-delay: 1350ms;" />
                        </svg>
                    </svg>

                </g>
            </g>
            <!-- Linguagem de Programação: Python -->
            <g transform="translate(0, 240)">
                <g class="stagger" style="animation-delay: 1350ms">
                    <text data-testid="lang-name" x="2" y="15" class="lang-name">Python</text>
                    <text x="215" y="34" class="lang-name">57.25%</text>

                    <svg width="205" x="0" y="25">
                        <rect rx="5" ry="5" x="0" y="0" width="205" height="8" fill="#ddd"></rect>
                        <svg data-testid="lang-progress" width="57.25%">
                            <rect height="8" fill="#306998" rx="5" ry="5" x="0" y="0" class="lang-progress"
                                style="animation-delay: 1500ms;" />
                        </svg>
                    </svg>
                </g>
            </g>
        </svg>

    </g>
</svg>
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=NotSlater&theme=tokyonight)



- I’m currently working on **Python Automation, Game Hacking, and Reverse Engineering**

- Support/Help or Contact **Discord: slater#0666**

- Fun fact **I have been coding for 4 years!**

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="[https://en.wikipedia.org/wiki/Python](https://en.wikipedia.org/wiki/Python_(programming_language))" target="_blank"> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="[https://en.wikipedia.org/wiki/python](https://en.wikipedia.org/wiki/C%2B%2B)" target="_blank"> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://en.wikipedia.org/wiki/C_Sharp_(programming_language)" target="_blank"> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/><a href="https://en.wikipedia.org/wiki/Python_(programming_language)" target="_blank"> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://en.wikipedia.org/wiki/JavaScript" target="_blank"> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a><a href="https://en.wikipedia.org/wiki/Node.js" target="_blank"> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/>
