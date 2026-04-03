<script>
  const investments = [
    { name: "Authentic voice mirroring", detail: "The Digital Mind speaks in your words, not generic AI copy.", tag: "Voice" },
    { name: "Omnichannel deployment", detail: "Publish across websites, SMS, WhatsApp, Slack, voice, and video.", tag: "Distribution" },
    { name: "Multi-format training", detail: "Train on text, audio, video, and live content feeds.", tag: "Content" },
    { name: "Lead capture", detail: "Turn conversations into intent signals, qualified leads, and product discovery moments.", tag: "Growth" },
    { name: "Continuous learning", detail: "As new content is added, your Digital Mind keeps evolving with you.", tag: "Freshness" },
    { name: "Legacy preservation", detail: "Preserve knowledge, stories, and teaching for the long term.", tag: "Legacy" }
  ];
</script>

<section id="portfolio" class="py-20 px-6 md:px-12 border-t border-gray-300 bg-white">
  <div class="flex flex-col md:flex-row gap-10">
    <div class="w-full md:w-1/4 pr-8 mb-12 md:mb-0">
      <h2 class="text-xl font-bold mb-8">Why Delphi</h2>
      <p class="text-2xl md:text-3xl font-medium leading-tight max-w-xs">
        More than an AI assistant. Delphi is an interactive profile built around ownership, authenticity, and trust.
      </p>
    </div>

    <div class="w-full md:w-3/4">
      <h3 class="text-xl font-bold mb-8">Platform capabilities</h3>

      <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-3 gap-4">
        {#each investments as company}
          <div class="min-h-52 border border-gray-200 bg-gray-50 flex flex-col justify-between p-5 hover:border-[var(--color-company-accent)] hover:bg-[color:var(--color-primary-50)] transition-colors cursor-pointer group">
            <div>
              <span class="inline-flex text-[11px] uppercase tracking-[0.2em] text-[var(--color-company-accent)] mb-6">{company.tag}</span>
              <h4 class="text-xl font-bold text-gray-950 mb-3">{company.name}</h4>
              <p class="text-sm text-gray-600 leading-relaxed">{company.detail}</p>
            </div>
            <span class="text-xs font-medium text-gray-500 mt-8">Built for creators, coaches, authors, speakers, and public figures</span>
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>
