<script>
    const openInNewTab = (/** @type {string} */ url) => {
        window.open(url, '_blank', 'noopener,noreferrer')
    }
</script>

<svelte:head>
    <title>Kit+Tailwind+Daisy</title>
</svelte:head>

<div class='w-full'>
    <div class="hero min-h-screen bg-base-200">
      <div class="hero-content text-center">
        <div class="max-w-md">
          <div class="ml-auto mr-auto">
            <h1 class="text-3xl font-bold whitespace-nowrap text-left drop-shadow-2xl">SvelteKit + <span class='text-[#38bdf8] drop-shadow-2xl'>TailwindCSS</span> + <span class='text-[#720aec] drop-shadow-2xl'>DaisyUI</span></h1>
          </div>
          <p class="py-6">Check out their respectative documentation here.</p>
          <div class="grid-cols-3">
            <button class="btn btn-black mx-2" on:click={() => openInNewTab('https://kit.svelte.dev')}>SvelteKit</button>
            <button class="btn bg-[#38bdf8] mx-2 border-transparent" on:click={() => openInNewTab('https://tailwindcss.com')}>TailwindCSS</button>
            <button class="btn bg-[#720aec] mx-2 border-transparent" on:click={() => openInNewTab('https://daisyui.com')}>DaisyUI</button>
          </div>
        </div>
      </div>
      <footer class="footer footer-center p-4 bg-base-300 text-base-content absolute bottom-0">
        <div>
            <p>Made by <a href="https://github.com/gxjakkap" class="underline" target="_blank" rel="noreferrer">GuntxJakka</a>. Released under <a class="underline" target="_blank" href="https://github.com/gxjakkap/kit-tailwind-daisy/blob/main/LICENSE" rel="noreferrer">The Unlicense</a>.</p>
        </div>
      </footer>
    </div>
</div>