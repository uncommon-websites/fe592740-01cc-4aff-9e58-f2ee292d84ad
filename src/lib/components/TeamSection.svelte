<script>
  const team = [
    {
      name: "Creator Economy",
      role: "Podcasters, newsletter operators, educators",
      details: "Delphi gives high-output creators a Digital Mind that answers audience questions in their own tone and point of view.",
      image: "/generated/image-confident-expert-creator-in-a-modern-wor-1775241771039-1.webp"
    },
    {
      name: "Investors & Operators",
      role: "VCs, executives, business builders",
      details: "Trusted by leaders who want to scale access to their frameworks, decisions, and hard-won pattern recognition.",
      image: "/generated/image-seasoned-investor-in-a-refined-office-se-1775241773637-2.webp"
    },
    {
      name: "Health & Wellness",
      role: "Doctors, coaches, biohackers, experts",
      details: "Perfect for experts with deep libraries of content who need safe, curated answers that remain aligned with their voice.",
      image: "/generated/image-wellness-expert-in-a-bright-minimalist-c-1775241776237-3.webp"
    }
  ];
</script>

<section id="team" class="py-20 px-6 md:px-12 border-t border-gray-300 bg-[color:var(--color-primary-50)]/30">
  <div class="flex flex-col md:flex-row gap-10">
    <div class="w-full md:w-1/4 pr-8 mb-12 md:mb-0">
      <h2 class="text-xl font-bold mb-8">Who it serves</h2>
      <p class="text-2xl md:text-3xl font-medium leading-tight max-w-xs">
        Delphi is built for people whose knowledge compounds faster than their time.
      </p>
      <p class="text-sm text-gray-600 mt-6 max-w-xs">
        From celebrity voices to technical educators and executive coaches, Delphi turns trusted expertise into a living interactive asset.
      </p>
    </div>

    <div class="w-full md:w-3/4">
      <div class="flex space-x-6 mb-8 text-lg border-b border-gray-300 overflow-x-auto">
        <button class="font-bold text-black border-b-2 border-[var(--color-company-accent)] pb-4 px-1 -mb-[1px] whitespace-nowrap">Creators</button>
        <button class="text-gray-400 hover:text-gray-600 transition-colors pb-4 px-1 whitespace-nowrap">Experts</button>
        <button class="text-gray-400 hover:text-gray-600 transition-colors pb-4 px-1 whitespace-nowrap">Legacy</button>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-x-8 gap-y-12">
        {#each team as member}
          <div class="group cursor-pointer">
            <div class="aspect-[4/5] bg-gray-200 mb-4 overflow-hidden border border-gray-200">
              <img src={member.image} alt={member.name} class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-500" />
            </div>
            <h3 class="font-bold text-lg">{member.name}</h3>
            <p class="text-gray-500 text-sm mb-3">{member.role}</p>
            <p class="text-xs leading-relaxed mb-4 min-h-16 text-gray-700">{member.details}</p>
            <div class="flex space-x-3 text-[var(--color-company-accent)] text-xs uppercase tracking-[0.18em]">
              <span>Authentic</span>
              <span>Private</span>
            </div>
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>
