<script lang="ts">
  import Button from './Button.svelte';
  
  let isMenuOpen = false;
</script>

<nav class="fixed top-0 left-0 right-0 z-50 bg-cream/90 backdrop-blur-sm border-b border-gray-200/50">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center h-20">
      <!-- Logo -->
      <div class="flex-shrink-0 flex items-center">
        <a href="/" class="flex items-center gap-2">
          <!-- Soundium Logo Icon -->
          <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle cx="16" cy="16" r="16" fill="#191817"/>
            <path d="M10 12 C10 12, 12 10, 16 10 C20 10, 22 12, 22 12 L22 20 C22 20, 20 22, 16 22 C12 22, 10 20, 10 20 Z" fill="oklch(0.696 0.17 162.48)"/>
            <circle cx="16" cy="16" r="3" fill="white"/>
            <path d="M8 16 L10 16 M22 16 L24 16" stroke="oklch(0.696 0.17 162.48)" stroke-width="2" stroke-linecap="round"/>
          </svg>
          <span class="font-bold text-xl tracking-tight">Soundium</span>
        </a>
      </div>

      <!-- Desktop Navigation -->
      <div class="hidden md:flex items-center space-x-8">
        <a href="#" class="text-sm font-medium hover:text-primary-brand transition-colors">Shop</a>
        <a href="#" class="text-sm font-medium hover:text-primary-brand transition-colors">Showroom</a>
        <a href="#" class="text-sm font-medium hover:text-primary-brand transition-colors">Brands</a>
        <a href="#" class="text-sm font-medium hover:text-primary-brand transition-colors">Journal</a>
      </div>

      <!-- Right Side -->
      <div class="hidden md:flex items-center space-x-6">
        <a href="#" class="text-sm font-medium hover:text-primary-brand transition-colors">About</a>
        <a href="#" class="text-sm font-medium hover:text-primary-brand transition-colors">Contact</a>
        <Button href="#" className="!py-2 !px-4 !text-sm">Visit Store</Button>
      </div>

      <!-- Mobile menu button -->
      <div class="md:hidden flex items-center">
        <button on:click={() => isMenuOpen = !isMenuOpen} class="text-gray-600 hover:text-gray-900 focus:outline-none">
          <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
          </svg>
        </button>
      </div>
    </div>
  </div>
</nav>
