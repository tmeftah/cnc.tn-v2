<script>
	import {scrollPosition} from '../stores';

	$:display= $scrollPosition > 20 ? "block" :"none"
	function topFunction(){
		$scrollPosition=0
	}
</script>


<button on:click={topFunction} id="myBtn" style="display:{display}">
    <img src="images/up-arrow.png" alt="alternative">
</button>
