<script>
</script>

<section class="bg-gray-950 text-white py-24 overflow-hidden relative">
  <!-- Background gradient effect -->
  <div class="absolute inset-0 bg-gradient-to-b from-gray-900 to-black opacity-100"></div>
  
  <div class="relative max-w-[1200px] mx-auto px-6 text-center">
    <h2 class="text-5xl font-bold mb-6 tracking-tight leading-tight">
      Intelligent Design<br>Coordination
    </h2>
    <p class="text-gray-400 text-lg max-w-2xl mx-auto mb-16 leading-relaxed">
      AI agents automatically coordinate dependencies across your autonomous system stack. Track every module, integration point, and design decision in real-time—no more fragmented tools or lost context.
    </p>

    <!-- UI Mockup -->
    <div class="bg-white rounded-xl shadow-2xl overflow-hidden text-left text-gray-900 mx-auto max-w-[1000px] border border-blue-400/30">
      <!-- Window Controls -->
      <div class="bg-gray-50 border-b border-gray-200 px-4 py-3 flex items-center gap-2">
        <div class="flex gap-1.5">
          <div class="w-3 h-3 rounded-full bg-red-400"></div>
          <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
          <div class="w-3 h-3 rounded-full bg-green-400"></div>
        </div>
        <div class="ml-4 flex items-center gap-2 text-xs font-medium text-gray-600 bg-white px-2 py-1 rounded border border-gray-200 shadow-sm">
           <span class="w-3 h-3 bg-gray-800 rounded-full flex items-center justify-center text-[8px] text-white">V</span>
           Voyager AV
           <span class="text-gray-400">▼</span>
        </div>
      </div>

      <div class="flex h-[500px]">
        <!-- Sidebar -->
        <div class="w-48 bg-gray-50 border-r border-gray-200 p-3 flex flex-col gap-1">
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">🕒</span> Recently opened
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-900 bg-white shadow-sm border border-gray-200 rounded cursor-pointer">
            <span class="opacity-70">🤖</span> System modules
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">👁️</span> Perception
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">🧠</span> Planning
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">🎮</span> Control
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">🔬</span> Simulation
          </div>
          
          <div class="mt-auto text-[10px] text-gray-400 px-2">42 modules</div>
        </div>

        <!-- Main List -->
        <div class="flex-1 bg-white flex flex-col">
          <div class="border-b border-gray-100 p-3">
             <div class="relative">
                <span class="absolute left-2 top-1.5 text-gray-400 text-xs">🔍</span>
                <input type="text" placeholder="Search parts and designs..." class="w-full bg-gray-50 border border-gray-200 rounded pl-7 pr-3 py-1 text-xs focus:outline-none focus:border-blue-500">
             </div>
          </div>
          <div class="flex-1 overflow-y-auto">
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-blue-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">BE</div>
                   <span class="text-xs font-medium text-gray-700">LiDAR Detection</span>
                </div>
                <div class="text-[10px] text-gray-400 group-hover:text-blue-500">R6-13 · 318-1793</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 bg-blue-50/50 cursor-pointer">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-blue-100 text-blue-600 rounded flex items-center justify-center text-[8px]">EA</div>
                   <span class="text-xs font-medium text-gray-900">Path Planning Core</span>
                </div>
                <div class="text-[10px] text-gray-400">318-8231</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-blue-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">SP</div>
                   <span class="text-xs font-medium text-gray-700">Object Detection</span>
                </div>
                <div class="text-[10px] text-gray-400 group-hover:text-blue-500">R9 · 318-3327</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-blue-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">KH</div>
                   <span class="text-xs font-medium text-gray-700">Localization Core</span>
                </div>
                <div class="text-[10px] text-gray-400 group-hover:text-blue-500">R2 · 318-2684</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-blue-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">CK</div>
                   <span class="text-xs font-medium text-gray-700">Motion Controller</span>
                </div>
                <div class="text-[10px] text-gray-400 group-hover:text-blue-500">318-1924</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-blue-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">G</div>
                   <span class="text-xs font-medium text-gray-700">Sensor Fusion</span>
                </div>
             </div>
          </div>
        </div>

        <!-- Right Panel -->
        <div class="w-80 bg-white border-l border-gray-200 flex flex-col">
          <div class="p-3 border-b border-gray-100 flex justify-between items-center">
             <span class="text-[10px] font-bold text-gray-400 uppercase tracking-wider">Module Detail</span>
             <button class="text-[10px] border border-gray-200 rounded px-2 py-1 hover:bg-gray-50 flex items-center gap-1">
                <span>👤</span> Take over as DRI
             </button>
          </div>
          
          <div class="p-4 flex-1 overflow-y-auto">
             <div class="text-[10px] font-bold text-gray-400 uppercase tracking-wider mb-2">Select version to open</div>
             
             <!-- Version Item -->
             <div class="mb-4 relative pl-4 border-l-2 border-gray-200">
                <div class="absolute -left-[5px] top-0 w-2 h-2 rounded-full bg-orange-400"></div>
                <div class="flex justify-between items-start mb-1">
                   <span class="text-xs font-bold text-gray-900">Local changes</span>
                   <span class="text-[10px] text-gray-400">Saved 3 days ago</span>
                </div>
             </div>

             <!-- Version Item -->
             <div class="mb-4 relative pl-4 border-l-2 border-blue-500">
                <div class="absolute -left-[5px] top-0 w-2 h-2 rounded-full bg-blue-500"></div>
                <div class="flex justify-between items-start mb-1">
                   <span class="text-xs font-bold text-gray-900">Latest (fd649cb5)</span>
                   <span class="text-[10px] text-gray-400">Kacie Jones</span>
                </div>
                <div class="text-[10px] text-gray-600 mb-2">
                   Updated path planning algorithm to handle dynamic obstacles more efficiently in urban scenarios
                </div>
                <span class="inline-block px-1.5 py-0.5 bg-blue-100 text-blue-700 text-[9px] rounded font-medium">Current Commit</span>
             </div>

             <div class="flex items-center gap-2 mb-4 pl-4">
                <div class="w-1 h-1 bg-gray-300 rounded-full"></div>
                <div class="w-1 h-1 bg-gray-300 rounded-full"></div>
                <div class="w-1 h-1 bg-gray-300 rounded-full"></div>
                <span class="text-[10px] text-gray-400">Show 12 more commits</span>
             </div>

             <!-- Version Item -->
             <div class="mb-4 relative pl-4 border-l-2 border-gray-200">
                <div class="absolute -left-[5px] top-0 w-2 h-2 rounded-full bg-gray-300"></div>
                <div class="flex justify-between items-start mb-1">
                   <span class="text-xs font-bold text-gray-500">Revision 6</span>
                   <span class="text-[10px] text-gray-400">Cody Stronghold</span>
                </div>
                <div class="text-[10px] text-gray-500">
                   Improved sensor fusion latency by 40ms through optimized data pipeline architecture
                </div>
             </div>
             
             <!-- Version Item -->
             <div class="mb-4 relative pl-4 border-l-2 border-gray-200">
                <div class="absolute -left-[5px] top-0 w-2 h-2 rounded-full bg-gray-300"></div>
                <div class="flex justify-between items-start mb-1">
                   <span class="text-xs font-bold text-gray-500">Revision 5</span>
                   <span class="text-[10px] text-gray-400">Cody Stronghold</span>
                </div>
                <div class="text-[10px] text-gray-500">
                   Refactored localization module to support multi-sensor calibration and real-time map updates.
                </div>
             </div>
          </div>
          
          <div class="p-3 border-t border-gray-100 bg-gray-50 flex justify-between items-center">
             <div class="flex items-center gap-2 text-[10px] text-gray-500">
                <button class="hover:text-gray-900">✕</button>
                <span>Do not load dependencies</span>
             </div>
             <div class="flex gap-2">
                <button class="bg-white border border-gray-200 text-gray-700 text-[10px] px-2 py-1 rounded hover:bg-gray-50">View on nema</button>
                <button class="bg-blue-600 text-white text-[10px] px-2 py-1 rounded hover:bg-blue-700">Open</button>
             </div>
          </div>
        </div>
      </div>
    </div>
    
    <!-- Bottom Integrations -->
    <div class="mt-12 flex items-center justify-center gap-4 bg-[#1E293B] rounded-lg p-4 max-w-4xl mx-auto border border-gray-700">
       <div class="flex items-center gap-4 border-r border-gray-600 pr-4">
          <div class="w-8 h-8 bg-orange-500 rounded flex items-center justify-center font-bold text-white text-xs">ROS</div>
          <div class="w-8 h-8 bg-blue-500 rounded flex items-center justify-center font-bold text-white text-xs">GH</div>
          <div class="w-8 h-8 bg-purple-600 rounded flex items-center justify-center font-bold text-white text-xs">JR</div>
       </div>
       <p class="text-xs text-gray-400 text-left flex-1">
          nema integrates seamlessly with your existing robotics stack. Connect with ROS, GitHub, Jira, and your simulation environments to maintain a single source of truth across your entire development lifecycle.
       </p>
       <button class="bg-black text-white px-3 py-1.5 rounded text-xs font-semibold hover:bg-gray-800">Request access</button>
    </div>
  </div>
</section>
