<template>
  <div class="info content-1 container text-center">
      <div class="text-center download">
      Resume 
      <a href="resume.doc" dowlnload="resume.doc">
        <i class="fas fa-download"></i>
      </a> 
    </div>
    <br><br>
    <div class="row">
        <div class="col-md-6">
            <h1>Experience</h1>
            <br>
            <h5>Current</h5>
            <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Qui dolor 
                quas iste quod nihil, minima modi voluptatem, 
                eligendi reiciendis id deleniti placeat illo magni officiis quasi 
                nesciunt alias nulla beatae.
            </p>
            <br>
            <hr>
            <br>
            <h5>Previous</h5>
            <br>
            <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Qui dolor 
                quas iste quod nihil, minima modi voluptatem, 
                eligendi reiciendis id deleniti placeat illo magni officiis quasi 
                nesciunt alias.
            </p>
        </div>
        <div class="col-md-6">
            <h1>Education</h1>
            <br>
            <p>
                <strong>Lorem ipsum</strong><br>
                <em>1999 - 2006</em> <br>
                dolor sit amet consectetur adipisicing elit. Qui dolor 
                quas iste quod nihil, minima modi voluptatem, 
                eligendi reiciendis id deleniti placeat illo magni officiis quasi 
                nesciunt alias.
            </p>
            <br>
            <hr>
            <br>
            <p>
                <strong>Lorem ipsum</strong><br>
                <em>2008 - 2014</em> <br>
                dolor sit amet consectetur adipisicing elit. Qui dolor 
                quas iste quod nihil, minima modi voluptatem, 
                eligendi reiciendis id deleniti placeat illo magni officiis quasi 
                nesciunt alias nulla beatae.
            </p>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Info',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    strong {
        font-weight: bolder!important;
    }
.content-1 {
  background: url(https://i.stack.imgur.com/k4Qm1.png) no-repeat center center; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: auto;
  width: 100%;
  padding-top: 30px;
  padding-bottom:30px;
  color:teal!important;
}
h1{
    color:grey!important;
    text-shadow: 10px 11px 9px;
}
h5, strong {
    color: teal!important;
}
hr {
    background-color:goldenrod!important;
}
.download {
    font-size: 20px!important;
}
</style>
