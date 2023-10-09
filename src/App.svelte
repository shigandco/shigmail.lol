<script lang="ts">
  import shiggy from "./assets/shiggy.png"
</script>

<main>
  <div class="container" >
    <div class="navbar">
      <ul>
        <a href="https://discord.gg/7Zjb3gkxQf"><li>Discord</li></a>
      </ul>
    </div>
  <img src="{shiggy}" alt="shiggy logo" style="display: inline-block; vertical-align: middle; max-width: 10em">
  <h1 style="display: inline-block; vertical-align: middle;">shigmail</h1>
  <h2>cutest mail service</h2>
  <div class="card">

  
</div>
  <p>
    
  </p>
</div>
</main>

<style>
  .navbar{
    display: flex;
    align-items: center;
    border-bottom: 1px solid white;
    height: 80%;
    margin-bottom: 15px;
  }
  .navbar ul {
    list-style: none;
display: flex;
  }
  .navbar ul a{
    text-decoration: none;
  }
 .navbar ul a li{
  margin: 0 15px;
    text-decoration: none;
    color: white;

 }  
  .container{
    width: 85%;
    margin: auto;
  }
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
    display: inline-block;
    vertical-align: middle;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  }
</style>
