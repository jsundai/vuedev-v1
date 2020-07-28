<template >

    

<section>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<div id="home">
<nav id="logo">
  <h2> 
<ul >
  <img src="@/assets/logo.png" /> 
   <li><a href="#contact"> Contact </a></li>
  <li><a href="#about"> About </a></li>
</ul>
</h2>
</nav>



<header id="header" >
  <h1 >
    <br>
		Jwahir Sundai
  </h1>
	
  
  <p  style="font-size:2vw;">
	I'm a <strong style="text-shadow: 1.5px 1px 0px pink;">full stack software engineer</strong> from Cambridge, MA. I hold a degree in Mathematics with Latin Honors from Bryn Mawr College. Skilled in the presentation, logic, and data layer of software.
  </p>
	<br>


	<h2 class="socials"> 
    
	<a href="https://github.com/jsundai" > <img src="https://image.flaticon.com/icons/svg/1051/1051326.svg" alt="Github" width=75px> </a>  <a href="https://medium.com/@jsundai" > <img src="https://image.flaticon.com/icons/svg/2111/2111539.svg" alt="Medium" width=75px></a>  
  </h2>



</header>


</div>
</section>

</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
