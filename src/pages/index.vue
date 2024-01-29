<style>

@import url("https://fonts.googleapis.com/css?family=Montserrat");

:root {
	--blue: #44667a;
  --darkest-blue: #2d3238;
  /* --darkest-blue: #ab4fae; */

	--darker-blue: #3c495c;
	--dark-blue: #283e5d;
	--medium-blue: #44667a;
	--light-blue: #5e7e92;
	--lighter-blue: #91a9b9;
	--lightest-blue: #aec0cc;
	
  --white: #ffffff;
	
  --black: #0e1442;
	
  --orange: #ffb300;
	--yellow: #fdd835;

  --bordo: #683131;
  --red: #b92626;

}

#container{
  max-width: 600px;
  margin: auto;
  font-family: Montserrat, sans-serif;
}

#court{
  border: 2px solid black;
  width: 400px;
  height: 200px;
  margin: auto;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: 1fr;
}

#joystick{
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: 1fr;
  border: 2px solid black;
  width: 400px;
  height: 100px;
  margin: auto;
  position: relative;
  top: 10px;
}


h1{
  text-transform: uppercase;
  text-align: center;
}


</style>

<template>

  <div id="container">
    <h1>Vuerta Tennis</h1>

    <div id="court">
      court
    </div>

    <div id="joytick">
      joystick
    </div>

  </div>
</template>

<script>

  console.log("hello world");

</script>