<template>
<section class="text-gray-400 bg-grey-900 body-font h-screen">
  <div class="absolute w-screen h-screen bg-gray-900"  id="particles-js">
    
  </div>

  <div class="flex h-screen justify-center items-center">
<div class="absolute object-center w-3/5">

 <div class="container h-3/2  flex   py-8  items-center p-0 justify-center flex-col">
    <img class="mb-10   p-0  rounded-full" alt="hero" src="~/assets/faraz.jpg">
	   <NavBar/>
    <div class="text-center lg:w-2/3 w-full">
      <h1 class=" sm:text-4xl text-3xl mb-4 p-1 text-indigo-400 font-extrabold   italic text-gray-400">Faraz Ahmad Khan</h1>
      <p class="mb-8   font-bold font-xl italic leading-relaxed">Hello! I am Faraz Ahmad Khan, a Software Engineer with the passion for developing 
        innovative programs.I love to work on Website, REST APIs and Machine Learning and always enjoy to learn new languages and development techniques.  </p>

    </div>
  </div>


</div>
  </div>



 
</section>
</template>

<script>
export default {

 
}




</script>



<style lang="scss">
// SASS Variables.

$link: #818CF8;
$link-hover: #4B5563;


canvas {
  display: block;
  vertical-align: bottom;
}

#particles-js {
//   position: absolute;
//   width: 100%;
//   height: 100%;

}

.text {
	// position: absolute;
	top: 50%;
	right: 50%;
	transform: translate(50%,-50%);
	// color: $text;
	max-width: 90%;
	// padding: 2em 3em;
	// background: rgba(0, 0, 0, 0.4);
	text-shadow: 0px 0px 2px #131415;
	font-family: 'Open Sans', sans-serif;
}

h1 {
	font-size: 2.25em;
	font-weight: 700;
	letter-spacing: -1px;
}

a,
a:visited {
	color: $link;
	transition: 0.25s;
}

a:hover,
a:focus {
	color: $link-hover;
}
</style>



<style>

.iconify { width: 80px; height: 80px; padding:10px }

</style>
