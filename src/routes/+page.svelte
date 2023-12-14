<script lang="ts">
   import Card from '$lib/card.svelte';
</script>

<style global>
   @import '../styles/app.styles.css';
   @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Roboto&display=swap');
</style>

<svelte:head>
	<title>Svelte Card App</title>
	<meta name="description" content="Svelte card app" />
</svelte:head>

<main class="main-container">
   <div class="flex">
      <Card 
         src='./icon-sedans.svg'
         title='sedans'
         description='Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city or on your next road trip.'
         customClass='' />
      <Card 
         src='./icon-suvs.svg'
         title='suvs'
         description='Take an SUV for its spacious interior, power, and versatility. Perfect for your next family vacation and off-road adventures,'
         customClass='secondary' />
      <Card 
         src='./icon-luxury.svg'
         title='luxury'
         description='Cruise in the best car brands without the bloated prices. Enjoy the enhanced comfort of a luxury rental and arrive in style.'
         customClass='tertiary' />
   </div>
</main>
