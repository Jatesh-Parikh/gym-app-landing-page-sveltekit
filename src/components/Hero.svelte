<script>
  import Header from "./Header.svelte";
  import SectionWrapper from "./SectionWrapper.svelte";
  import Stars from "./Stars.svelte";
  import CTAs from "./CTAs.svelte";
</script>


<SectionWrapper>
    <Header />
    <div class="flex flex-col flex-1 gap-10 items-center justify-center pb-10 md:pb-14">
        <h2 class="text-4xl sm:text-5xl md:text-6xl lg:text-7xl max-w-[1200px] mx-auto w-full text-center font-semibold">
            <span class="text-indigo-400">Gym</span> Training
            <span class="text-slate-600 line-through">Is Hard</span><br />
            Just Got <span class="text-indigo-400">Easier</span>
        </h2>
        <p class="text-xl sm:text-2xl md:text-3xl text-center max-w-[1000px] mx-auto w-full">
            Less thinking & more doing. We're the trainer in your pocket full of <span
                class="italic"
                >personalized workouts, exercise explanations, analytics</span
            > and much much more.
        </p>
        <CTAs />
        <Stars />
    </div>
</SectionWrapper>