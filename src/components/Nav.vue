<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#"><span class="title">TP</span> Profile</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavDropdown">
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#Features">Features</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#Pricing">Pricing</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#Contact">Contact</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                Dropdown link
              </a>
              <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                <a class="dropdown-item" href="https://facebook.com">Facebook</a>
                <a class="dropdown-item" href="https://linkedin.com">LinkedIn</a>
                <a class="dropdown-item" href="https://twitter.com">Twitter</a>
              </div>
            </li>
          </ul>
        </div>
      </nav>
</template>

<script>
export default {
  name: 'Nav',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  nav a span{
    color:rgb(224, 31, 224)!important;
    font-weight: 600!important;
  }
</style>
