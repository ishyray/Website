<script>
  let isNavbarOpen = $state(false)
</script>
<nav class="flex flex-row items-center justify-between p-3 pl-10 pr-10">
  <h1 class="text-2xl">
    <a href="/">Ishayu Ray</a>
  </h1>
  <div class="flex items-center gap-3 max-md:hidden">
    <a href="#about"> About Me </a>
    <a href="#contact"> Contact Me </a>
  </div>
  <button class="text-3xl min-md:hidden" onclick={() => isNavbarOpen = !isNavbarOpen}> ≡ </button>
</nav>
<hr/>
<div class={(isNavbarOpen)? "flex flex-col justify-center items-center text-center gap-3 p-3" : "hidden"}>
  <a href="#about"> About Me </a>
  <a href="#contact"> Contact Me </a>
</div>
<hr class="p-2"/>
<article class="pl-10 pr-10">
  <h1 class="text-4xl text-yellow-300" id="about"> Hi 👋 I'm Ishayu Ray! </h1>
  <p> I'm a high school student interested in programing and robots</p>
  <p> I also enjoy reading. </p>
  <p id="contact"> You can contact me at <a href="mailto:theishayuray@gmail.com" class="text-blue-400 underline">theishayuray@gmail.com</a></p>
</article>