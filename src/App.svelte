<script>
  let clicks = 0;
  const handleClick = () => (clicks += 1);
</script>

<div
  class="container mx-auto flex flex-col md:flex-row items-center my-12 md:my-24">
  <!--Left Col-->
  <div
    class="flex flex-col w-full lg:w-1/2 justify-center items-start pt-12 pb-24
    px-6">
    <p class="uppercase tracking-loose">Em construção...</p>
    <h1 class="font-bold text-3xl my-4">Minha biblioteca virtual</h1>
    <p class="leading-normal mb-4">
      Minha biblioteca virtual para exposição e leitura de livros de
      devenvolvimento web e programação em geral no formato PDF, desenvolvido em
      Svelte 3.
    </p>
    <p class="font-bold">Links das Bibliotecas, componentes e servidor utilizados:</p>
    <ul class="mb-5">
      <li>
        <a href="https://svelte.dev/">Svelte 3</a>
      </li>
      <li>
        <a href="https://tailwindcss.com/">Tailwind CSS</a>
      </li>
      <li>
        <a href="https://www.pdftron.com/webviewer/">PDFTron webviwer</a>
      </li>
      <li>
        <a href="https://www.npmjs.com/package/page">Pages.js</a>
      </li>
      <li>
        <a href="https://vercel.com/home">Vercel</a>
      </li>
    </ul>
    <button
      class="bg-transparent hover:bg-gray-900 text-gray-900 hover:text-white
      rounded shadow hover:shadow-lg py-2 px-4 border border-gray-900
      hover:border-transparent"
      on:click={handleClick}>
      Clicado {clicks} {clicks === 1 ? 'time' : 'times'}
    </button>
  </div>
  <!--Right Col-->
  <div class="w-full lg:w-1/2 lg:py-6 text-center">
    <!--Add your product image here-->
    <svg
      class="fill-current text-gray-900 w-3/5 mx-auto"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 20 20">
      <path
        d="M17 6V5h-2V2H3v14h5v4h3.25H11a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6zm-5.75
        14H3a2 2 0 0 1-2-2V2c0-1.1.9-2 2-2h12a2 2 0 0 1 2 2v4a2 2 0 0 1 2 2v10a2
        2 0 0 1-2 2h-5.75zM11 8v8h6V8h-6zm3 11a1 1 0 1 0 0-2 1 1 0 0 0 0 2z" />
    </svg>
  </div>

</div>

<!--Container-->
<div class="bg-white h-screen">
  <div class="container mx-auto pt-24 md:pt-16 px-6">
    <p class="py-4">
      <i class="em em-wave" />
      <i class="em em-world_map" />
    </p>
  </div>
</div>
