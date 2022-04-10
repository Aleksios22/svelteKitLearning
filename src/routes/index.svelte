<script>
  import Nav from '$lib/nav.svelte'
  let title
  const updateTitle = () => {
    title = 'Vite'
  }
</script>

<div>
</div>

<main class="index text-center" >
  <Nav />
  <section>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
      Rerum assumenda quibusdam mollitia doloribus. Ad! Lorem ipsum
      dolor sit amet consectetur adipisicing elit. Quia facere in
       minima voluptatibus itaque voluptatem, at unde ut quis quod
        iste suscipit! Ex, repudiandae enim. Deserunt?
    </p>
    <button class="btn m-5" on:click={updateTitle}>Change title</button>
    <input class="border-2 p-2" type="text" bind:value={title}>
  </section>  

</main>
