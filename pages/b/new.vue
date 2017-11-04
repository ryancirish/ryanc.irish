<template>
	<div id="entry" class="">

		<aside class="titleCard">
			<h1 class="f-subheadline helvetica white mv0"> misc. </h1>
			<div class="ml3">
				<h2 class="f2 helvetica white">11/4/2017</h2>
				<h3 class="f3 helvetica white"></h3>
			</div>
		</aside>

		<main id="copy" class="f4 center white lh-copy">

			<p>Hello again, long time no see. Added a couple repos to <a href="http://www.github.com/ryancirish">my github</a> that are going to serve as repositories for generic code that been useful in my recent client projects. Also, one of my main items in my research stack this week is distributing this thru zeit or reconfiguring my caddy dist to pull straight from the hub. That should be a better vehicle for continuous integration for a small static distro such as this.</p>

			<p style="margin-bottom:0px;">-rci</p>
		</main>

	</div>
	
</template>

<script></script>

<style>

	#entry {
		min-height: 100vh;
		background-image: url('/sky.jpg');
		background-repeat: repeat-y;
		background-size: 

	}

	#copy {
		filter: grayscale(1);
	}

	.measure-wide {
		max-width: 54rem;
	}

	main {
	
		
	}


@media (max-width: 850px) {
  /* styles */
  main {
  	max-width: 24rem
  }

  #entry {
  
  }
}

@media (min-width: 850px) {
  /* styles */
  main {
  	max-width: 48rem
  }
}





</style>