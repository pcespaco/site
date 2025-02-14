# site
![image](https://github.com/user-attachments/assets/4f861564-0d7b-415e-8d6f-a1ed0caa2f5e)
# fontes e paletas
/* ======================== */
/*        FONTES           */
/* ======================== */
@import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@500&family=Roboto+Mono:wght@400&display=swap');

body {
    font-family: 'Roboto Mono', monospace;
    background: radial-gradient(circle, #1A2A6C, #000428);
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    min-height: 100vh;
    overflow-x: hidden;
}

h1, p, .button-hover {
    font-family: 'Orbitron', sans-serif;
}

/* ======================== */
/*      PALETA DE CORES     */
/* ======================== */
.btn-orange { background-color: #FF6F00; }
.text-orange { color: #FF6F00; }

.btn-blue { background-color: #1A2A6C; }
.btn-green { background-color: #A1A1A6; }
.btn-red, .btn-purple { background-color: #FF6F00; }

.text-gray { color: #4B5563; }

/* ======================== */
/*        BOTÕES            */
/* ======================== */
.button-hover {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    padding: 15px;
    transition: transform 0.2s ease-in-out;
    color: white;
    text-decoration: none;
    border-radius: 12px;
}

.button-hover:hover {
    transform: scale(1.05);
}

/* ======================== */
/*    EFEITOS VISUAIS       */
/* ======================== */
.custom-cursor {
    position: absolute;
    font-size: 2rem;
    pointer-events: none;
    transition: transform 0.05s linear;
}

.star {
    position: absolute;
    color: #fff;
    font-size: 1rem;
    animation: twinkle 3s infinite ease-in-out;
}

@keyframes twinkle {
    0%, 100% { opacity: 0; transform: scale(0.5); }
    50% { opacity: 1; transform: scale(1); }
}
