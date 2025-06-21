<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>White Hierarchy - Fintech & Animal Welfare</title>
  <meta name="description" content="White Hierarchy is launching an innovative fintech solution while making a difference through our animal welfare initiative, PawsIndia." />

  <!-- Tailwind CSS -->
  <link href="assets/css/output.css" rel="stylesheet" />

  <style>
    body {
      scroll-behavior: smooth;
    }
    .boss-hero {
      background-color: #fff;
      background-image: radial-gradient(#3b82f6 0.5px, #fff 0.5px);
      background-size: 10px 10px;
    }
  </style>
</head>
<body class="bg-white font-sans">

  <!-- Header -->
  <header class="fixed top-0 w-full bg-white shadow z-50">
    <div class="max-w-7xl mx-auto flex justify-between items-center h-16 px-4">
      <div class="flex items-center">
        <svg class="h-8 w-auto text-blue-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
        </svg>
        <span class="ml-2 text-xl font-bold text-gray-900">White Hierarchy</span>
      </div>
      <nav class="hidden md:flex space-x-8">
        <a href="#home" class="text-gray-900 font-medium">Home</a>
        <a href="#about" class="text-gray-500 hover:text-gray-900 font-medium">About</a>
        <a href="#fintech" class="text-gray-500 hover:text-gray-900 font-medium">Fintech</a>
        <a href="#pawsindia" class="text-gray-500 hover:text-gray-900 font-medium">PawsIndia</a>
        <a href="#contact" class="text-gray-500 hover:text-gray-900 font-medium">Contact</a>
      </nav>
      <button id="mobile-menu-btn" class="md:hidden p-2 rounded text-gray-400 hover:text-gray-500 hover:bg-gray-100">
        <span class="sr-only">Open menu</span>
        <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
        </svg>
      </button>
    </div>
    <div id="mobile-menu" class="hidden md:hidden bg-white shadow-md">
      <a href="#home" class="block px-4 py-2">Home</a>
      <a href="#about" class="block px-4 py-2">About</a>
      <a href="#fintech" class="block px-4 py-2">Fintech</a>
      <a href="#pawsindia" class="block px-4 py-2">PawsIndia</a>
      <a href="#contact" class="block px-4 py-2">Contact</a>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="boss-hero pt-24 pb-20">
    <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row items-center">
      <div class="md:w-1/2 pr-8">
        <h1 class="text-5xl font-bold text-gray-900 leading-tight">
          Transforming Finance<br/>
          <span class="text-blue-600">Empowering Lives</span>
        </h1>
        <p class="mt-4 text-xl text-gray-600">
          White Hierarchy is launching an innovative fintech solution while making a difference through our animal welfare initiative, PawsIndia.
        </p>
        <div class="mt-8 flex space-x-4">
          <a href="#fintech" class="bg-blue-600 text-white px-6 py-3 rounded-md hover:bg-blue-700">Learn About Our Fintech</a>
          <a href="#pawsindia" class="border border-gray-300 text-blue-600 px-6 py-3 rounded-md hover:bg-gray-50">Discover PawsIndia</a>
        </div>
      </div>
      <div class="md:w-1/2 mt-10 md:mt-0">
        <!-- Hero SVG graphic -->
        <svg class="w-full h-auto" viewBox="0 0 500 400" xmlns="http://www.w3.org/2000/svg">
          <!-- (same SVG from your code) -->
        </svg>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-16">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <h2 class="text-4xl font-extrabold text-gray-900">About White Hierarchy</h2>
      <p class="mt-4 text-xl text-gray-500 max-w-2xl mx-auto">Pioneering the future of finance while making a positive impact on society.</p>
      <div class="mt-16 grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Vision Card -->
        <div class="bg-gray-50 rounded-lg shadow-lg hover:shadow-xl transform hover:-translate-y-1 transition overflow-hidden">
          <div class="p-8">
            <h3 class="text-2xl font-medium text-gray-900">Our Vision</h3>
            <p class="mt-4 text-gray-600">At White Hierarchy, we envision a world where financial services are accessible, transparent, and beneficial for everyone...</p>
          </div>
          <div class="p-6 bg-blue-50 flex items-center">
            <svg class="h-6 w-6 text-blue-600" xmlns="http://www.w3.org/2000/svg".../>
            <span class="ml-2 text-lg font-medium text-blue-600">Innovation with Purpose</span>
          </div>
        </div>
        <!-- Mission Card -->
        <div class="bg-gray-50 rounded-lg shadow-lg hover:shadow-xl transform hover:-translate-y-1 transition overflow-hidden">
          <div class="p-8">
            <h3 class="text-2xl font-medium text-gray-900">Our Mission</h3>
            <p class="mt-4 text-gray-600">We're on a mission to revolutionize financial technology while maintaining a strong commitment to social responsibility...</p>
          </div>
          <div class="p-6 bg-blue-50 flex items-center">
            <svg class="h-6 w-6 text-blue-600" xmlns="http://www.w3.org/2000/svg".../>
            <span class="ml-2 text-lg font-medium text-blue-600">Technology with Heart</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Fintech Section -->
  <section id="fintech" class="py-16 bg-gray-50">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <h2 class="text-4xl font-extrabold text-gray-900">Our Fintech Solution</h2>
      <p class="mt-4 text-xl text-gray-500">Coming soon: A revolutionary approach to financial technology.</p>
      <div class="mt-16 grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Feature cards -->
        <div class="feature-card bg-white rounded-lg shadow-md p-6 hover:shadow-xl hover:-translate-y-1 transition">
          <div class="bg-blue-100 p-3 rounded-md inline-block">
            <svg class="h-6 w-6 text-blue-600".../>
          </div>
          <h3 class="mt-5 text-lg font-medium text-gray-900">Smart Payments</h3>
          <p class="mt-2 text-gray-600">Seamless, secure, intelligent payment solutions.</p>
        </div>
        <!-- Additional cards – Security, Analytics -->
        <div class="feature-card bg-white rounded-lg shadow-md p-6 hover:shadow-xl hover:-translate-y-1 transition">
          <div class="bg-blue-100 p-3 rounded-md inline-block">
            <svg class="h-6 w-6 text-blue-600".../>
          </div>
          <h3 class="mt-5 text-lg font-medium text-gray-900">Enhanced Security</h3>
          <p class="mt-2 text-gray-600">State-of-the-art protection for your financial data.</p>
        </div>
        <div class="feature-card bg-white rounded-lg shadow-md p-6 hover:shadow-xl hover:-translate-y-1 transition">
          <div class="bg-blue-100 p-3 rounded-md inline-block">
            <svg class="h-6 w-6 text-blue-600".../>
          </div>
          <h3 class="mt-5 text-lg font-medium text-gray-900">Financial Analytics</h3>
          <p class="mt-2 text-gray-600">Powerful insights to inform smart decisions.</p>
        </div>
      </div>
      <div class="mt-16">
        <a href="#contact" class="inline-block bg-blue-600 text-white px-5 py-3 rounded-md hover:bg-blue-700">Get Early Access</a>
        <p class="mt-3 text-sm text-gray-500">Be the first to experience our revolutionary fintech solution.</p>
      </div>
    </div>
  </section>

  <!-- PawsIndia Section -->
  <section id="pawsindia" class="py-16">
    <div class="max-w-7xl mx-auto px-6">
      <div class="text-center">
        <svg class="h-8 w-8 text-blue-600 inline-block".../>
        <h2 class="inline ml-3 text-4xl font-extrabold text-gray-900">PawsIndia</h2>
        <p class="mt-4 text-xl text-gray-500 max-w-2xl mx-auto">Our NGO dedicated to animal welfare across India.</p>
      </div>
      <div class="mt-16 lg:flex lg:items-center lg:gap-16">
        <div class="lg:w-1/2">
          <svg class="w-full h-auto rounded-lg shadow-lg".../>
        </div>
        <div class="mt-10 lg:mt-0 lg:w-1/2">
          <h3 class="text-2xl font-extrabold text-gray-900">Making a Difference for Animals</h3>
          <p class="mt-3 text-lg text-gray-500">PawsIndia is our initiative to help stray animals across India...</p>
          <ul class="mt-8 space-y-4">
            <li class="flex items-start"><svg class="h-6 w-6 text-green-500".../><span class="ml-3">Animal rescue and rehabilitation</span></li>
            <li class="flex items-start"><svg class="h-6 w-6 text-green-500".../><span class="ml-3">Vaccination and sterilization programs</span></li>
            <li class="flex items-start"><svg class="h-6 w-6 text-green-500".../><span class="ml-3">Community education and awareness</span></li>
          </ul>
          <a href="https://www.instagram.com/pawsindiango" target="_blank" class="inline-block mt-8 bg-blue-600 text-white px-5 py-3 rounded-md hover:bg-blue-700">
            Follow on Instagram
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-16 bg-gradient-to-br from-blue-600 via-cyan-500 to-blue-400 text-white">
    <div class="max-w-lg mx-auto px-6">
      <h2 class="text-3xl font-extrabold text-center">Get in Touch</h2>
      <p class="mt-4 text-center text-lg">Interested in our fintech solution or want to support PawsIndia?</p>
      <form class="mt-8 space-y-6">
        <div>
          <label for="name" class="block text-sm font-medium">Full name</label>
          <input type="text" id="name" name="name" class="mt-1 w-full px-4 py-3 rounded-md text-gray-900" placeholder="John Doe" />
        </div>
        <div>
          <label for="email" class="block text-sm font-medium">Email</label>
          <input type="email" id="email" name="email" class="mt-1 w-full px-4 py-3 rounded-md text-gray-900" placeholder="john@example.com" />
        </div>
        <div>
          <label for="message" class="block text-sm font-medium">Message</label>
          <textarea id="message" name="message" rows="4" class="mt-1 w-full px-4 py-3 rounded-md text-gray-900" placeholder="Your message here..."></textarea>
        </div>
        <div>
          <button type="submit" class="w-full bg-white text-blue-600 rounded-md py-3 font-medium hover:bg-gray-50">Send Message</button>
        </div>
      </form>
      <p class="mt-4 text-center text-sm">We'll get back to you as soon as possible.</p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-gray-400 py-12">
    <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 md:grid-cols-3 gap-8">
      <div>
        <div class="flex items-center">
          <svg class="h-8 w-auto text-blue-400".../>
          <span class="ml-2 text-xl font-bold text-white">White Hierarchy</span>
        </div>
        <p class="mt-4 text-base">Transforming finance, empowering lives, and making a difference for animals across India.</p>
      </div>
      <div>
        <h3 class="font-semibold uppercase tracking-wider">Quick Links</h3>
        <ul class="mt-4 space-y-2">
          <li><a href="#home" class="hover:text-white">Home</a></li>
          <li><a href="#about" class="hover:text-white">About</a></li>
          <li><a href="#fintech" class="hover:text-white">Fintech</a></li>
          <li><a href="#pawsindia" class="hover:text-white">PawsIndia</a></li>
        </ul>
      </div>
      <div>
        <h3 class="font-semibold uppercase tracking-wider">Connect With Us</h3>
        <a href="https://www.instagram.com/pawsindiango" target="_blank" class="flex items-center mt-4 hover:text-white">
          <svg class="h-5 w-5 mr-2".../>
          <span>Instagram</span>
        </a>
      </div>
    </div>
  </footer>

  <!-- Optional JS -->
  <script src="assets/js/script.js"></script>
</body>
</html>
