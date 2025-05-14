
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--title>Varsha Palamuri - Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- AOS Library for Animations -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #1a1a1a;
            color: #ffffff;
        }
        .section-title {
            @apply text-3xl font-bold text-blue-400 mb-8 text-center;
        }
        .card {
            @apply bg-gray-800 p-6 rounded-lg shadow-lg;
        }
        .navbar {
            @apply bg-gray-900 shadow-md sticky top-0 z-50;
        }
        .btn {
            @apply px-4 py-2 rounded-md font-semibold transition duration-300;
        }
        .btn-primary {
            @apply bg-blue-600 hover:bg-blue-700 text-white;
        }
        .skill-bar {
            @apply bg-gray-600 h-2 rounded-full overflow-hidden;
        }
        .skill-bar-fill {
            @apply bg-blue-500 h-full;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar py-4">
        <div class="max-w-6xl mx-auto px-4 flex justify-between items-center">
            <h1 class="text-2xl font-bold text-blue-400">Varsha Palamuri</h1>
            <ul class="flex space-x-6">
                <li><a href="#home" class="hover:text-blue-400 transition">Home</a></li>
                <li><a href="#about" class="hover:text-blue-400 transition">About</a></li>
                <li><a href="#education" class="hover:text-blue-400 transition">Education</a></li>
                <li><a href="#experience" class="hover:text-blue-400 transition">Experience</a></li>
                <li><a href="#projects" class="hover:text-blue-400 transition">Projects</a></li>
                <li><a href="#skills" class="hover:text-blue-400 transition">Skills</a></li>
                <li><a href="#contact" class="hover:text-blue-400 transition">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="min-h-screen flex items-center justify-center bg-gradient-to-b from-gray-900 to-gray-800">
        <div class="text-center" data-aos="fade-up">
            <h1 class="text-5xl font-bold mb-4">Hi, I'm Varsha Palamuri</h1>
            <p class="text-xl mb-6">Data Science & AI Master's Student | Full-Stack Developer | Infrastructure Specialist</p>
            <a href="#contact" class="btn btn-primary mr-4">Get in Touch</a>
            <a href="https://www.linkedin.com/in/varsha-p-b42826203/" target="_blank" class="btn btn-primary">View LinkedIn</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="section-title">About Me</h2>
            <div class="card" data-aos="fade-up">
                <p class="text-lg">I am a passionate technologist with expertise in designing, developing, and deploying full-stack web applications. I have hands-on experience configuring and managing Linux VMs in VMware vSphere environments, including network setup, system monitoring, and performance tuning using vCenter Server. Currently pursuing a Master’s in Data Science & Artificial Intelligence, I aim to leverage my skills in AI, cloud technologies, and infrastructure management to solve real-world challenges.</p>
            </div>
        </div>
    </section>
    <!-- Education Section -->
    <section id="education" class="py-20 bg-gray-900">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="section-title">Education</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="card" data-aos="fade-up">
                    <h3 class="text-xl font-semibold text-blue-400">Master’s in Data Science & AI</h3>
                    <p>University of Central Missouri | 2025 - Present</p>
                </div>
                <div class="card" data-aos="fade-up" data-aos-delay="100">
                    <h3 class="text-xl font-semibold text-blue-400">B.Tech in Electronics & Communication</h3>
                    <p>Sreyas Institute of Engineering and Technology | 2018 - 2022 | CGPA: 7.88</p>
                </div>
               </div>
        </div>
    </section>
    <!-- Experience Section -->
    <section id="experience" class="py-20">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="section-title">Experience</h2>
            <div class="card" data-aos="fade-up">
                <h3 class="text-xl font-semibold text-blue-400">Associate Technical Consultant, Hitachi</h3>
                <p>Hyderabad, India | Feb 2023 – Dec 2024</p>
                <ul class="list-disc pl-5 mt-4">
                    <li>Maintained Hitachi Vantara databases, storage systems, and servers.</li>
                    <li>Monitored IT infrastructure health, performance, and availability.</li>
                    <li>Managed Network Attached Storage (NAS) systems.</li>
                    <li>Performed ESXI Host patching for HCP storage.</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 bg-gray-900">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="section-title">Projects</h2>
            <div class="card" data-aos="fade-up">
                <h3 class="text-xl font-semibold text-blue-400">Detection and Classification of Diabetic Retinopathy</h3>
                <p>Feb 2023 – Dec 2024</p>
                <ul class="list-disc pl-5 mt-4">
                    <li>Developed an automated system using Deep Learning to detect and classify Diabetic Retinopathy severity.</li>
                    <li>Enabled rapid detection to prevent severe consequences of the disease.</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="section-title">Skills</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="card" data-aos="fade-up">
                    <h3 class="text-xl font-semibold text-blue-400 mb-4">Applied Skills</h3>
                    <ul class="list-disc pl-5">
                        <li>E-commerce Website Design</li>
                        <li>ESXI Host Patching</li>
                        <li>Health Checks</li>
                    </ul>
                </div>
                
                <div class="card" data-aos="fade-up" data-aos-delay="100">
                    <h3 class="text-xl font-semibold text-blue-400 mb-4">Tools</h3>
                    <ul class="list-disc pl-5">
                        <li>Git</li>
                        <li>HTML</li>
                        <li>CSS</li>
                        <li>VMware</li>
                        <li>ServiceNow</li>
                        <li>Nagios</li>
                    </ul>
                </div>
                <div class="card" data-aos="fade-up" data-aos-delay="200">
                    <h3 class="text-xl font-semibold text-blue-400 mb-4">Languages</h3>
                    <ul class="list-disc pl-5">
                        <li>Python</li>
                        <li>Angular Framework</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Certifications Section -->
    <section id="certifications" class="py-20 bg-gray-900 text-white">
    <div class="max-w-6xl mx-auto px-4">
    <h2 class="text-3xl font-bold text-center mb-10">Licenses & Certifications</h2>

    <div class="space-y-6">
      <!-- Certification Card -->
      
      <div class="bg-gray-800 p-6 rounded-lg shadow-lg" data-aos="fade-up">
        <h3 class="text-xl font-semibold text-blue-400">ITIL Foundation Certificate in IT Service Management – PeopleCert</h3>
        <p class="text-sm text-gray-400">2023</p>
        <p class="mt-2 text-gray-200">Completed foundational certification in IT Service Management.</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-lg shadow-lg" data-aos="fade-up">
        <h3 class="text-xl font-semibold text-blue-400">Cloud GCP Intern – Wipro</h3>
        <p class="text-sm text-gray-400">2022</p>
        <p class="mt-2 text-gray-200">Developed an E-Commerce Website and deployed it on Google Cloud Platform.</p>
      </div>

      <div class="bg-gray-800 p-6 rounded-lg shadow-lg" data-aos="fade-up">
        <h3 class="text-xl font-semibold text-blue-400">Network Systems – BSNL</h3>
        <p class="text-sm text-gray-400">2021</p>
        <p class="mt-2 text-gray-200">Learned Networking Concepts and designed a Campus Area Network.</p>
      </div>

      <div class="bg-gray-800 p-6 rounded-lg shadow-lg" data-aos="fade-up">
        <h3 class="text-xl font-semibold text-blue-400">Introduction to Ethical Hacking – Supraja Technologies</h3>
        <p class="text-sm text-gray-400">2020</p>
        <p class="mt-2 text-gray-200">Gained knowledge on security solutions and performed bug fixes on personal IDs.</p>
      </div>
    </div>
  </div>
</section>


    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-900">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="section-title">Contact Me</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="card" data-aos="fade-up">
                    <h3 class="text-xl font-semibold text-blue-400 mb-4">Get in Touch</h3>
                    <p><i class="fas fa-envelope mr-2"></i> <a href="mailto:varshapabc123@gmail.com">varshapabc123@gmail.com</a></p>
                    <p><i class="fas fa-phone mr-2"></i> <a href="tel:+16605805111">+1 660-580-5111</a></p>
                    <p><i class="fab fa-linkedin mr-2"></i> <a href="https://www.linkedin.com/in/varsha-p-b42826203/" target="_blank">LinkedIn</a></p>
                </div>
                <div class="card" data-aos="fade-up" data-aos-delay="100">
                    <h3 class="text-xl font-semibold text-blue-400 mb-4">Send a Message</h3>
                    <form>
                        <div class="mb-4">
                            <input type="text" placeholder="Name" class="w-full p-2 rounded bg-gray-700 text-white border border-gray-600 focus:outline-none focus:border-blue-400">
                        </div>
                        <div class="mb-4">
                            <input type="email" placeholder="Email" class="w-full p-2 rounded bg-gray-700 text-white border border-gray-600 focus:outline-none focus:border-blue-400">
                        </div>
                        <div class="mb-4">
                            <textarea placeholder="Message" rows="4" class="w-full p-2 rounded bg-gray-700 text-white border border-gray-600 focus:outline-none focus:border-blue-400"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 py-6 text-center">
        <div class="flex justify-center space-x-6 mb-4">
            <a href="https://www.linkedin.com/in/varsha-p-b42826203/" target="_blank" class="text-blue-400 hover:text-blue-300"><i class="fab fa-linkedin fa-2x"></i></a>
            <a href="mailto:varshapabc123@gmail.com" class="text-blue-400 hover:text-blue-300"><i class="fas fa-envelope fa-2x"></i></a>
        </div>
        <p>&copy; 2025 Varsha Palamuri. All rights reserved.</p>
    </footer>

    <!-- JavaScript for Smooth Scrolling and AOS Initialization -->
    <script>
        // Initialize AOS
        AOS.init({
            duration: 1000,
            once: true
        });

        // Smooth scrolling for nav links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
