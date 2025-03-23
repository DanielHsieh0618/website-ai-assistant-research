<template>
  <div id="webcrumbs">
    <div class="min-h-screen flex flex-col bg-white font-sans">
      <header class="flex justify-between items-center py-4 px-6 border-b border-gray-100">
        <div class="flex items-center"> <a href="https://webcrumbs.cloud/placeholder" class="flex items-center">
            <svg class="h-6 w-6 text-black" viewBox="0 0 24 24" fill="currentColor">
              <circle cx="12" cy="12" r="3.5"></circle>
              <path fill-rule="evenodd" clip-rule="evenodd"
                d="M4 8a4 4 0 014-4h8a4 4 0 014 4v8a4 4 0 01-4 4H8a4 4 0 01-4-4V8zm4-2a2 2 0 00-2 2v8a2 2 0 002 2h8a2 2 0 002-2V8a2 2 0 00-2-2H8z">
              </path>
            </svg> <span class="ml-2 font-medium text-black">photo</span> </a>
          <nav class="ml-8 hidden md:flex"> <a href="https://webcrumbs.cloud/placeholder"
              class="text-sm font-medium text-blue-500 mx-3 border-b-2 border-blue-500 pb-4 transition-all duration-200 hover:text-blue-600">Home</a>
            <a href="https://webcrumbs.cloud/placeholder"
              class="text-sm font-medium text-gray-500 mx-3 pb-4 border-b-2 border-transparent transition-all duration-200 hover:text-gray-800 hover:border-gray-300">Photos</a>
            <a href="https://webcrumbs.cloud/placeholder"
              class="text-sm font-medium text-gray-500 mx-3 pb-4 border-b-2 border-transparent transition-all duration-200 hover:text-gray-800 hover:border-gray-300">Community</a>
            <a href="https://webcrumbs.cloud/placeholder"
              class="text-sm font-medium text-gray-500 mx-3 pb-4 border-b-2 border-transparent transition-all duration-200 hover:text-gray-800 hover:border-gray-300">Support</a>
          </nav>
        </div>
        <div class="flex items-center space-x-2"> <button
            class="text-sm text-gray-500 border border-gray-300 rounded-md px-4 py-1.5 transition-all duration-200 hover:bg-gray-50">Log
            in</button> <button
            class="text-sm text-white bg-blue-500 rounded-md px-4 py-1.5 transition-all duration-200 hover:bg-blue-600">Sign
            up</button> </div>
      </header>
      <section class="bg-gray-100 flex flex-col items-center justify-center py-24 px-6 text-center">
        <div
          class="relative mb-8 w-16 h-16 bg-blue-500 rounded-full flex items-center justify-center transform transition-transform duration-300 hover:scale-110">
          <svg class="w-8 h-8 text-white" viewBox="0 0 24 24" fill="none" stroke="currentColor">
            <polygon points="5 3 19 12 5 21 5 3" fill="currentColor"></polygon>
          </svg>
        </div>
        <h1 class="text-2xl font-semibold mb-6">The largest community of photo enthusiasts</h1> <button
          class="bg-blue-500 text-white rounded-md px-6 py-2 font-medium transition-all duration-200 hover:bg-blue-600 transform hover:-translate-y-0.5">Join
          Today</button>
      </section>
      <section class="py-16 px-6 md:px-12 lg:px-16">
        <h2 class="text-xl font-semibold mb-8">Snap photos and share like never before</h2>
        <div class="grid md:grid-cols-2 gap-8 mb-16">
          <div>
            <h3 class="font-medium mb-2">Sed ut perspiciatis</h3>
            <p class="text-sm text-gray-600 mb-4">Nam libero tempore, cum soluta nobis est eligendi optio
              cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas
              assumenda est, omnis dolor repellendus.</p> <button
              class="text-sm text-blue-500 hover:text-blue-700 transition-colors duration-200">Learn more
              →</button>
          </div>
          <div>
            <h3 class="font-medium mb-2">Lorem ipsum dolor</h3>
            <p class="text-sm text-gray-600 mb-4">Temporibus autem quibusdam et aut officiis debitis aut
              rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non
              recusandae. Itaque earum rerum hic.</p> <button
              class="text-sm text-blue-500 hover:text-blue-700 transition-colors duration-200">Learn more
              →</button>
          </div>
        </div>
        <div class="grid md:grid-cols-2 gap-8 mb-16">
          <div>
            <h3 class="font-medium mb-2">Nemo enim ipsum</h3>
            <p class="text-sm text-gray-600 mb-4">Neque porro quisquam est, qui dolorem ipsum quia dolor sit
              amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore
              et dolore magnam aliquam.</p> <button
              class="text-sm text-blue-500 hover:text-blue-700 transition-colors duration-200">Learn more
              →</button>
          </div>
          <div>
            <h3 class="font-medium mb-2">Tempor incididunt</h3>
            <p class="text-sm text-gray-600 mb-4">Ut enim ad minim veniam, quis nostrud exercitation ullamco
              laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
              voluptate velit esse cillum.</p> <button
              class="text-sm text-blue-500 hover:text-blue-700 transition-colors duration-200">Learn more
              →</button>
          </div>
        </div>
        <div
          class="bg-gray-200 h-64 mb-16 flex items-center justify-center transition-transform duration-300 hover:bg-gray-300">
          <span class="text-gray-400 text-lg">Placeholder Image</span>
        </div>
        <div class="mb-16">
          <h3 class="font-medium mb-2">Sed ut perspiciatis unde omnis</h3>
          <p class="text-sm text-gray-600 mb-4">Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut
            odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.
            Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur.</p>
        </div>
        <div class="bg-gray-100 p-8 mb-16">
          <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div>
              <h3 class="font-medium mb-2">Sed ut perspiciatis unde omnis</h3>
              <p class="text-sm text-gray-600 mb-4">Nemo enim ipsam voluptatem quia voluptas sit
                aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione
                voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit
                amet, consectetur.</p>
            </div>
            <div
              class="bg-gray-200 h-56 flex items-center justify-center transition-transform duration-300 hover:bg-gray-300">
              <span class="text-gray-400 text-lg">Placeholder Image</span>
            </div>
          </div>
        </div>
        <div class="text-center mb-16">
          <h2 class="text-xl font-semibold mb-4">You&#x27;re in good company</h2>
          <p class="text-gray-600 mb-8 max-w-2xl mx-auto">Lorem ipsum dolor sit amet, consectetur adipiscing
            elit, sed do eiusmod tempor incididunt ut labore</p>
          <div class="grid grid-cols-2 md:grid-cols-4 gap-4 mb-4">
            <div
              class="bg-gray-200 h-16 flex items-center justify-center transition-all duration-200 hover:bg-gray-300">
              <span class="text-gray-400 text-sm">Logo</span>
            </div>
            <div
              class="bg-gray-200 h-16 flex items-center justify-center transition-all duration-200 hover:bg-gray-300">
              <span class="text-gray-400 text-sm">Logo</span>
            </div>
            <div
              class="bg-gray-200 h-16 flex items-center justify-center transition-all duration-200 hover:bg-gray-300">
              <span class="text-gray-400 text-sm">Logo</span>
            </div>
            <div
              class="bg-gray-200 h-16 flex items-center justify-center transition-all duration-200 hover:bg-gray-300">
              <span class="text-gray-400 text-sm">Logo</span>
            </div>
          </div>
          <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
            <div
              class="bg-gray-200 h-16 flex items-center justify-center transition-all duration-200 hover:bg-gray-300">
              <span class="text-gray-400 text-sm">Logo</span>
            </div>
            <div
              class="bg-gray-200 h-16 flex items-center justify-center transition-all duration-200 hover:bg-gray-300">
              <span class="text-gray-400 text-sm">Logo</span>
            </div>
            <div
              class="bg-gray-200 h-16 flex items-center justify-center transition-all duration-200 hover:bg-gray-300">
              <span class="text-gray-400 text-sm">Logo</span>
            </div>
            <div
              class="bg-gray-200 h-16 flex items-center justify-center transition-all duration-200 hover:bg-gray-300">
              <span class="text-gray-400 text-sm">Logo</span>
            </div>
          </div>
        </div>
        <div class="bg-gray-100 py-10 px-6 flex flex-col md:flex-row justify-between items-center">
          <p class="text-gray-600 mb-4 md:mb-0">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
            do eiusmod tempor incididunt ut labore</p>
          <div class="flex space-x-3"> <button
              class="bg-blue-500 text-white rounded-md px-6 py-2 font-medium transition-all duration-200 hover:bg-blue-600 transform hover:-translate-y-0.5">Sign
              up today</button> <button
              class="text-gray-500 border border-gray-300 bg-white rounded-md px-6 py-2 font-medium transition-all duration-200 hover:bg-gray-50">Learn
              more</button> </div>
        </div>
      </section>
      <footer class="bg-white border-t border-gray-200 py-10 px-6">
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8 mb-10">
          <div>
            <h4 class="text-xs uppercase text-gray-500 font-medium mb-4">Product</h4>
            <ul class="space-y-2">
              <li><a href="https://webcrumbs.cloud/placeholder"
                  class="text-sm text-gray-600 hover:text-gray-900 transition-colors duration-200">Features</a>
              </li>
              <li><a href="https://webcrumbs.cloud/placeholder"
                  class="text-sm text-gray-600 hover:text-gray-900 transition-colors duration-200">Pricing</a>
              </li>
            </ul>
          </div>
          <div>
            <h4 class="text-xs uppercase text-gray-500 font-medium mb-4">Company</h4>
            <ul class="space-y-2">
              <li><a href="https://webcrumbs.cloud/placeholder"
                  class="text-sm text-gray-600 hover:text-gray-900 transition-colors duration-200">About</a>
              </li>
              <li><a href="https://webcrumbs.cloud/placeholder"
                  class="text-sm text-gray-600 hover:text-gray-900 transition-colors duration-200">Careers</a>
              </li>
            </ul>
          </div>
          <div class="flex justify-center items-center"> <a href="https://webcrumbs.cloud/placeholder"
              class="flex items-center"> <svg class="h-6 w-6 text-black" viewBox="0 0 24 24" fill="currentColor">
                <circle cx="12" cy="12" r="3.5"></circle>
                <path fill-rule="evenodd" clip-rule="evenodd"
                  d="M4 8a4 4 0 014-4h8a4 4 0 014 4v8a4 4 0 01-4 4H8a4 4 0 01-4-4V8zm4-2a2 2 0 00-2 2v8a2 2 0 002 2h8a2 2 0 002-2V8a2 2 0 00-2-2H8z">
                </path>
              </svg> <span class="ml-2 font-medium text-black">photo</span> </a> </div>
          <div>
            <h4 class="text-xs uppercase text-gray-500 font-medium mb-4">Resources</h4>
            <ul class="space-y-2">
              <li><a href="https://webcrumbs.cloud/placeholder"
                  class="text-sm text-gray-600 hover:text-gray-900 transition-colors duration-200">Blog</a>
              </li>
              <li><a href="https://webcrumbs.cloud/placeholder"
                  class="text-sm text-gray-600 hover:text-gray-900 transition-colors duration-200">Support</a>
              </li>
            </ul>
          </div>
        </div>
        <div class="flex justify-center space-x-4 mb-6"> <a href="https://webcrumbs.cloud/placeholder"
            class="w-8 h-8 rounded-full bg-gray-200 flex items-center justify-center transition-all duration-200 hover:bg-gray-300">
            <i class="fa-brands fa-facebook text-gray-600"></i> </a> <a href="https://webcrumbs.cloud/placeholder"
            class="w-8 h-8 rounded-full bg-gray-200 flex items-center justify-center transition-all duration-200 hover:bg-gray-300">
            <i class="fa-brands fa-twitter text-gray-600"></i> </a> <a href="https://webcrumbs.cloud/placeholder"
            class="w-8 h-8 rounded-full bg-gray-200 flex items-center justify-center transition-all duration-200 hover:bg-gray-300">
            <i class="fa-brands fa-instagram text-gray-600"></i> </a> <a href="https://webcrumbs.cloud/placeholder"
            class="w-8 h-8 rounded-full bg-gray-200 flex items-center justify-center transition-all duration-200 hover:bg-gray-300">
            <i class="fa-brands fa-linkedin text-gray-600"></i> </a> </div>
        <div class="text-center text-xs text-gray-500">
          <p>© 2023 All rights reserved • <a href="https://webcrumbs.cloud/placeholder"
              class="underline hover:text-gray-700">Privacy Policy</a> • <a href="https://webcrumbs.cloud/placeholder"
              class="underline hover:text-gray-700">Terms</a>
          </p>
        </div>
      </footer>
    </div>
  </div>
</template>