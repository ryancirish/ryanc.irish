<template>
	<div id="entry" class="">

		<aside class="titleCard">
			<h1 class="f-subheadline helvetica white mv0"> hello world </h1>
			<div class="ml3">
				<h2 class="f2 helvetica white">10/9/2017</h2>
				<h3 class="f3 helvetica white"></h3>
			</div>
		</aside>

		<main id="copy" class="f4 center white lh-copy">
			<p> New domain, same name. I have been sitting on this for a while after the new TLD announcements, so its about time I spooled up the latest stack/tools I've been playing with. Last blog install on the old domain was ghost, and while it is completely sufficent, I have grown to fancy more lightweight tooling. This site is built with Nuxt, which is an abstraction of Vue that has the ability to statically generate assets. At the same time, I have complete control of the installed modules and file structure. Not bad. </p>

			<p>Vue, in general has been amazing to work with, and I am blessed to be "coming up" at a time where such tooling exists. I grew up on the front end, first kindling my love for dev back in elementary school making HTML sites, so the JS world was relatively easy to pick up. I will focus a lot of articles on my adventures and growth using Vue, and whatever else I use along the way. At the moment, I am quite fond of Feathers.js as a backend, and I have been using it to tinker with an experiment/potential MVP. Feathers is database and front end agnostic, and has support for many authentication protocols out of the box. Combine this with axios and Vue integrates perfectly as the view layer. 3 EZ.</p>

			<p>I'll be back soon with whatever comes to mind. There will be no specific format at the moment. Torn at the moment in regard to self censorship- will employers even read this? Most likely not. Alas, we shall go where the current takes us.</p>

			<p>-rci</p>
		</main>

	</div>
	
</template>

<script></script>

<style>
	#entry {
		height: 100vh;
		background-image: url('/sky.jpg');
	}

	#copy {
		filter: grayscale(1);
	}

	.measure-wide {
		max-width: 54rem;
	}

	main {
		max-height: 70vh;
		overflow-y: auto;
		
	}


@media (max-width: 850px) {
  /* styles */
  main {
  	max-width: 24rem
  }
}

@media (min-width: 850px) {
  /* styles */
  main {
  	max-width: 48rem
  }
}





</style>