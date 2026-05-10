<script lang="ts">
  import Seo from "$lib/components/Seo.svelte";
</script>

<Seo
  title="Manuel Loaiza"
  description="Software engineer, researcher, and mathematician."
/>

<p
  class="layout-md text-black text-xl leading-tight font-light mb-16"
  id="eric-is"
>
  <span class="g">is a</span> software engineer<span class="g">,</span><br />
  researcher <span class="g">and</span><br />
  mathematician<span class="g">.</span>
</p>

<div class="layout-md text-lg space-y-14">
  <div class="space-y-5">
    <p>
      Today I spend most of my time working on a stealth fintech
      and techleading as an independent software consultant.
    </p>

    <p>
      Previously, I worked at <a class="link" href="https://www.autodesk.com/">Autodesk</a>,
      <a class="link" href="https://www.haystack.tv/">Haystack News</a> and
      <a class="link" href="https://fromsolvers.com/">Fromsolvers</a>.
    </p>

    <p>
      I recently graduated from <a class="link" href="https://www.pucp.edu.pe/">PUCP</a>,
      where I was a teaching fellow for upper-level informatics classes,
      studied mathematics,
      represented my university in international competitive programming contests,
      and founded <a class="link" href="https://www.instagram.com/pucp.algorithms.club">PUCP Algorithms Club</a>.
    </p>
  </div>

  <div class="space-y-5">
    <!-- <p>This is what I look like:</p> -->
    <img
      alt="Self-portrait photograph of Manuel Loaiza at his desk"
      src="/assets/images/profile5.jpg"
    />
  </div>
</div>

<style lang="postcss">
  .g {
    @apply text-neutral-400;
  }

  em {
    @apply font-serif text-[110%] leading-[100%];
  }

  .project-pair {
    @apply grid sm:grid-cols-[1fr,2fr] gap-y-1 -mx-3 px-3 py-2 hover:bg-neutral-100 transition-colors;
  }

  aside {
    @apply mt-0.5 text-base text-neutral-500;
  }

  /* Correction for vertical navigation links on mobile. */
  @media (max-width: 420px) {
    #eric-is {
      @apply -mt-10;
    }
  }
</style>
