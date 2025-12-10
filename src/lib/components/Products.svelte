<script>
  // No script needed
</script>

<div class="space-y-32 pb-32">
  <!-- Code Intelligence Section -->
  <section class="max-w-7xl mx-auto px-6 grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
    <div>
      <h3 class="text-4xl font-medium mb-6">Code Intelligence</h3>
      <p class="text-xl text-gray-600 mb-8 leading-relaxed">
        <strong class="text-black">Instant customization analysis.</strong> AI-powered scanning identifies every custom object, modification, and enhancement across your SAP landscape in minutes, not months.
      </p>
      <div class="flex flex-col gap-2">
        <a href="#" class="group inline-flex items-center text-black font-medium hover:opacity-70 transition-opacity">
          See it in action 
          <span class="ml-1 group-hover:translate-x-1 transition-transform">→</span>
        </a>
        <a href="#" class="text-sm text-gray-400 hover:text-black transition-colors">Book a demo</a>
      </div>
    </div>
    <div class="bg-gray-50 rounded-3xl p-12 flex items-center justify-center min-h-[400px]">
      <!-- Code Analysis Visualization -->
      <div class="relative w-full max-w-md">
        <div class="flex justify-between items-center">
          <!-- Central Analysis Engine -->
          <div class="w-16 h-16 bg-primary-600 rounded-lg flex items-center justify-center relative z-10 shadow-lg">
            <svg width="32" height="32" viewBox="0 0 24 24" fill="white"><path d="M9.4 16.6L4.8 12l4.6-4.6L8 6l-6 6 6 6 1.4-1.4zm5.2 0l4.6-4.6-4.6-4.6L16 6l6 6-6 6-1.4-1.4z"/></svg>
          </div>
          
          <!-- Analysis Categories -->
          <div class="flex flex-col gap-3">
            {#each ['Custom Programs', 'User Exits', 'BAdIs', 'Enhancements', 'Modifications', 'Tables', 'Transports'] as item, i}
              <div class="flex items-center gap-4">
                <div class="w-24 h-[1px] bg-gradient-to-r from-primary-300/40 to-transparent transform rotate-180 origin-left"></div>
                <div class="flex items-center gap-2">
                  <div class="w-2 h-2 rounded-full bg-primary-500"></div>
                  <span class="text-xs font-medium text-gray-700">{item}</span>
                </div>
              </div>
            {/each}
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Dependency Mapping Section -->
  <section class="max-w-7xl mx-auto px-6 grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
    <div>
      <h3 class="text-4xl font-medium mb-6">Dependency Mapping</h3>
      <p class="text-xl text-gray-600 mb-8 leading-relaxed">
        <strong class="text-black">See the complete picture.</strong> Automatically trace dependencies across your entire SAP system. Understand impact before you make changes, eliminating surprises during migration.
      </p>
      <div class="flex flex-col gap-2">
        <a href="#" class="group inline-flex items-center text-black font-medium hover:opacity-70 transition-opacity">
          Explore mapping 
          <span class="ml-1 group-hover:translate-x-1 transition-transform">→</span>
        </a>
        <a href="#" class="text-sm text-gray-400 hover:text-black transition-colors">Request access</a>
      </div>
    </div>
    <div class="bg-gray-900 rounded-3xl overflow-hidden min-h-[400px] relative p-8">
      <!-- Network Graph Visualization -->
      <div class="relative w-full h-full flex items-center justify-center">
        <!-- Central Node -->
        <div class="absolute w-16 h-16 bg-primary-500 rounded-full flex items-center justify-center text-white text-xs font-bold shadow-lg z-10">
          CORE
        </div>
        
        <!-- Connecting Lines -->
        <svg class="absolute inset-0 w-full h-full opacity-30">
          <line x1="50%" y1="50%" x2="20%" y2="20%" stroke="rgb(168, 85, 247)" stroke-width="2"/>
          <line x1="50%" y1="50%" x2="80%" y2="20%" stroke="rgb(168, 85, 247)" stroke-width="2"/>
          <line x1="50%" y1="50%" x2="80%" y2="80%" stroke="rgb(168, 85, 247)" stroke-width="2"/>
          <line x1="50%" y1="50%" x2="20%" y2="80%" stroke="rgb(168, 85, 247)" stroke-width="2"/>
          <line x1="50%" y1="50%" x2="50%" y2="10%" stroke="rgb(168, 85, 247)" stroke-width="2"/>
          <line x1="50%" y1="50%" x2="90%" y2="50%" stroke="rgb(168, 85, 247)" stroke-width="2"/>
        </svg>
        
        <!-- Dependency Nodes -->
        <div class="absolute top-[10%] left-[20%] w-10 h-10 bg-primary-400 rounded-full flex items-center justify-center text-white text-[10px] font-medium">SD</div>
        <div class="absolute top-[10%] right-[20%] w-10 h-10 bg-primary-400 rounded-full flex items-center justify-center text-white text-[10px] font-medium">MM</div>
        <div class="absolute bottom-[10%] right-[20%] w-10 h-10 bg-primary-400 rounded-full flex items-center justify-center text-white text-[10px] font-medium">FI</div>
        <div class="absolute bottom-[10%] left-[20%] w-10 h-10 bg-primary-400 rounded-full flex items-center justify-center text-white text-[10px] font-medium">PP</div>
        <div class="absolute top-[5%] left-[50%] -translate-x-1/2 w-10 h-10 bg-primary-300 rounded-full flex items-center justify-center text-white text-[10px] font-medium">HR</div>
        <div class="absolute top-[50%] right-[5%] w-10 h-10 bg-primary-300 rounded-full flex items-center justify-center text-white text-[10px] font-medium">WM</div>
      </div>
    </div>
  </section>

  <!-- Migration Acceleration Section -->
  <section class="max-w-7xl mx-auto px-6 grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
    <div>
      <h3 class="text-4xl font-medium mb-6">Migration Acceleration</h3>
      <p class="text-xl text-gray-600 mb-8 leading-relaxed">
        <strong class="text-black">From analysis to action.</strong> Deploy pilots in 48 hours. Reduce project time by 60-80%. Turn $2-3M of manual work into automated intelligence that accelerates your SAP transformation.
      </p>
      <div class="flex flex-col gap-2">
        <a href="#" class="group inline-flex items-center text-black font-medium hover:opacity-70 transition-opacity">
          Start your pilot 
          <span class="ml-1 group-hover:translate-x-1 transition-transform">→</span>
        </a>
        <a href="#" class="text-sm text-gray-400 hover:text-black transition-colors">See customer results</a>
      </div>
    </div>
    <div class="bg-white border border-gray-200 rounded-3xl p-8 flex items-center justify-center min-h-[400px] shadow-sm">
      <!-- Migration Timeline Visualization -->
      <div class="w-full space-y-6">
        <div class="text-sm font-semibold text-gray-900 mb-8">Migration Timeline</div>
        
        <!-- Traditional Approach -->
        <div class="space-y-2">
          <div class="flex items-center justify-between text-xs">
            <span class="text-gray-600">Traditional Manual Analysis</span>
            <span class="text-gray-400">18 months</span>
          </div>
          <div class="w-full h-3 bg-gray-200 rounded-full overflow-hidden">
            <div class="h-full bg-gray-400 rounded-full" style="width: 100%"></div>
          </div>
        </div>
        
        <!-- With Conduct -->
        <div class="space-y-2">
          <div class="flex items-center justify-between text-xs">
            <span class="text-gray-900 font-medium">With Conduct</span>
            <span class="text-primary-600 font-semibold">4 months</span>
          </div>
          <div class="w-full h-3 bg-gray-100 rounded-full overflow-hidden">
            <div class="h-full bg-primary-500 rounded-full" style="width: 22%"></div>
          </div>
        </div>
        
        <!-- Stats -->
        <div class="grid grid-cols-3 gap-4 pt-6 border-t border-gray-100">
          <div>
            <div class="text-2xl font-bold text-primary-600">60-80%</div>
            <div class="text-xs text-gray-600 mt-1">Time Saved</div>
          </div>
          <div>
            <div class="text-2xl font-bold text-primary-600">$2-3M</div>
            <div class="text-xs text-gray-600 mt-1">Cost Avoided</div>
          </div>
          <div>
            <div class="text-2xl font-bold text-primary-600">48hrs</div>
            <div class="text-xs text-gray-600 mt-1">To Deploy</div>
          </div>
        </div>
      </div>
    </div>
  </section>
</div>
