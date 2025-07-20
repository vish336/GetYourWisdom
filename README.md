<!DOCTYPE html>
<html lang="en">


<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>The Tuition Teacher Clone</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-800">

  <!-- Header -->
  <header class="bg-white shadow-md">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <a href="#" class="text-2xl font-bold">Vishal</a>
      <nav>
        <ul class="flex space-x-6">
          <li><a href="#" class="hover:text-blue-600">Home</a></li>
          <li><a href="#services" class="hover:text-blue-600">Services</a></li>
          <li><a href="#contact" class="hover:text-blue-600">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="bg-blue-600 text-white py-20">
    <div class="container mx-auto px-6 text-center">
      <h1 class="text-4xl font-extrabold mb-4">Find the Best Tutors in Lucknow</h1>
      <p class="text-lg mb-8">Expert tuition for all grades & subjects, 1-on-1 or online.</p>
      <a href="#contact" class="bg-white text-blue-600 px-8 py-3 font-semibold rounded">Get Started</a>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="py-16">
    <div class="container mx-auto px-6">
      <h2 class="text-3xl font-bold text-center mb-12">Our Services</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded-lg shadow">
          <h3 class="text-xl font-semibold mb-2">1-on-1 Tuition</h3>
          <p>Personalized lessons tailored to your needs.</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow">
          <h3 class="text-xl font-semibold mb-2">Online Classes</h3>
          <p>Learn from home with experienced teachers.</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow">
          <h3 class="text-xl font-semibold mb-2">Exam Prep</h3>
          <p>Targeted support for board or competitive exams.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Form -->
  <section id="contact" class="bg-gray-100 py-16">
    <div class="container mx-auto px-6 max-w-lg">
      <h2 class="text-3xl font-bold mb-6 text-center">Contact Us</h2>
      <form class="space-y-4">
        <input type="text" placeholder="Your Name" class="w-full border p-3 rounded"/>
        <input type="email" placeholder="Your Email" class="w-full border p-3 rounded"/>
        <textarea placeholder="How can we help?" class="w-full border p-3 rounded"></textarea>
        <button class="w-full bg-blue-600 text-white py-3 rounded font-semibold">Submit</button>
      </form>
    </div>
  </section>

  <footer class="bg-white py-6 text-center">
    <p>&copy; 2025 Your Website. All Rights Reserved.</p>
  </footer>
</body>
</html>

