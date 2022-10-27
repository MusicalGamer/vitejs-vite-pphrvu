<input type="range" bind:value={age} min="-78" max="50" />
<input bind:value={age} placeholder="Your age"/>
<h1>When I was born, I was:</h1>
<h3>{age}</h3>
<h4>{name}</h4>

<button on:click={onClick}>Increase</button>
<button on:click={reduceTheAge}>Reduce</button>

<style>
h4
{
  background:pink;
  color:blue
}
h3
{
  background:blue;
  color: white
}
h2
{
background:aqua;
}
h1
{
  Background:red;
}
p
{
  Background: yellow;
}
</style>
<script>
let name = "Jonah"
let age;
age=14

function onClick() {
age = age + 1
}

function reduceTheAge() {
  age-=1
}
</script>