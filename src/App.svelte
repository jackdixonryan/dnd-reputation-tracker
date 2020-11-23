<script>
	let infoModalDeployed = false;
	function deployInfoModal() {
		infoModalDeployed = true;
	};
</script>

<style>
	.tooltip-button {
		margin-left: 1rem;
		margin-bottom: 0.5rem;
	}
</style>

<main>
	<h1>
		Auroran Guild Tracker
		<span>
			<button on:click={deployInfoModal}
				class="button tooltip-button">
				?
			</button>

			<div class="modal">
				<h2 class="modal-header">
					Tracking Guilds	
				</h2>
				<p class="modal-body">
					You're a DM. It's hard to figure out where everyone stands with the various factions in this bustling city. How is anyone expected to keep track of all the changes and dirty doings in the city of Auroran? Well, have no fear! This application will help you figure out exactly where your characters stand! 
				</p>
			</div>
		</span>
	</h1>
</main>
