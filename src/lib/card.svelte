<script lang="ts">
   /**
	 * @type {string}
	 */
      let src : string ;
     let customClass;
     let title : string;
    let description : string;

    export {src, customClass, title, description}

    const cardClass = 'card' + ' ' + customClass
</script>

<div class={cardClass}>
   <img {src} alt="car-icon">

   <p class="title-text">{title}</p>
   <p>{description}</p>

   <button class="card-button">Learn More</button>
</div>