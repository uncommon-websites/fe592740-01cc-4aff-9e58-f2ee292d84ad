
<script>
  const companiesLeft = [
    "Lenny Rachitsky", "Gary Brecka", "Roelof Botha", "Brian Halligan", "Arnold Schwarzenegger", "Mark Hyman",
    "Vanessa Van Edwards", "Michael Ovitz", "Jay Shetty", "Jeff Bussgang", "Heather Monahan", "Mona Sharma",
    "Coaches", "Consultants", "Authors", "Speakers", "Investors", "Content Creators", "Writers", "Business Owners",
    "Celebrities", "Experts", "Podcasters", "Newsletter Creators", "Fitness Icons", "Wellness Personalities",
    "Functional Medicine Physicians", "Behavioral Scientists", "Executive Coaches", "Harvard Professors"
  ];

  const companiesRight = [
    "Venture Capitalists", "Startup Founders", "Product Leaders", "Marketing Experts", "Health Influencers",
    "Biohackers", "Motivational Speakers", "Life Coaches", "Career Coaches", "Relationship Experts",
    "Financial Advisors", "Real Estate Experts", "Legal Experts", "Nutritionists", "Personal Trainers",
    "Mindfulness Teachers", "Leadership Coaches", "Sales Trainers", "Educators", "Online Course Creators",
    "Community Builders", "Brand Strategists", "YouTube Creators", "LinkedIn Thought Leaders", "Substack Writers",
    "Legacy Builders", "Estate Planners", "Archivists", "Museum Curators", "Memory Keepers"
  ];
</script>

<section class="py-20 px-6 md:px-12 border-t border-gray-300 bg-gray-950 text-white">
  <div class="flex flex-col md:flex-row gap-10">
    <div class="w-full md:w-1/4 pr-8">
      <h2 class="text-xl font-bold mb-8">Adoption</h2>
      <p class="text-2xl md:text-3xl font-medium leading-tight max-w-xs text-white/95">
        Delphi is becoming the interface for trusted expertise across the creator economy and beyond.
      </p>
    </div>

    <div class="w-full md:w-3/4">
      <div class="mb-12">
        <div class="flex flex-wrap gap-x-4 gap-y-2 text-xl font-bold mb-4">
          <span class="text-white">Experts</span>
          <span class="text-white/40">Creators</span>
          <span class="text-white/40">Legacy</span>
        </div>
        <div class="text-white/60 text-lg leading-relaxed max-w-2xl">
          Delphi powers conversational access to trusted voices across business, media, education, health, culture, and personal legacy.
        </div>
      </div>

      <div class="grid grid-cols-2 gap-x-8 text-lg font-medium leading-tight">
        <div class="space-y-1">
          {#each companiesLeft as company}
            <div class="hover:text-[var(--color-primary-300)] cursor-pointer transition-colors text-white/85">{company}</div>
          {/each}
        </div>
        <div class="space-y-1">
          {#each companiesRight as company}
            <div class="hover:text-[var(--color-primary-300)] cursor-pointer transition-colors text-white/85">{company}</div>
          {/each}
        </div>
      </div>
    </div>
  </div>
</section>
