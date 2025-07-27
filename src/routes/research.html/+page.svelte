<script>
import sydney from '$lib/assets/images/sydney.jpg'


const imgSrc =
  'https://images.unsplash.com/photo-1463171515643-952cee54d42a?q=80&w=450&h=190&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D';

</script>

<div class="flex justify-center">
<a
  href="https://dl.acm.org/doi/10.1145/3701716.3715190"
  class="ml-2 mr-2 mt-2 card preset-filled-surface-100-900 border-[1px] border-primary-500 card-hover divide-primary-500 block max-w-md divide-y overflow-hidden md:mt-5 md:mr-0 md:ml-0"
>
 
  <header>
    <img src={sydney} class="aspect-[21/9] w-full grayscale hue-rotate-90" alt="banner" />
  </header>

  <article class="space-y-4 p-4">
    <div>
      <h2 class="h6">Article</h2>
      <h3 class="h3">Personalised News Summarisation Using Demographic-aware
BART Model</h3>
    </div>
    <p class="opacity-100">
      This research introduces a novel framework for personalised news summarisation
that accounts for reader-specific factors such as age, geography, and
cultural background.
    </p>
  </article>

  <footer class="flex items-center justify-between gap-4 p-4">
    <small class="opacity-60">Presented to The ACM Web Conference Sydney</small>
    <small class="opacity-60">2025</small>
  </footer>
</a>

</div>
<div class="flex justify-center items-center">
  <a type="button" href="https://dl.acm.org/doi/10.1145/3701716.3715190"><button class="btn variant-filled-primary mt-4">read paper</button></a>
</div>