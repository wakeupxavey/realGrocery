<script>

	import Toggle from "$componenets/interactives/Toggle.svelte";

</script>
<section>
	<h2>The Context</h2>

	<p>We wanted to explore what grocery prices were like, right here in our own East Bay backyard. Right now, everything feels more expensive, and we hope that this project can provide locals with a snapshot of what their prices are doing. </p>
    
    <p>In the U.S. Grocery increased 2.1% in the year of 2024. Egg prices are in the news everyday. Consumer are voicing their fears amidst looming agricultural tariffs. Everywhere people are talking about prices.</p>
   
    <select id="storeDropdown">
		<option value="">Select a store</option>
		<option value="store1">Store 1</option>
		<option value="store2">Store 2</option>
		<option value="store3">Store 3</option>
	  </select>
	
   
    <p>So how are your prices doing?</p>
</section>

<style>


	section {
		background: #FFEAEA;
		max-width: 600px;
		margin: 20px auto;
		padding: 10px;
		border-radius: 10px;
      
	}

    h2, p{
        text-align: center;
    }

	h2{
		font-family: "Faster One";
	}

	p{
		font-family: "Quantico";
	}

</style>