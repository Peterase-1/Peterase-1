<!DOCTYPE html>
<html>
<head>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .tech-icon:hover { transform: scale(1.1); transition: all 0.3s ease; }
        .wave { animation: wave 2s infinite; display: inline-block; }
        @keyframes wave { 0%,100% { transform: rotate(0deg); } 25% { transform: rotate(20deg); } 75% { transform: rotate(-15deg); } }
    </style>
</head>
<body class="bg-gray-900 text-white p-6 max-w-3xl mx-auto">
    <div class="flex items-center mb-8">
        <img src="" class="w-24 h-24 rounded-full border-4 border-blue-500 mr-6">
        <div>
            <h1 class="text-3xl font-bold">Hey <span class="wave">👋</span>, I'm Peter</h1>
            <p class="text-blue-300">Aspiring Full-Stack Developer | Learning One Line at a Time</p>
        </div>
    </div>
    <div class="bg-gray-800 rounded-xl p-6 mb-6">
        <h2 class="text-xl font-bold mb-4 border-b border-blue-500 pb-2">About Me</h2>
        <p class="mb-4">🌱 Currently learning <strong>Computer Science, Python, JavaScript, C++</strong></p>
        <p class="mb-4">💬 Ask me about <strong>Python, HTML and CSS</strong></p>
        <p class="mb-4">📫 Reach me at <a href="mailto:pasegid@gmail.com" class="text-blue-400">pasegid@gmail.com</a></p>
        <p class="text-sm bg-gray-700 p-3 rounded-lg">⚡ Fun fact: Some people say music is a universal language... I think code is too, but with less rhythm and more bugs to fix!</p>
    </div>
    <div class="bg-gray-800 rounded-xl p-6 mb-6">
        <h2 class="text-xl font-bold mb-4 border-b border-blue-500 pb-2">Tech Stack</h2>
        <div class="grid grid-cols-3 gap-4">
            <div class="tech-icon text-center p-3">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" class="w-12 h-12 mx-auto mb-2">
                <span>Python</span>
            </div>
            <div class="tech-icon text-center p-3">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" class="w-12 h-12 mx-auto mb-2">
                <span>JavaScript</span>
            </div>
            <div class="tech-icon text-center p-3">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" class="w-12 h-12 mx-auto mb-2">
                <span>C++</span>
            </div>
            <div class="tech-icon text-center p-3">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" class="w-12 h-12 mx-auto mb-2">
                <span>HTML5</span>
            </div>
            <div class="tech-icon text-center p-3">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" class="w-12 h-12 mx-auto mb-2">
                <span>CSS3</span>
            </div>
            <div class="tech-icon text-center p-3">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" class="w-12 h-12 mx-auto mb-2">
                <span>Git</span>
            </div>
        </div>
    </div>
    <div class="bg-gray-800 rounded-xl p-6">
        <h2 class="text-xl font-bold mb-4 border-b border-blue-500 pb-2">Connect</h2>
        <div class="flex justify-center space-x-4">
            <a href="#" class="bg-gray-700 hover:bg-blue-600 w-12 h-12 rounded-full flex items-center justify-center transition">
                <i class="fab fa-github text-xl"></i>
            </a>
            <a href="#" class="bg-gray-700 hover:bg-blue-400 w-12 h-12 rounded-full flex items-center justify-center transition">
                <i class="fab fa-twitter text-xl"></i>
            </a>
            <a href="#" class="bg-gray-700 hover:bg-blue-700 w-12 h-12 rounded-full flex items-center justify-center transition">
                <i class="fab fa-linkedin-in text-xl"></i>
            </a>
            <a href="mailto:pasegid@gmail.com" class="bg-gray-700 hover:bg-red-500 w-12 h-12 rounded-full flex items-center justify-center transition">
                <i class="fas fa-envelope text-xl"></i>
            </a>
        </div>
    </div>
</body>
</html>
