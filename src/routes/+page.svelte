<script lang="ts">
  import Navbar from '$lib/Navbar.svelte';
  import Footer from '$lib/Footer.svelte';
  import Button from '$lib/Button.svelte';
</script>

<div class="min-h-screen font-sans text-dark bg-cream overflow-x-hidden">
  <Navbar />

  <!-- Hero Section -->
  <section class="pt-32 pb-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto text-center">
    <div class="mb-6">
      <span class="text-xs font-bold tracking-widest text-gray-500 uppercase">Curated Audio Gear • Vilnius, Lithuania</span>
    </div>
    <h1 class="text-5xl md:text-7xl font-serif mb-6 leading-tight">
      Trust your ears, <br class="hidden md:block" /> not just specs
    </h1>
    <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10 leading-relaxed">
      Experience premium audio gear before you buy. Expert consultations, 200+ demo products, 
      and a curated selection of legendary staples and hidden gems.
    </p>
    <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-20">
      <Button href="#" type="primary">Visit Showroom</Button>
      <Button href="#" type="outline">Shop Online</Button>
    </div>

    <!-- Hero Image -->
    <div class="relative w-full max-w-5xl mx-auto rounded-2xl overflow-hidden shadow-2xl border border-gray-200 bg-white aspect-[16/9] mb-16 group">
      <img src="/generated/image-modern-audio-showroom-interior-with-prem-1765563970352-0.webp" alt="Soundium showroom interior" class="w-full h-full object-cover" />
      
      <!-- Decorative Elements -->
      <div class="absolute -left-12 bottom-12 w-24 h-24 bg-primary-brand rounded-full blur-2xl opacity-20"></div>
      <div class="absolute -right-12 top-12 w-32 h-32 bg-primary-light rounded-full blur-2xl opacity-20"></div>
    </div>

    <!-- Brands -->
    <div class="text-center">
      <p class="text-sm text-gray-500 mb-6">Featuring legendary brands and hidden gems for audiophiles and professionals</p>
      <div class="flex flex-wrap justify-center items-center gap-8 md:gap-12 opacity-70 hover:opacity-100 transition-all duration-500">
        <span class="font-bold text-xl text-gray-700">Sennheiser</span>
        <span class="font-bold text-xl text-gray-700">Audio-Technica</span>
        <span class="font-bold text-xl text-gray-700">Bang & Olufsen</span>
        <span class="font-bold text-xl text-gray-700">Beyerdynamic</span>
        <span class="font-bold text-xl text-gray-700">Audeze</span>
        <span class="font-bold text-xl text-gray-700">FiiO</span>
      </div>
    </div>
  </section>

  <!-- Stats Section -->
  <section class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-3xl mx-auto">
        More than just another online store
      </h2>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-16">
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">200+</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Demo Products</div>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">23</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">European Countries</div>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">3-Year</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Warranty</div>
        </div>
      </div>

      <!-- Product Categories Carousel -->
      <div class="flex gap-4 overflow-hidden relative">
        <div class="absolute inset-y-0 left-0 w-20 bg-gradient-to-r from-white to-transparent z-10"></div>
        <div class="absolute inset-y-0 right-0 w-20 bg-gradient-to-l from-white to-transparent z-10"></div>
        
        <div class="flex gap-4 animate-scroll">
            <!-- Card 1 -->
            <div class="w-64 h-80 bg-gradient-to-br from-gray-100 to-gray-200 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-xs font-bold">
                    Headphones
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">Premium Audio</div>
                    <div class="text-xs opacity-80">Over-ear & In-ear</div>
                </div>
            </div>
            <!-- Card 2 -->
            <div class="w-64 h-80 bg-gradient-to-br from-gray-200 to-gray-300 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-xs font-bold">
                    Speakers
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">Hi-Fi Systems</div>
                    <div class="text-xs opacity-80">Bookshelf & Studio</div>
                </div>
            </div>
            <!-- Card 3 -->
            <div class="w-64 h-80 bg-gradient-to-br from-gray-100 to-gray-200 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-xs font-bold">
                    Turntables
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">Vinyl Experience</div>
                    <div class="text-xs opacity-80">Analog & Digital</div>
                </div>
            </div>
             <!-- Card 4 -->
            <div class="w-64 h-80 bg-gradient-to-br from-gray-200 to-gray-300 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-xs font-bold">
                    DJ Gear
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">Professional Setup</div>
                    <div class="text-xs opacity-80">Controllers & Mixers</div>
                </div>
            </div>
             <!-- Card 5 -->
            <div class="w-64 h-80 bg-gradient-to-br from-gray-100 to-gray-200 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-xs font-bold">
                    Studio
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/60 to-transparent p-4 text-white">
                    <div class="font-bold">Production Tools</div>
                    <div class="text-xs opacity-80">Interfaces & Monitors</div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- The Soundium Difference -->
  <section class="bg-dark text-white py-24 overflow-hidden">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4">The Soundium <br /> difference</h2>
      <p class="text-center text-gray-400 mb-16">Knowledge over sales. Trust your ears, not just specs.</p>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
        <!-- Online Only -->
        <div>
          <h3 class="text-xl font-serif mb-2">Online-Only Stores</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            Buy based on specs and reviews. Hope it sounds good. Deal with returns if it doesn't. No hands-on experience before purchase.
          </p>
          <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700 relative">
             <div class="space-y-3">
                <div class="flex items-center gap-3">
                   <div class="w-2 h-2 bg-red-500 rounded-full"></div>
                   <span class="text-sm text-gray-400">No demo before buying</span>
                </div>
                <div class="flex items-center gap-3">
                   <div class="w-2 h-2 bg-red-500 rounded-full"></div>
                   <span class="text-sm text-gray-400">Generic advice</span>
                </div>
                <div class="flex items-center gap-3">
                   <div class="w-2 h-2 bg-red-500 rounded-full"></div>
                   <span class="text-sm text-gray-400">Overwhelming selection</span>
                </div>
                <div class="flex items-center gap-3">
                   <div class="w-2 h-2 bg-red-500 rounded-full"></div>
                   <span class="text-sm text-gray-400">High return rates</span>
                </div>
             </div>
          </div>
        </div>

        <!-- Soundium Way -->
        <div>
          <h3 class="text-xl font-serif mb-2">The Soundium Way</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            Test 200+ products in our showroom. Get expert guidance. Make informed decisions. Buy with confidence knowing exactly what you're getting.
          </p>
          <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700 relative">
             <div class="space-y-3">
                <div class="flex items-center gap-3">
                   <div class="w-2 h-2 bg-primary-brand rounded-full"></div>
                   <span class="text-sm text-gray-300">200+ demo products</span>
                </div>
                <div class="flex items-center gap-3">
                   <div class="w-2 h-2 bg-primary-brand rounded-full"></div>
                   <span class="text-sm text-gray-300">Expert consultations</span>
                </div>
                <div class="flex items-center gap-3">
                   <div class="w-2 h-2 bg-primary-brand rounded-full"></div>
                   <span class="text-sm text-gray-300">Curated selection</span>
                </div>
                <div class="flex items-center gap-3">
                   <div class="w-2 h-2 bg-primary-brand rounded-full"></div>
                   <span class="text-sm text-gray-300">3-year warranty</span>
                </div>
             </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Features Section 1 -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        Experience audio gear the way it should be
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Card 1: Showroom -->
        <div class="lg:col-span-2 bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden relative group">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">200+ products to demo</h3>
                <p class="text-gray-500 text-sm">Visit our Vilnius showroom and test headphones, speakers, and turntables before you buy. Experience the difference that hands-on testing makes.</p>
            </div>
            <div class="rounded-xl h-64 relative overflow-hidden">
                <img src="/generated/image-customer-trying-on-high-end-headphones-i-1765563974826-1.webp" alt="Customer testing headphones" class="w-full h-full object-cover rounded-xl" />
            </div>
        </div>

        <!-- Card 2: Expert Team -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">Expert consultations</h3>
                <p class="text-gray-500 text-sm">Our team knows gear inside-out. Get personalized recommendations based on your needs, not sales quotas.</p>
            </div>
            <div class="rounded-xl h-48 relative overflow-hidden">
                <img src="/generated/image-audio-expert-consultant-helping-a-custom-1765563977547-2.webp" alt="Expert consultation" class="w-full h-full object-cover rounded-xl" />
            </div>
        </div>

        <!-- Card 3: Curated Selection -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 rounded-xl mb-6 relative overflow-hidden">
                <img src="/generated/image-close-up-of-premium-audio-equipment-disp-1765563980297-3.webp" alt="Premium audio equipment" class="w-full h-full object-cover rounded-xl" />
             </div>
             <h3 class="text-xl font-serif mb-2">Curated selection</h3>
             <p class="text-gray-500 text-sm">We stock legendary industry staples and hidden gems - no overwhelming catalogs, just quality gear.</p>
        </div>

        <!-- Card 4: European Shipping -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-gray-50 rounded-xl mb-6 p-4 flex items-center justify-center">
                <div class="text-center">
                    <div class="text-5xl font-serif mb-4">23</div>
                    <div class="text-sm text-gray-500">European Countries</div>
                    <div class="mt-4 text-xs text-gray-400">Free shipping over €149</div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Europe-wide shipping</h3>
             <p class="text-gray-500 text-sm">Fast delivery to 23 countries. Orders by 17:00 delivered in 3-5 business days.</p>
        </div>

        <!-- Card 5: Warranty -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-gray-50 rounded-xl mb-6 p-4 flex items-center justify-center relative">
                 <div class="text-center">
                    <div class="text-5xl font-serif mb-4">3</div>
                    <div class="text-sm text-gray-500">Year Warranty</div>
                    <div class="mt-4 text-xs text-gray-400">+ 30-day money back</div>
                 </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Quality guarantee</h3>
             <p class="text-gray-500 text-sm">3-year warranty on all products plus 30-day money-back guarantee. We stand behind what we sell.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonial 1 -->
  <section class="py-16 bg-cream">
    <div class="max-w-4xl mx-auto px-4 text-center">
        <div class="flex justify-center mb-8">
            <div class="w-16 h-16 rounded-full overflow-hidden">
                <img src="/generated/image-happy-customer-portrait-holding-new-head-1765563983035-4.webp" alt="Robert" class="w-full h-full object-cover" />
            </div>
        </div>
        <blockquote class="text-2xl md:text-3xl font-serif leading-relaxed mb-8">
            "The staff is not pushy and really helps you form a complete picture so you can make an informed decision. It's refreshing to have a vibrant physical store in this day and age."
        </blockquote>
        <div class="flex items-center justify-center gap-4">
            <div class="text-center">
                <div class="font-bold text-sm">Robert</div>
                <div class="text-xs text-gray-500">Soundium Customer</div>
            </div>
        </div>
    </div>
  </section>

  <!-- Features Section 2 -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        Shop your way - <br /> online or in-store
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Card 1 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-gray-50 rounded-xl h-64 mb-8 p-4 relative overflow-hidden flex items-center justify-center">
                <div class="text-center">
                    <div class="text-6xl mb-4">🏪</div>
                    <div class="text-lg font-serif mb-2">Visit Our Showroom</div>
                    <div class="text-sm text-gray-500">T. Ševčenkos g. 18, Vilnius</div>
                    <div class="text-sm text-gray-500">Mon-Fri 10:00-18:00</div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Physical store experience</h3>
            <p class="text-gray-500 text-sm">Test products hands-on, get expert advice, and pick up your order instantly from our Vilnius location.</p>
        </div>

        <!-- Card 2 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-gray-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                 <div class="text-center">
                    <div class="text-6xl mb-4">📦</div>
                    <div class="text-lg font-serif mb-2">Online Shopping</div>
                    <div class="text-sm text-gray-500">Free shipping over €149</div>
                    <div class="text-sm text-gray-500">3-5 day delivery</div>
                 </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Shop from anywhere</h3>
            <p class="text-gray-500 text-sm">Browse our full catalog online and get fast delivery to 23 European countries with secure payment options.</p>
        </div>

        <!-- Card 3 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-gray-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                <div class="text-center">
                    <div class="text-6xl mb-4">💬</div>
                    <div class="text-lg font-serif mb-2">Discord Community</div>
                    <div class="text-sm text-gray-500">Weekly contests</div>
                    <div class="text-sm text-gray-500">€30 vouchers</div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Join our community</h3>
            <p class="text-gray-500 text-sm">Connect with fellow audio enthusiasts, share your setup, and win weekly prizes in our Discord server.</p>
        </div>

        <!-- Card 4 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-gray-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                <div class="text-center">
                    <div class="text-6xl mb-4">🏢</div>
                    <div class="text-lg font-serif mb-2">Business Accounts</div>
                    <div class="text-sm text-gray-500">VAT-free pricing</div>
                    <div class="text-sm text-gray-500">Invoicing available</div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">B2B solutions</h3>
            <p class="text-gray-500 text-sm">Register for a business account to access special pricing, invoicing, and VAT-free options for eligible companies.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Visit Showroom CTA -->
  <section class="py-24 bg-cream relative overflow-hidden">
    <!-- Floating Icons Background (Simplified) -->
    <div class="absolute inset-0 opacity-10 pointer-events-none">
        <div class="absolute top-10 left-10 w-12 h-12 bg-gray-800 rounded-lg transform rotate-12"></div>
        <div class="absolute top-20 right-20 w-12 h-12 bg-gray-700 rounded-lg transform -rotate-6"></div>
        <div class="absolute bottom-20 left-1/3 w-12 h-12 bg-gray-600 rounded-lg transform rotate-45"></div>
        <div class="absolute bottom-10 right-1/4 w-12 h-12 bg-gray-800 rounded-lg transform -rotate-12"></div>
    </div>

    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <div class="inline-block bg-gray-100 text-gray-800 px-4 py-1 rounded-full text-xs font-bold mb-6">
            Experience the difference
        </div>
        <h2 class="text-4xl md:text-6xl font-serif mb-4">200+ products <br /> ready to demo</h2>
        <p class="text-gray-500 mb-10">Visit our Vilnius showroom Monday-Friday 10:00-18:00</p>
        
        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Get Directions</Button>
            <Button href="#" type="white">Shop Online</Button>
        </div>
    </div>
  </section>

  <!-- Team Section -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        Meet the team behind <br /> your next audio upgrade
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Left Large Card -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 md:row-span-2 flex flex-col">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">Knowledge over sales</h3>
                <p class="text-gray-500 text-sm">Our team focuses on helping and educating rather than pushing products. We're here to help you make informed decisions, not just close a sale.</p>
            </div>
            <div class="flex-1 rounded-2xl relative overflow-hidden min-h-[300px]">
                <img src="/generated/image-professional-team-of-four-people-in-mode-1765563985899-5.webp" alt="Soundium team" class="w-full h-full object-cover rounded-2xl" />
            </div>
        </div>

        <!-- Right Top Card -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="mb-4">
                <h3 class="text-xl font-serif mb-2">Expert consultations</h3>
                <p class="text-gray-500 text-sm">Vincas, Martyna, Benas, and Gytis can geek out over gear with you or help you find exactly what you need.</p>
            </div>
            <div class="bg-gray-50 rounded-xl p-6">
                <div class="space-y-3">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-full bg-gray-200 flex items-center justify-center text-sm font-bold">V</div>
                        <div>
                            <div class="font-bold text-sm">Vincas</div>
                            <div class="text-xs text-gray-500">CEO / Purchases</div>
                        </div>
                    </div>
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-full bg-gray-200 flex items-center justify-center text-sm font-bold">M</div>
                        <div>
                            <div class="font-bold text-sm">Martyna</div>
                            <div class="text-xs text-gray-500">Customer Support</div>
                        </div>
                    </div>
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-full bg-gray-200 flex items-center justify-center text-sm font-bold">B</div>
                        <div>
                            <div class="font-bold text-sm">Benas</div>
                            <div class="text-xs text-gray-500">Consultations</div>
                        </div>
                    </div>
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-full bg-gray-200 flex items-center justify-center text-sm font-bold">G</div>
                        <div>
                            <div class="font-bold text-sm">Gytis</div>
                            <div class="text-xs text-gray-500">Consultations</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Right Bottom Card -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <h3 class="text-xl font-serif mb-2">Visit us in Vilnius</h3>
            <p class="text-gray-500 text-sm mb-6">Stop by our showroom for a personalized consultation and hands-on product testing.</p>
            <div class="bg-gray-50 rounded-xl p-4">
                <div class="text-sm mb-2">
                    <div class="font-bold">Address</div>
                    <div class="text-gray-600">T. Ševčenkos g. 18</div>
                    <div class="text-gray-600">Vilnius 03111, Lithuania</div>
                </div>
                <div class="text-sm">
                    <div class="font-bold">Hours</div>
                    <div class="text-gray-600">Mon-Fri: 10:00-18:00</div>
                    <div class="text-xs text-gray-500">(Lunch: 13:30-14:30)</div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Featured Brands Grid -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        Legendary brands and hidden gems
      </h2>

      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-4">
         <!-- Row 1 -->
         <div class="aspect-square bg-gradient-to-br from-gray-100 to-gray-200 rounded-2xl flex items-center justify-center">
            <span class="text-2xl font-bold text-gray-700">Sennheiser</span>
         </div>
         <div class="aspect-square bg-white rounded-2xl flex items-center justify-center border border-gray-100">
            <span class="text-2xl font-bold text-gray-700">Audio-Technica</span>
         </div>
         <div class="col-span-2 bg-gradient-to-br from-gray-50 to-gray-100 rounded-2xl p-8 flex flex-col justify-center">
            <div class="text-center">
                <div class="text-4xl font-serif mb-4">🎧</div>
                <h3 class="text-xl font-serif mb-2">Premium Headphones</h3>
                <p class="text-sm text-gray-600">From studio monitors to wireless freedom</p>
            </div>
         </div>

         <!-- Row 2 -->
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
            <span class="text-3xl font-bold text-gray-700">Bang & Olufsen</span>
         </div>
         <div class="aspect-square bg-gradient-to-br from-gray-100 to-gray-200 rounded-2xl flex items-center justify-center">
             <span class="text-xl font-bold text-gray-700">Beyerdynamic</span>
         </div>
         <div class="aspect-square bg-gradient-to-br from-gray-100 to-gray-200 rounded-2xl flex items-center justify-center">
             <span class="text-xl font-bold text-gray-700">Audeze</span>
         </div>

         <!-- Row 3 -->
         <div class="col-span-2 bg-gradient-to-br from-gray-50 to-gray-100 rounded-2xl p-8 flex flex-col justify-center">
            <div class="text-center">
                <div class="text-4xl font-serif mb-4">🔊</div>
                <h3 class="text-xl font-serif mb-2">Hi-Fi Speakers</h3>
                <p class="text-sm text-gray-600">Bookshelf, studio monitors, and more</p>
            </div>
         </div>
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
             <span class="text-2xl font-bold text-gray-700">FiiO</span>
         </div>
         
         <!-- Row 4 -->
         <div class="aspect-square bg-gradient-to-br from-gray-100 to-gray-200 rounded-2xl flex items-center justify-center">
             <span class="text-xl font-bold text-gray-700">AlphaTheta</span>
         </div>
         <div class="aspect-square bg-gradient-to-br from-gray-100 to-gray-200 rounded-2xl flex items-center justify-center">
             <span class="text-xl font-bold text-gray-700">Kanto Audio</span>
         </div>
         <div class="col-span-2 bg-gradient-to-br from-gray-50 to-gray-100 rounded-2xl p-8 flex flex-col justify-center">
             <div class="text-center">
                <div class="text-4xl font-serif mb-4">🎵</div>
                <h3 class="text-xl font-serif mb-2">Turntables & Vinyl</h3>
                <p class="text-sm text-gray-600">Analog warmth meets modern precision</p>
            </div>
         </div>
      </div>
    </div>
  </section>

  <!-- Main CTA Section -->
  <section class="bg-dark py-24 relative overflow-hidden">
    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <h2 class="text-4xl md:text-6xl font-serif mb-8 text-white">Ready to upgrade <br /> your audio experience?</h2>
        
        <div class="flex flex-col md:flex-row justify-center gap-6 mb-10 text-sm font-medium text-gray-300">
            <div class="flex items-center gap-2">
                <div class="bg-primary-brand text-white rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                200+ products to demo in-store
            </div>
            <div class="flex items-center gap-2">
                <div class="bg-primary-brand text-white rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                Free shipping over €149
            </div>
            <div class="flex items-center gap-2">
                <div class="bg-primary-brand text-white rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                3-year warranty
            </div>
        </div>

        <div class="flex justify-center gap-4">
            <Button href="#" type="white">Visit Showroom</Button>
            <Button href="#" type="outline">Shop Online</Button>
        </div>
    </div>
  </section>

  <!-- Product Categories -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">Explore Our Collection</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Large Card Top -->
        <div class="md:col-span-2 bg-gradient-to-br from-gray-100 to-gray-200 rounded-3xl p-10 md:p-16 flex flex-col md:flex-row items-center gap-10">
            <div class="flex-1">
                <div class="text-6xl mb-8">🎧</div>
                <h3 class="text-4xl font-serif mb-4">Headphones</h3>
                <p class="text-gray-600">From studio-grade monitors to premium wireless freedom</p>
            </div>
            <div class="flex-1 bg-white/90 backdrop-blur rounded-2xl p-8 shadow-sm">
                <div class="text-xs font-bold text-gray-400 uppercase mb-4">Featured Brands</div>
                <div class="space-y-3 mb-6">
                    <div class="text-lg font-bold">Sennheiser</div>
                    <div class="text-lg font-bold">Audio-Technica</div>
                    <div class="text-lg font-bold">Beyerdynamic</div>
                    <div class="text-lg font-bold">Audeze</div>
                </div>
                <button class="bg-dark text-white px-4 py-2 rounded-lg text-sm font-bold w-full">Browse Headphones &rarr;</button>
            </div>
        </div>

        <!-- Bottom Left -->
        <div class="bg-gradient-to-br from-gray-200 to-gray-300 rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="text-6xl mb-4">🔊</div>
            <div class="bg-white/90 backdrop-blur rounded-2xl p-6 shadow-sm mt-auto">
                <h3 class="text-2xl font-serif mb-2">Speakers</h3>
                <p class="text-gray-600 text-sm mb-4">Bookshelf, studio monitors, and portable options</p>
                <button class="bg-dark text-white px-4 py-2 rounded-lg text-xs font-bold w-full">Explore Speakers &rarr;</button>
            </div>
        </div>

        <!-- Bottom Right -->
        <div class="bg-gradient-to-br from-gray-100 to-gray-200 rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="text-6xl mb-4">🎵</div>
            <div class="bg-white/90 backdrop-blur rounded-2xl p-6 shadow-sm mt-auto">
                <h3 class="text-2xl font-serif mb-2">Turntables</h3>
                <p class="text-gray-600 text-sm mb-4">Vinyl experience with analog warmth and modern precision</p>
                <button class="bg-dark text-white px-4 py-2 rounded-lg text-xs font-bold w-full">View Turntables &rarr;</button>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif mb-16">Frequently Asked Questions</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-x-12 gap-y-6">
        {#each [
            "Can I test products before buying?",
            "What is your return policy?",
            "Do you ship internationally?",
            "What warranty do you offer?",
            "Where is your showroom located?",
            "Do you offer business accounts?",
            "How long does shipping take?",
            "Can I pick up my order in-store?"
        ] as question}
            <div class="border-b border-gray-200 py-4 flex justify-between items-center group cursor-pointer">
                <span class="font-medium text-lg group-hover:text-primary-brand transition-colors">{question}</span>
                <div class="w-6 h-6 rounded-full bg-dark text-white flex items-center justify-center text-sm group-hover:bg-primary-brand transition-colors">+</div>
            </div>
        {/each}
      </div>
    </div>
  </section>

  <Footer />
</div>

<style>
  /* Custom Scroll Animation */
  @keyframes scroll {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
  }
  .animate-scroll {
    animation: scroll 20s linear infinite;
  }
  
  @keyframes spin-slow {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }
  .animate-spin-slow {
    animation: spin-slow 20s linear infinite;
  }
</style>

