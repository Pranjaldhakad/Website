<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pranjal Dhakad - Web Developer Portfolio</title>
    <link href="./dist/output.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        /* Optional: Custom CSS for the typing effect if not using a plugin directly */
        /* This is outside strict "Tailwind only" but common for dynamic effects */
        .typing-effect::after {
            content: '|';
            display: inline-block;
            animation: blink-caret .75s step-end infinite;
        }

        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: currentColor; }
        }
    </style>
</head>
<body class="font-poppins text-gray-800 bg-gray-50">

    <nav class="bg-white shadow-lg fixed w-full z-50 top-0">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#home" class="text-2xl font-bold text-blue-600 hover:text-blue-800 transition duration-300">Pranjal Dhakad</a>
            <div class="hidden md:flex space-x-8">
                <a href="#home" class="text-gray-600 hover:text-blue-600 font-medium transition duration-300">Home</a>
                <a href="#about" class="text-gray-600 hover:text-blue-600 font-medium transition duration-300">About Me</a>
                <a href="#projects" class="text-gray-600 hover:text-blue-600 font-medium transition duration-300">Projects</a>
                <a href="#contact" class="text-gray-600 hover:text-blue-600 font-medium transition duration-300">Contact</a>
            </div>
            <button id="mobile-menu-button" class="md:hidden text-gray-600 hover:text-blue-600 focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
            </button>
        </div>
        <div id="mobile-menu" class="hidden md:hidden bg-white py-2 shadow-md">
            <a href="#home" class="block px-6 py-2 text-gray-700 hover:bg-blue-50 hover:text-blue-600 transition duration-300">Home</a>
            <a href="#about" class="block px-6 py-2 text-gray-700 hover:bg-blue-50 hover:text-blue-600 transition duration-300">About Me</a>
            <a href="#projects" class="block px-6 py-2 text-gray-700 hover:bg-blue-50 hover:text-blue-600 transition duration-300">Projects</a>
            <a href="#contact" class="block px-6 py-2 text-gray-700 hover:bg-blue-50 hover:text-blue-600 transition duration-300">Contact</a>
        </div>
    </nav>

    <section id="home" class="min-h-screen flex flex-col justify-center items-center text-center p-8 pt-24 bg-gradient-to-r from-blue-500 to-purple-600 text-white relative">
        <div class="absolute inset-0 bg-pattern opacity-10"></div> <div class="relative z-10">
            <img src="./images/profile.jpg" alt="Pranjal Dhakad" class="w-40 h-40 rounded-full mx-auto mb-6 object-cover border-4 border-white shadow-xl">

            <h1 class="text-5xl md:text-6xl font-extrabold mb-3 leading-tight">Pranjal Dhakad</h1>
            <p class="text-2xl md:text-3xl font-light mb-8 typing-effect">Web Developer & Designer</p>

            <p class="text-lg md:text-xl max-w-2xl mx-auto mb-10 italic">"Crafting digital experiences, one line of code at a time."</p>

            <a href="your_resume.pdf" download class="bg-white text-blue-600 hover:bg-blue-100 px-8 py-4 rounded-full text-lg font-semibold shadow-lg hover:shadow-xl transition duration-300 ease-in-out transform hover:scale-105">
                <i class="fas fa-download mr-2"></i> Download Resume
            </a>
        </div>
    </section>

    <section id="about" class="py-16 md:py-24 bg-gray-100">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">About Me</h2>

            <div class="flex flex-col md:flex-row items-center md:items-start gap-12">
                <div class="md:w-1/2 bg-white rounded-lg shadow-lg p-8 flex-shrink-0 animate-fade-in-up">
                    <p class="text-lg leading-relaxed mb-6 text-gray-700">
                        Hello! I'm Pranjal Dhakad, a passionate and dedicated Web Developer and Designer. I'm currently immersing myself in the world of web technologies, constantly learning and building. My journey into web development began with a fascination for how websites are built and an eagerness to create interactive and visually appealing digital experiences. I believe in writing clean, efficient, and maintainable code, always striving for pixel-perfect designs.
                    </p>
                    <p class="text-lg leading-relaxed text-gray-700">
                        My interests span from mastering front-end frameworks to exploring the depths of back-end development. I enjoy tackling challenging problems and transforming complex ideas into user-friendly interfaces. Outside of coding, I'm usually found exploring new design trends, contributing to open-source projects, or diving into a good book. My goal is to build innovative web applications that make a difference.
                    </p>
                </div>

                <div class="md:w-1/2 grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-white rounded-lg shadow-lg p-8 animate-fade-in-up delay-200">
                        <h3 class="text-2xl font-semibold text-blue-600 mb-6">Key Skills</h3>
                        <ul class="list-disc list-inside text-gray-700 text-lg space-y-2">
                            <li>HTML5, CSS3, JavaScript (ES6+)</li>
                            <li>Tailwind CSS, Bootstrap</li>
                            <li>React.js (Basic)</li>
                            <li>Node.js (Beginner)</li>
                            <li>Responsive Design</li>
                            <li>Git & GitHub</li>
                            <li>UI/UX Principles</li>
                        </ul>
                    </div>

                    <div class="bg-white rounded-lg shadow-lg p-8 animate-fade-in-up delay-400">
                        <h3 class="text-2xl font-semibold text-blue-600 mb-6">Education & Experience</h3>
                        <div class="space-y-6">
                            <div>
                                <h4 class="font-bold text-xl text-gray-800">Bachelor of Technology (B.Tech)</h4>
                                <p class="text-gray-600">Computer Science & Engineering</p>
                                <p class="text-sm text-gray-500">2nd Year (Ongoing)</p>
                                <p class="text-sm text-gray-500">Your University Name, Your City</p>
                            </div>
                            <div>
                                <h4 class="font-bold text-xl text-gray-800">Freelance Web Developer</h4>
                                <p class="text-gray-600">Self-Employed</p>
                                <p class="text-sm text-gray-500">2023 - Present</p>
                                <p class="text-sm text-gray-500">Developing small business websites and personal projects.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="py-16 md:py-24 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">My Projects</h2>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
                <div class="bg-white rounded-lg shadow-xl overflow-hidden hover:scale-105 hover:shadow-2xl transition duration-300 ease-in-out">
                    <img src="./images/project1.jpg" alt="Project 1 Screenshot" class="w-full h-56 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-semibold text-blue-600 mb-3">E-commerce Product Page</h3>
                        <p class="text-gray-700 text-base mb-4">
                            A responsive e-commerce product page built with HTML, Tailwind CSS, and a touch of JavaScript for interactive elements like image galleries and quantity selectors. Focus on clean UI/UX.
                        </p>
                        <p class="text-gray-600 text-sm mb-4">
                            <span class="font-medium">Tools:</span> HTML, Tailwind CSS, JavaScript
                        </p>
                        <a href="https://github.com/yourusername/project1-repo" target="_blank" class="text-blue-600 hover:underline font-medium text-lg">
                            <i class="fab fa-github mr-2"></i> View on GitHub
                        </a>
                    </div>
                </div>

                <div class="bg-white rounded-lg shadow-xl overflow-hidden hover:scale-105 hover:shadow-2xl transition duration-300 ease-in-out">
                    <img src="./images/project2.jpg" alt="Project 2 Screenshot" class="w-full h-56 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-semibold text-blue-600 mb-3">Simple Todo App</h3>
                        <p class="text-gray-700 text-base mb-4">
                            A classic Todo application demonstrating basic CRUD operations. Built using HTML, CSS, and vanilla JavaScript to manage tasks, mark them as complete, and delete them.
                        </p>
                        <p class="text-gray-600 text-sm mb-4">
                            <span class="font-medium">Tools:</span> HTML, CSS, JavaScript
                        </p>
                        <a href="https://github.com/yourusername/project2-repo" target="_blank" class="text-blue-600 hover:underline font-medium text-lg">
                            <i class="fab fa-github mr-2"></i> View on GitHub
                        </a>
                    </div>
                </div>

                <div class="bg-white rounded-lg shadow-xl overflow-hidden hover:scale-105 hover:shadow-2xl transition duration-300 ease-in-out">
                    <img src="./images/project3.jpg" alt="Project 3 Screenshot" class="w-full h-56 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-semibold text-blue-600 mb-3">Portfolio Template</h3>
                        <p class="text-gray-700 text-base mb-4">
                            A minimal and modern portfolio website template designed for developers and designers. Showcases responsive design principles and clean code structure.
                        </p>
                        <p class="text-gray-600 text-sm mb-4">
                            <span class="font-medium">Tools:</span> HTML, Tailwind CSS
                        </p>
                        <a href="https://github.com/yourusername/project3-repo" target="_blank" class="text-blue-600 hover:underline font-medium text-lg">
                            <i class="fab fa-github mr-2"></i> View on GitHub
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-16 md:py-24 bg-gradient-to-r from-blue-600 to-indigo-700 text-white">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold text-center mb-12">Get in Touch</h2>

            <div class="max-w-xl mx-auto bg-white rounded-lg shadow-xl p-8 md:p-10">
                <form action="#" method="POST">
                    <div class="mb-6">
                        <label for="name" class="block text-gray-700 text-lg font-medium mb-2">Name</label>
                        <input type="text" id="name" name="name" class="shadow-sm appearance-none border rounded w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition duration-200" placeholder="Your Name" required>
                    </div>
                    <div class="mb-6">
                        <label for="email" class="block text-gray-700 text-lg font-medium mb-2">Email</label>
                        <input type="email" id="email" name="email" class="shadow-sm appearance-none border rounded w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition duration-200" placeholder="your.email@example.com" required>
                    </div>
                    <div class="mb-8">
                        <label for="message" class="block text-gray-700 text-lg font-medium mb-2">Message</label>
                        <textarea id="message" name="message" rows="6" class="shadow-sm appearance-none border rounded w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition duration-200" placeholder="Your message..." required></textarea>
                    </div>
                    <div class="text-center">
                        <button type="submit" class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-8 rounded-full shadow-lg hover:shadow-xl transition duration-300 ease-in-out transform hover:scale-105 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-opacity-50">
                            Send Message <i class="fas fa-paper-plane ml-2"></i>
                        </button>
                    </div>
                </form>

                <div class="mt-12 text-center">
                    <p class="text-white text-xl font-semibold mb-4">Connect with me:</p>
                    <div class="flex justify-center space-x-6">
                        <a href="https://github.com/yourusername" target="_blank" class="text-white hover:text-gray-200 transition duration-300 transform hover:scale-125">
                            <i class="fab fa-github fa-3x"></i>
                        </a>
                        <a href="https://linkedin.com/in/yourusername" target="_blank" class="text-white hover:text-gray-200 transition duration-300 transform hover:scale-125">
                            <i class="fab fa-linkedin fa-3x"></i>
                        </a>
                        <a href="https://twitter.com/yourusername" target="_blank" class="text-white hover:text-gray-200 transition duration-300 transform hover:scale-125">
                            <i class="fab fa-twitter fa-3x"></i>
                        </a>
                        </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-gray-800 text-white py-8 text-center">
        <div class="container mx-auto px-6">
            <p>&copy; 2025 Pranjal Dhakad. All rights reserved.</p>
            <p class="text-sm mt-2">Built with <span class="text-red-500">&hearts;</span> and Tailwind CSS</p>
        </div>
    </footer>

    <script>
        // Mobile Menu Toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when a link is clicked
        const mobileMenuLinks = mobileMenu.querySelectorAll('a');
        mobileMenuLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        // Dynamic Typing Effect (Vanilla JS - adjust as needed for Tailwind Plugins)
        // If you were to use a Tailwind plugin, this JS would be replaced by its setup.
        const typingElement = document.querySelector('.typing-effect');
        const phrases = ["Web Developer & Designer", "UI/UX Enthusiast", "Problem Solver"];
        let phraseIndex = 0;
        let charIndex = 0;
        let isDeleting = false;

        function typeWriter() {
            const currentPhrase = phrases[phraseIndex];
            let displayText = '';

            if (isDeleting) {
                displayText = currentPhrase.substring(0, charIndex - 1);
            } else {
                displayText = currentPhrase.substring(0, charIndex + 1);
            }

            typingElement.textContent = displayText;

            let typeSpeed = 100; // Typing speed
            if (isDeleting) {
                typeSpeed /= 2; // Faster deleting
            }

            if (!isDeleting && charIndex === currentPhrase.length) {
                // Pause at end of word
                typeSpeed = 1500;
                isDeleting = true;
            } else if (isDeleting && charIndex === 0) {
                isDeleting = false;
                phraseIndex = (phraseIndex + 1) % phrases.length; // Move to next phrase
                typeSpeed = 500; // Pause before typing next word
            }

            if (isDeleting) {
                charIndex--;
            } else {
                charIndex++;
            }

            setTimeout(typeWriter, typeSpeed);
        }

        document.addEventListener('DOMContentLoaded', () => {
            if (typingElement) {
                typeWriter();
            }
        });
    </script>
</body>
</html>
