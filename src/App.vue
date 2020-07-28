<template>
  <div id="app">
    <Home msg="Welcome to Your Vue.js App"/>
    <About msg="This is the About page"/>
    <Skills msg="This is the Skills and Activities page"/>
    <Footer msg="This is the Footer page"/>
    
    
    
    

    
  </div>
</template>

<script>
import Home from './components/Home.vue'
import About from './components/About.vue'
import Skills from './components/Skills.vue'
import Footer from './components/Footer.vue'






export default {
  name: 'App', 
  components: {
    Home,
    About, 
    Skills,
    Footer
    
    
    
    

  }
}
</script>

<style>

<head>
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
</head>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  height: 100%; }

* {
  box-sizing: border-box;
}

body {
	background: #696969;
	background-size: 400% 400%;
  padding: 0;
  margin: 0;
  width: 100%;
  min-height: 100vh;

}

@keyframes gradient {
	0% {
		background-position: 0% 50%;
	}
	50% {
		background-position: 100% 50%;
	}
	100% {
		background-position: 0% 50%;
	}
}


/*navigation*/
nav {
	margin: 0;
	text-transform:uppercase;
	}


ul {
  list-style-type: none;
  margin-top: 50px;
	margin-right: 50px;
  overflow: hidden;

}

li {
  float: right;
}

#logo img {
  width: 75px; height: 75px;
  margin-left: 25px;
}

li a {
	display: flex;
	flex-direction: row;
	justify-content: flex-start;
  margin-left: 50px;
 
}

/*style the  navigation links*/
a {
  color: black;
  text-decoration: none;

}

/* makes the navigation links red on hover*/
a:hover {
  color: #FFA07A;
  text-decoration: none;
  transition: 0.25s;
}




/*header*/



#header  {
  text-align: center;
  padding-bottom: 300px;

}





h1 {
  font-family: 'Raleway', sans-serif;
  color: white;
	font-size: 80px;
  text-transform: uppercase;
  font-weight: 150;

}

h2 {
  margin: 0;
  font-family: 'Quicksand', sans-serif;
  font-size: 20px;
  font-weight: 150;
  word-spacing: 1.5em;
}





/*text*/
h5 {
	font-family:  'Lucida Sans Typewriter', monospace;
	font-size: 20px;
	text-transform: uppercase;

}

p {
	font-size: 30px;
	color: black;
	font-family: 'Quicksand', sans-serif;
  font-weight: 300;
  
}

#header p {
  color: white;
  padding-left: 200px;
  padding-right: 200px;
}



h3 {
  font-family: "Playfair Display", serif;
  color: black;
	font-size: 80px;
}

h4 {
  font-family: 'Quicksand', sans-serif;
  font-size: 35px;
  font-weight: 150;
  color: white;
}


/*select work*/
/*cards*/
#work {
  padding: 100px;
  position: relative;
  background: white;
}


.card-body h3 {
  font-family: 'Quicksand', sans-serif;
  font-weight: lighter;
  color: black;
  font-size: 20px;
  margin-top: 40px;
 
}
.card-body p {
  font-size: 15px;
}



/*grid*/


.grid-wrap {
  box-sizing: border-box;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  margin: 0 auto;
}

.card  {
  display: grid;
  border: 1px solid #e0e0e0;
  border-radius: 5px;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  margin: .2em;
  transition: 0.3s;
  padding: .5em .5em;
  grid-template-rows: 100px 250px;
  font-size: 64px;
  background: white;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.4);
}

.card-head {
  border-radius: 5px;
}

.card-body {
  text-align: center;
  margin-bottom: 2em;

}

.grid-wrap2 {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
	margin: 0 auto;
 
 
}

h6 {
  color: black;
}

#work img {
width: 175px; height: 100px;
display: block;
margin-left: auto;
margin-right: auto;
border: 5px solid whitesmoke;
}





/*buttons*/
.btn {
  border: 2px solid black;
  background-color: white;
  color: black;
  padding: 14px 28px;
  font-size: 16px;
  cursor: pointer;
	justify-content: right;
  float: right;
  margin-top: 50px;
}

.default {
  border-color: darkgray;
  color: black;
}

.default:hover {
  background: #e7e7e7;
}

/*about*/
#about {
  background: #f2f2f2;

}

#about img {
  float: left;
  margin-left: 100px;
  margin-right: 100px;
  margin-bottom: 40px;
  
}



#about div.description {
  display: inline-block;
  overflow-wrap: break-word;
  padding: 100px;

  
}

#about p {
  font-size: 20px;
}

#about div.description h3 {
  margin-top: 0px;
}

.name {
 -webkit-text-decoration: white solid underline;
  text-decoration: white solid underline;
  -webkit-text-decoration-skip: ink;
  text-decoration-skip: ink;
}

#about .pronouns {
  color: black;
  font-size: 15px;
 
}


/*skills*/


#skills {
  padding: 200px;
  background: white;
  
}

section.technologies p {
  column-count: 3;
  column-gap: 40px;
  line-height: 1.6;
  
}

section.activity h5 {
  margin-top: 50px;
}
section.activities p {
  column-count: 1;
  line-height: 1.6;
}

/*footer*/

.footer  {
  background-color: black;
  width: 100%;
  height: 100%;
  padding: 100px;
}

.footer p {
  color: white;
text-align: center;
font-size: 20px;

}

#contact a  {
  color: white;
  text-align: center;
  padding: 20px;
  -webkit-text-decoration: blue solid underline;
  text-decoration: blue solid underline;
  -webkit-text-underline-position: under;
  text-underline-position: under;
}



</style>
