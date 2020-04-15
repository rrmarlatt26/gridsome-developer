<template>
  <div
    class="font-sans text-gray-800 leading-normal flex flex-col min-h-screen"
  >
    <header class="border-t-10 border-blue-600">
      <nav class="container mx-auto flex justify-between items-center py-8">
        <a href>Logo</a>
        <ul class="uppercase tracking-wide font-bold flex items-center">
          <li class="mr-8">
            <g-link class="text-gray-800 hover:text-gray-699" to="/"
              >Home</g-link
            >
          </li>
          <li class="mr-8">
           <g-link class="text-gray-800 hover:text-gray-699" to="/About/"
              >About Us</g-link
            >
          </li>
        </ul>
      </nav>
    </header>
    <div class="flex-grow container mx-auto">
      <slot />
    </div>
    <footer class="bg-blue-600 text-white py-5">
      <div class="container mx-auto flex items-center justify-between">
        <div>Copyright 2019. All Rights Reserved</div>

        <ul class="flex items-center">
          <li class="mr-8"><font-awesome :icon="['fab', 'twitter']" /></li>
          <li class="mr-8"><font-awesome :icon="['fab', 'youtube']" /></li>
          <li class="mr-8"><font-awesome :icon="['fab', 'facebook']" /></li>
        </ul>
      </div>
    </footer>
  </div>
</template>
