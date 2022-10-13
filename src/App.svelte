<h1></h1>
<h3>{age}</h3>

<button on:click={onClick}>Increase</button>
<button on:click={reduceTheAge}>Reduce</button>

<style>
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
let age;
age=14

function onClick() {
age = age + 1
}

function reduceTheAge() {
  age-=1
}
</script>