<template>
  <div class="min-h-screen bg-gradient-to-br from-blue-50 to-indigo-100">
    <!-- Navigation -->
    <nav class="bg-white shadow-sm">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex justify-between items-center h-16">
          <div class="flex items-center">
            <h1 class="text-2xl font-bold text-indigo-600">Nuxt Landing</h1>
          </div>
          <div class="hidden md:flex space-x-8">
            <a href="#features" class="text-gray-700 hover:text-indigo-600 transition">Features</a>
            <a href="#about" class="text-gray-700 hover:text-indigo-600 transition">About</a>
            <a href="#contact" class="text-gray-700 hover:text-indigo-600 transition">Contact</a>
          </div>
          <div>
            <button class="bg-indigo-600 text-white px-6 py-2 rounded-lg hover:bg-indigo-700 transition">
              Get Started
            </button>
          </div>
        </div>
      </div>
    </nav>

    <!-- Hero Section -->
    <section class="py-20 px-4 sm:px-6 lg:px-8">
      <div class="max-w-7xl mx-auto text-center">
        <h2 class="text-5xl md:text-6xl font-extrabold text-gray-900 mb-6">
          Welcome to Nuxt Landing
        </h2>
        <p class="text-xl md:text-2xl text-gray-600 mb-8 max-w-3xl mx-auto">
          Build fast, modern web applications with Nuxt.js. A powerful framework for creating amazing user experiences.
        </p>
        <div class="flex flex-col sm:flex-row gap-4 justify-center">
          <button class="bg-indigo-600 text-white px-8 py-4 rounded-lg text-lg font-semibold hover:bg-indigo-700 transition shadow-lg">
            Start Building
          </button>
          <button class="bg-white text-indigo-600 px-8 py-4 rounded-lg text-lg font-semibold hover:bg-gray-50 transition shadow-lg border-2 border-indigo-600">
            Learn More
          </button>
        </div>
      </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-20 px-4 sm:px-6 lg:px-8 bg-white">
      <div class="max-w-7xl mx-auto">
        <h3 class="text-4xl font-bold text-center text-gray-900 mb-12">
          Amazing Features
        </h3>
        <div class="grid md:grid-cols-3 gap-8">
          <div class="text-center p-6 rounded-lg hover:shadow-lg transition">
            <div class="w-16 h-16 bg-indigo-100 rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
              </svg>
            </div>
            <h4 class="text-xl font-semibold text-gray-900 mb-2">Lightning Fast</h4>
            <p class="text-gray-600">Optimized for performance with automatic code splitting and prefetching.</p>
          </div>
          
          <div class="text-center p-6 rounded-lg hover:shadow-lg transition">
            <div class="w-16 h-16 bg-indigo-100 rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4" />
              </svg>
            </div>
            <h4 class="text-xl font-semibold text-gray-900 mb-2">Highly Configurable</h4>
            <p class="text-gray-600">Customize every aspect to fit your project needs with powerful configuration options.</p>
          </div>
          
          <div class="text-center p-6 rounded-lg hover:shadow-lg transition">
            <div class="w-16 h-16 bg-indigo-100 rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" />
              </svg>
            </div>
            <h4 class="text-xl font-semibold text-gray-900 mb-2">Secure by Default</h4>
            <p class="text-gray-600">Built-in security features to protect your application and users.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 px-4 sm:px-6 lg:px-8">
      <div class="max-w-7xl mx-auto">
        <div class="grid md:grid-cols-2 gap-12 items-center">
          <div>
            <h3 class="text-4xl font-bold text-gray-900 mb-6">
              Built with Modern Technologies
            </h3>
            <p class="text-lg text-gray-600 mb-4">
              This landing page is powered by Nuxt.js, a powerful Vue.js framework that makes web development simple and intuitive.
            </p>
            <p class="text-lg text-gray-600 mb-6">
              With server-side rendering, automatic routing, and powerful data fetching capabilities, Nuxt.js helps you build production-ready applications faster.
            </p>
            <ul class="space-y-3">
              <li class="flex items-center text-gray-700">
                <svg class="w-5 h-5 text-green-500 mr-3" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                </svg>
                Server-side rendering
              </li>
              <li class="flex items-center text-gray-700">
                <svg class="w-5 h-5 text-green-500 mr-3" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                </svg>
                Automatic code splitting
              </li>
              <li class="flex items-center text-gray-700">
                <svg class="w-5 h-5 text-green-500 mr-3" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd" />
                </svg>
                TypeScript support
              </li>
            </ul>
          </div>
          <div class="bg-white p-8 rounded-lg shadow-xl">
            <div class="aspect-w-16 aspect-h-9 bg-gradient-to-br from-indigo-400 to-purple-500 rounded-lg flex items-center justify-center">
              <svg class="w-32 h-32 text-white opacity-50" fill="currentColor" viewBox="0 0 20 20">
                <path d="M10.394 2.08a1 1 0 00-.788 0l-7 3a1 1 0 000 1.84L5.25 8.051a.999.999 0 01.356-.257l4-1.714a1 1 0 11.788 1.838L7.667 9.088l1.94.831a1 1 0 00.787 0l7-3a1 1 0 000-1.838l-7-3zM3.31 9.397L5 10.12v4.102a8.969 8.969 0 00-1.05-.174 1 1 0 01-.89-.89 11.115 11.115 0 01.25-3.762zM9.3 16.573A9.026 9.026 0 007 14.935v-3.957l1.818.78a3 3 0 002.364 0l5.508-2.361a11.026 11.026 0 01.25 3.762 1 1 0 01-.89.89 8.968 8.968 0 00-5.35 2.524 1 1 0 01-1.4 0zM6 18a1 1 0 001-1v-2.065a8.935 8.935 0 00-2-.712V17a1 1 0 001 1z" />
              </svg>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section id="contact" class="py-20 px-4 sm:px-6 lg:px-8 bg-indigo-600">
      <div class="max-w-4xl mx-auto text-center">
        <h3 class="text-4xl font-bold text-white mb-6">
          Ready to Get Started?
        </h3>
        <p class="text-xl text-indigo-100 mb-8">
          Join thousands of developers building amazing applications with Nuxt.js
        </p>
        <button class="bg-white text-indigo-600 px-8 py-4 rounded-lg text-lg font-semibold hover:bg-gray-100 transition shadow-lg">
          Start Your Project Today
        </button>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-300 py-12 px-4 sm:px-6 lg:px-8">
      <div class="max-w-7xl mx-auto">
        <div class="grid md:grid-cols-4 gap-8 mb-8">
          <div>
            <h4 class="text-white text-lg font-semibold mb-4">Nuxt Landing</h4>
            <p class="text-sm">Building the future of web development.</p>
          </div>
          <div>
            <h5 class="text-white text-sm font-semibold mb-4">Product</h5>
            <ul class="space-y-2 text-sm">
              <li><a href="#" class="hover:text-white transition">Features</a></li>
              <li><a href="#" class="hover:text-white transition">Pricing</a></li>
              <li><a href="#" class="hover:text-white transition">Documentation</a></li>
            </ul>
          </div>
          <div>
            <h5 class="text-white text-sm font-semibold mb-4">Company</h5>
            <ul class="space-y-2 text-sm">
              <li><a href="#" class="hover:text-white transition">About</a></li>
              <li><a href="#" class="hover:text-white transition">Blog</a></li>
              <li><a href="#" class="hover:text-white transition">Careers</a></li>
            </ul>
          </div>
          <div>
            <h5 class="text-white text-sm font-semibold mb-4">Legal</h5>
            <ul class="space-y-2 text-sm">
              <li><a href="#" class="hover:text-white transition">Privacy</a></li>
              <li><a href="#" class="hover:text-white transition">Terms</a></li>
              <li><a href="#" class="hover:text-white transition">Contact</a></li>
            </ul>
          </div>
        </div>
        <div class="border-t border-gray-800 pt-8 text-center text-sm">
          <p>&copy; 2026 Nuxt Landing. All rights reserved.</p>
        </div>
      </div>
    </footer>
  </div>
</template>
