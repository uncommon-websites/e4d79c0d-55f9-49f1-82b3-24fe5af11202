<script>
</script>

<section class="pt-20 pb-16 text-center max-w-[1200px] mx-auto px-6">
  <h1 class="text-6xl font-bold tracking-tight text-gray-900 mb-6 leading-[1.1]">
    Ship Autonomous Machines<br>10x Faster
  </h1>
  <p class="text-lg text-gray-600 mb-8 max-w-2xl mx-auto leading-relaxed">
    AI-powered engineering lifecycle management that coordinates design, testing, and deployment for autonomous vehicle teams. Built by MIT and Waymo engineers.
  </p>
  <button class="bg-black text-white px-6 py-3 rounded-lg hover:bg-gray-800 transition-colors font-semibold text-sm mb-20 cursor-pointer">
    Request access
  </button>

  <!-- Autonomous System Architecture Visualization -->
  <div class="relative w-full aspect-[2/1] bg-gradient-to-br from-gray-50 to-gray-100 rounded-xl overflow-hidden flex items-center justify-center border border-gray-200">
    <!-- Abstract representation of autonomous system layers -->
    <div class="relative w-full h-full flex items-center justify-center">
       <!-- Central autonomous vehicle representation -->
       <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-48 h-32 bg-gray-900 rounded-2xl shadow-2xl">
          <!-- Vehicle windows -->
          <div class="absolute top-4 left-8 right-8 h-12 bg-gray-700 rounded-t-xl border-2 border-gray-600"></div>
          <!-- Sensor dots -->
          <div class="absolute top-20 left-4 w-3 h-3 rounded-full bg-primary-400 animate-pulse"></div>
          <div class="absolute top-20 right-4 w-3 h-3 rounded-full bg-primary-400 animate-pulse" style="animation-delay: 0.3s"></div>
          <div class="absolute bottom-4 left-1/2 transform -translate-x-1/2 w-3 h-3 rounded-full bg-primary-400 animate-pulse" style="animation-delay: 0.6s"></div>
       </div>
       
       <!-- Orbiting system modules -->
       <div class="absolute top-[20%] left-[25%] w-24 h-20 bg-white rounded-lg shadow-lg border border-gray-200 p-2 flex flex-col gap-1">
          <div class="text-[8px] font-bold text-gray-400 uppercase">Perception</div>
          <div class="flex-1 bg-primary-50 rounded"></div>
       </div>
       
       <div class="absolute top-[20%] right-[25%] w-24 h-20 bg-white rounded-lg shadow-lg border border-gray-200 p-2 flex flex-col gap-1">
          <div class="text-[8px] font-bold text-gray-400 uppercase">Planning</div>
          <div class="flex-1 bg-primary-50 rounded"></div>
       </div>
       
       <div class="absolute bottom-[20%] left-[25%] w-24 h-20 bg-white rounded-lg shadow-lg border border-gray-200 p-2 flex flex-col gap-1">
          <div class="text-[8px] font-bold text-gray-400 uppercase">Control</div>
          <div class="flex-1 bg-primary-50 rounded"></div>
       </div>
       
       <div class="absolute bottom-[20%] right-[25%] w-24 h-20 bg-white rounded-lg shadow-lg border border-gray-200 p-2 flex flex-col gap-1">
          <div class="text-[8px] font-bold text-gray-400 uppercase">Simulation</div>
          <div class="flex-1 bg-primary-50 rounded"></div>
       </div>
       
       <!-- Connection lines -->
       <svg class="absolute inset-0 w-full h-full pointer-events-none" style="z-index: 0;">
          <line x1="35%" y1="30%" x2="45%" y2="45%" stroke="oklch(0.696 0.17 162.48)" stroke-width="2" stroke-dasharray="4 4" opacity="0.3"/>
          <line x1="65%" y1="30%" x2="55%" y2="45%" stroke="oklch(0.696 0.17 162.48)" stroke-width="2" stroke-dasharray="4 4" opacity="0.3"/>
          <line x1="35%" y1="70%" x2="45%" y2="55%" stroke="oklch(0.696 0.17 162.48)" stroke-width="2" stroke-dasharray="4 4" opacity="0.3"/>
          <line x1="65%" y1="70%" x2="55%" y2="55%" stroke="oklch(0.696 0.17 162.48)" stroke-width="2" stroke-dasharray="4 4" opacity="0.3"/>
       </svg>
    </div>
    
    <div class="absolute inset-0 bg-gradient-to-t from-white via-transparent to-transparent pointer-events-none"></div>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-3 gap-12 mt-20 text-left">
    <div>
      <div class="text-xs font-semibold text-gray-400 mb-2">01</div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">AI-Powered Coordination</h3>
      <p class="text-sm text-gray-500 leading-relaxed">
        Intelligent agents coordinate across perception, planning, control, and simulation teams—eliminating manual handoffs and version conflicts.
      </p>
    </div>
    <div>
      <div class="text-xs font-semibold text-gray-400 mb-2">02</div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Systems Architecture</h3>
      <p class="text-sm text-gray-500 leading-relaxed">
        MIT-validated reference architectures for autonomous systems. Start with proven patterns, iterate faster, avoid common pitfalls.
      </p>
    </div>
    <div>
      <div class="text-xs font-semibold text-gray-400 mb-2">03</div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Lifecycle Management</h3>
      <p class="text-sm text-gray-500 leading-relaxed">
        Track every design decision, test result, and deployment from concept to production. Full traceability for safety-critical systems.
      </p>
    </div>
  </div>
</section>
