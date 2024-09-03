<script>
    let email = "";
  </script>
  
  <style>
    /* Ensure the page takes up the full height of the viewport */
    html, body {
      height: 100%;
      margin: 0;
      display: flex;
      flex-direction: column;
    }
  
    /* Content wrapper */
    .content-wrapper {
      flex: 1;
    }
  
    /* Ensure footer stays at the bottom */
    footer {
      flex-shrink: 0;
    }
  </style>
  
  <div class="content-wrapper">
    <!-- Main content goes here -->
  </div>
  
  <footer class="bg-gray-800 text-white text-sm py-10">
    <!-- Stay Connected Section -->
    <div class="text-center mb-8 px-4">
      <h4 class="font-bold mb-4">Stay Connected!</h4>
      <div class="flex flex-col md:flex-row justify-center items-center">
        <input
          type="email"
          class="bg-gray-700 p-2 w-full md:w-1/3 border border-gray-400 rounded-md"
          placeholder="Enter your email"
          bind:value={email}
        />
        <button class="p-2 bg-red-500 text-white mt-4 md:mt-0 md:ml-2 rounded-md">
          Subscribe
        </button>
      </div>
    </div>
  
    <div class="container mx-auto px-4">
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
        <!-- First Column: Information and Help Sections -->
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
          <!-- Information Section -->
          <div class="px-4">
            <h4 class="font-bold mb-4">INFORMATION</h4>
            <ul>
              <li><a href="#" class="hover:text-red-500">About DigiKey</a></li>
              <li><a href="#" class="hover:text-red-500">Marketplace</a></li>
              <li><a href="#" class="hover:text-red-500">Sell on DigiKey.com</a></li>
              <li><a href="#" class="hover:text-red-500">Site Map</a></li>
              <li><a href="#" class="hover:text-red-500">Digital Solutions</a></li>
              <li><a href="#" class="hover:text-red-500">Newsroom</a></li>
            </ul>
          </div>
          <!-- Help Section -->
          <div class="px-4">
            <h4 class="font-bold mb-4">HELP</h4>
            <ul>
              <li><a href="#" class="hover:text-red-500">Help and Support</a></li>
              <li><a href="#" class="hover:text-red-500">Order Status</a></li>
              <li><a href="#" class="hover:text-red-500">Shipping Rates/Options</a></li>
              <li><a href="#" class="hover:text-red-500">Returns and Order Issues</a></li>
            </ul>
          </div>
        </div>
        
        <!-- Second Column: Contact Us and Social Media Icons -->
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
          <!-- Contact Us Section -->
          <div class="px-4">
            <h4 class="font-bold mb-4">CONTACT US</h4>
            <ul>
              <li class="mb-2"><i class="far fa-comments"></i> Chat</li>
              <li class="mb-2"><i class="fas fa-phone"></i> 000-800-040-4249</li>
              <li class="mb-2"><i class="fas fa-envelope"></i> india.support@digikey.com</li>
              <li class="mb-2"><i class="fas fa-user-friends"></i> Co-Browse</li>
            </ul>
            <div class="flex flex-col space-y-2">
              <img src="path-to-ecia-logo.png" alt="ECIA Member" class="w-full md:w-auto" />
              <img src="path-to-viking-cloud.png" alt="Trusted Commerce" class="w-full md:w-auto" />
            </div>
          </div>
          <!-- Social Media Icons -->
          <div class="text-center px-4 mt-8 md:mt-0">
            <h4 class="font-bold mb-4">FOLLOW US</h4>
            <div class="flex justify-center space-x-4">
              <a href="#" class="hover:text-red-500 hover:scale-110 transition-transform duration-300">
                <i class="fab fa-facebook-f"></i>
              </a>
              <a href="#" class="hover:text-red-500 hover:scale-110 transition-transform duration-300">
                <i class="fab fa-twitter"></i>
              </a>
              <a href="#" class="hover:text-red-500 hover:scale-110 transition-transform duration-300">
                <i class="fab fa-youtube"></i>
              </a>
              <a href="#" class="hover:text-red-500 hover:scale-110 transition-transform duration-300">
                <i class="fab fa-instagram"></i>
              </a>
              <a href="#" class="hover:text-red-500 hover:scale-110 transition-transform duration-300">
                <i class="fab fa-linkedin-in"></i>
              </a>
            </div>
            <div class="mt-4 flex flex-col md:flex-row justify-center space-y-4 md:space-y-0 md:space-x-4">
              <a href="#"><img src="path-to-app-store.png" alt="App Store" class="inline-block hover:scale-110 transition-transform duration-300" /></a>
              <a href="#"><img src="path-to-google-play.png" alt="Google Play" class="inline-block hover:scale-110 transition-transform duration-300" /></a>
            </div>
          </div>
        </div>
      </div>
  
      <!-- Footer Links Section -->
      <div class="mt-10 flex-center px-4">
        <ul class="flex flex-wrap justify-center space-x-4">
          <li><a href="#" class="hover:text-red-500">India</a></li>
          <span>|</span>
          <li><a href="#" class="hover:text-red-500">Copyright © 1995-2024, DigiKey.</a></li>
          <span>|</span>
          <li><a href="#" class="hover:text-red-500">All Rights Reserved</a></li>
          <span>|</span>
          <li><a href="#" class="hover:text-red-500">Terms & Conditions</a></li>
          <span>|</span>
          <li><a href="#" class="hover:text-red-500">Privacy Notice</a></li>
          <span>|</span>
          <li><a href="#" class="hover:text-red-500">Cookie Settings</a></li>
        </ul>
      </div>
    </div>
  </footer>
  