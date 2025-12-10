<script>
  let activeTab = 'Dependencies';
  const tabs = ['Dependencies', 'Custom Code', 'Transports', 'Modifications', 'Enhancements', 'User Exits', 'BAdIs', 'Tables', 'Programs'];
</script>

<section class="pt-32 pb-20 px-6 max-w-7xl mx-auto">
  <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 mb-16">
    <div>
      <h1 class="text-5xl md:text-6xl font-medium tracking-tight text-black leading-[1.1] mb-8">
        Transform SAP <br /> customizations into strategic intelligence
      </h1>
    </div>
    <div class="flex flex-col justify-end items-start lg:pl-12">
      <p class="text-xl text-gray-600 mb-6 max-w-md leading-relaxed">
        AI-powered code analysis and dependency mapping that turns undocumented SAP customizations into migration clarity.
      </p>
      <a href="#" class="group inline-flex items-center text-black font-medium hover:opacity-70 transition-opacity">
        See how it works 
        <span class="ml-1 group-hover:translate-x-1 transition-transform">→</span>
      </a>
    </div>
  </div>

  <!-- Interactive Visual Section -->
  <div class="rounded-3xl overflow-hidden bg-gray-50 border border-gray-200 shadow-sm">
    <!-- Tabs -->
    <div class="flex overflow-x-auto scrollbar-hide border-b border-gray-200 bg-white/50 backdrop-blur-sm">
      {#each tabs as tab}
        <button 
          class="px-5 py-4 text-sm font-medium whitespace-nowrap transition-colors relative {activeTab === tab ? 'text-black' : 'text-gray-500 hover:text-gray-800'}"
          on:click={() => activeTab = tab}
        >
          {tab}
          {#if activeTab === tab}
            <div class="absolute bottom-0 left-0 right-0 h-0.5 bg-black"></div>
          {/if}
        </button>
      {/each}
    </div>

    <!-- Content Area -->
    <div class="relative h-[500px] bg-gray-900 overflow-hidden group">
      <!-- Background Image -->
      <img 
        src="/generated/image-professional-sap-consultant-analyzing-co-1765401560204-0.webp" 
        alt="SAP system analysis" 
        class="absolute inset-0 w-full h-full object-cover opacity-40 transition-transform duration-700 group-hover:scale-105"
      />
      
      <!-- Floating UI Card - Dependency Analysis -->
      <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-96 bg-white/95 backdrop-blur-md border border-gray-200 rounded-2xl p-5 shadow-2xl">
        <div class="flex justify-between items-center mb-5">
          <span class="text-sm font-semibold text-gray-900">Dependency Analysis</span>
          <span class="text-xs text-gray-500">Live Analysis</span>
        </div>
        
        <!-- Analysis Item 1 -->
        <div class="flex items-start gap-3 mb-4 pb-4 border-b border-gray-100">
          <div class="w-10 h-10 rounded-lg bg-primary-500 flex items-center justify-center text-white shrink-0">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="3"/><path d="M12 1v6m0 6v6M5.6 5.6l4.2 4.2m4.2 4.2l4.2 4.2M1 12h6m6 0h6M5.6 18.4l4.2-4.2m4.2-4.2l4.2-4.2"/></svg>
          </div>
          <div class="flex-1 min-w-0">
            <div class="flex justify-between items-baseline mb-1">
              <h3 class="text-sm font-semibold text-gray-900">Z_CUSTOM_PRICING</h3>
              <span class="text-xs font-medium text-primary-600">Critical</span>
            </div>
            <p class="text-xs text-gray-600">247 dependencies mapped</p>
            <div class="flex gap-2 mt-2">
              <span class="px-2 py-0.5 rounded-full bg-gray-100 text-[10px] font-medium text-gray-700">SD Module</span>
              <span class="px-2 py-0.5 rounded-full bg-gray-100 text-[10px] font-medium text-gray-700">User Exit</span>
            </div>
          </div>
        </div>

        <!-- Analysis Item 2 -->
        <div class="flex items-start gap-3">
          <div class="w-10 h-10 rounded-lg bg-green-500 flex items-center justify-center text-white shrink-0">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg>
          </div>
          <div class="flex-1 min-w-0">
            <div class="flex justify-between items-baseline mb-1">
              <h3 class="text-sm font-semibold text-gray-900">BAPI_MATERIAL_GET</h3>
              <span class="text-xs font-medium text-green-600">Safe</span>
            </div>
            <p class="text-xs text-gray-600">Standard API, no conflicts</p>
            <div class="flex gap-2 mt-2">
              <span class="px-2 py-0.5 rounded-full bg-gray-100 text-[10px] font-medium text-gray-700">MM Module</span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Code Block -->
    <div class="bg-gray-50 p-6 border-t border-gray-200 overflow-x-auto">
      <pre class="font-mono text-xs leading-relaxed text-gray-600">
<span class="text-gray-400 select-none">1</span>  <span class="text-gray-400">* Analyze custom code dependencies and impact across SAP landscape</span>
<span class="text-gray-400 select-none">2</span>
<span class="text-gray-400 select-none">3</span>  <span class="text-purple-600">REPORT</span> z_custom_pricing_analysis.
<span class="text-gray-400 select-none">4</span>
<span class="text-gray-400 select-none">5</span>  <span class="text-blue-600">DATA:</span> lt_dependencies <span class="text-purple-600">TYPE TABLE OF</span> conduct_dependency,
<span class="text-gray-400 select-none">6</span>        lv_impact_score  <span class="text-purple-600">TYPE</span> i,
<span class="text-gray-400 select-none">7</span>        lv_risk_level    <span class="text-purple-600">TYPE</span> string.
<span class="text-gray-400 select-none">8</span>
<span class="text-gray-400 select-none">9</span>  <span class="text-gray-400">* AI-powered dependency mapping</span>
<span class="text-gray-400 select-none">10</span> <span class="text-blue-600">CALL FUNCTION</span> <span class="text-green-600">'Z_CONDUCT_ANALYZE'</span>
<span class="text-gray-400 select-none">11</span>   <span class="text-blue-600">EXPORTING</span>
<span class="text-gray-400 select-none">12</span>     iv_object_name = <span class="text-green-600">'Z_CUSTOM_PRICING'</span></pre>
    </div>
  </div>
</section>
