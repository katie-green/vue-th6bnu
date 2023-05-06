<template>
<nav class="navbar navbar-expand-sm bg-success navbar-dark">
  <a class="navbar-brand" href="#">Save the Earth</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="collapsibleNavbar">
    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link" href="#">About</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Donations</a>
      </li> 
    </ul>
  </div>  
</nav>
</template>

<script>
export default {
  name: 'Comp1',
  props: {
    msg: String
  }
}
</script>
