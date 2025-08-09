<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Economist Ajay Sahu - Official Website</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      background-color: #F8F8F8;
      color: #333333;
    }
    .nav-link {
      transition: color 0.3s ease;
    }
    .nav-link:hover {
      color: #20B2AA;
    }
    .btn-primary {
      background-color: #20B2AA;
      transition: background-color 0.3s ease;
    }
    .btn-primary:hover {
      background-color: #1A928C;
    }
    .video-card {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .video-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1),
                  0 4px 6px -2px rgba(0, 0, 0, 0.05);
    }
  </style>
</head>
<body class="antialiased">

  <!-- Header -->
  <header class="bg-white shadow-sm py-4 px-6 fixed w-full z-10 top-0">
    <div class="container mx-auto flex justify-between items-center">
      <a href="#hero" class="text-2xl font-bold text-gray-800">Economist Ajay Sahu</a>
      <nav>
        <ul class="flex space-x-6">
          <li><a href="#about" class="nav-link text-gray-700 hover:text-teal-500">About</a></li>
          <li><a href="#videos" class="nav-link text-gray-700 hover:text-teal-500">Videos</a></li>
          <li><a href="#contact" class="nav-link text-gray-700 hover:text-teal-500">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Main Content -->
  <main class="pt-20">
    <!-- Hero Section -->
    <section id="hero" class="relative bg-gradient-to-r from-gray-800 to-gray-900 text-white py-24 px-4 text-center">
      <div class="container mx-auto">
        <h1 class="text-4xl md:text-6xl font-bold leading-tight">Welcome to My World of Economics!</h1>
        <p class="mt-4 text-lg md:text-xl max-w-2xl mx-auto opacity-90">Simplifying complex economic concepts for everyone.</p>
        <a href="https://www.youtube.com/@Economist_Ajay_Sahu9999" target="_blank" class="mt-8 inline-block bg-teal-500 text-white font-semibold py-3 px-8 rounded-full shadow-lg hover:bg-teal-600 transition duration-300">Watch My Latest Videos</a>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 px-4 bg-white">
      <div class="container mx-auto grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
        <div class="md:order-2">
          <img src="https://placehold.co/600x400/E0E0E0/333333?text=Ajay+Sahu" alt="Ajay Sahu Profile Image" class="rounded-lg shadow-lg w-full h-auto object-cover">
        </div>
        <div class="md:order-1">
          <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-6">About Me</h2>
          <p class="text-lg text-gray-700 leading-relaxed mb-4">
            Hello! I'm Ajay Sahu, an economist dedicated to making economic concepts accessible and engaging. With a passion for teaching and a knack for breaking down complex topics, I aim to empower individuals with knowledge that can make a real difference in their lives.
          </p>
          <p class="text-lg text-gray-700 leading-relaxed">
            Join me as we explore the fascinating world of economics together!
          </p>
        </div>
      </div>
    </section>

    <!-- Videos Section -->
    <section id="videos" class="py-16 px-4 bg-gray-50">
      <div class="container mx-auto">
        <h2 class="text-3xl md:text-4xl font-bold text-center text-gray-800 mb-10">Featured Videos</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
          <!-- Video 1 -->
          <div class="video-card bg-white rounded-lg shadow-md overflow-hidden">
            <div class="aspect-w-16 aspect-h-9">
              <iframe class="w-full h-full" src="https://www.youtube.com/embed/b76lQaw925A" title="Elasticity of Demand" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen loading="lazy"></iframe>
            </div>
            <div class="p-6">
              <h3 class="text-xl font-semibold text-gray-800 mb-2">Determinants of Demand Elasticity</h3>
              <p class="text-gray-600 text-sm">Understanding the factors that influence the elasticity of demand in economics.</p>
            </div>
          </div>
          <!-- Add more video cards as needed -->
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 px-4 bg-white">
      <div class="container mx-auto text-center">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-8">Get in Touch</h2>
        <p class="text-lg text-gray-700 max-w-2xl mx-auto mb-10">
          Have questions or want to connect? Reach out through the form below or connect with me on social media!
        </p>

        <div class="flex justify-center space-x-6 mb-12 text-3xl">
          <a href="https://www.youtube.com/@Economist_Ajay_Sahu9999" target="_blank" class="text-gray-600 hover:text-red-600 transition duration-300" aria-label="YouTube Channel">▶️</a>
          <a href="https://www.instagram.com/ajaysahu_economist" target="_blank" class="text-gray-600 hover:text-pink-600 transition duration-300" aria-label="Instagram">📸</a>
          <a href="https://www.twitter.com/ajaysahu_econ" target="_blank" class="text-gray-600 hover:text-blue-500 transition duration-300" aria-label="Twitter">🐦</a>
          <a href="mailto:ajaysahu@example.com" class="text-gray-600 hover:text-blue-700 transition duration-300" aria-label="Email">📧</a>
        </div>

        <div class="max-w-xl mx-auto bg-gray-50 p-8 rounded-lg shadow-md">
          <form id="contactForm" class="space-y-6">
            <div>
              <label for="name" class="block text-left text-gray-700 text-sm font-semibold mb-2">Name</label>
              <input type="text" id="name" name="name" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-teal-500" placeholder="Your Name" required>
            </div>
            <div>
              <label for="email" class="block text-left text-gray-700 text-sm font-semibold mb-2">Email</label>
              <input type="email" id="email" name="email" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-teal-500" placeholder="your@example.com" required>
            </div>
            <div>
              <label for="message" class="block text-left text-gray-700 text-sm font-semibold mb-2">Message</label>
              <textarea id="message" name="message" rows="5" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-teal-500" placeholder="Your message..." required></textarea>
            </div>
            <button type="submit" class="btn-primary w-full text-white font-semibold py-3 rounded-md shadow-lg">Send Message</button>
          </form>
          <div id="formMessage" class="mt-4 text-center text-sm hidden"></div>
        </div>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer class="bg-gray-800 text-white py-8">
    <div class="container mx-auto text-center px-4">
      <p>&copy; 2025 Economist Ajay Sahu. All rights reserved.</p>
      <div class="mt-2 text-sm text-gray-400">
        <a href="#" class="hover:underline">Privacy Policy</a> | <a href="#" class="hover:underline">Terms of Service</a>
      </div>
    </div>
  </footer>

  <!-- Scripts -->
  <script>
    document.addEventListener('DOMContentLoaded', () => {
      // Smooth scrolling for navigation links
      document.querySelectorAll('nav a').forEach(anchor => {
        anchor.addEventListener('click', function (e) {
          e.preventDefault();
          document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
          });
        });
      });

     
::contentReference[oaicite:8]{index=8}
      
