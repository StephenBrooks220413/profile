<template>
  <div class="hello">
    <div class="profile">
      <h5>Mike Lohansen</h5>
      <p>
        Chicago, IL. / 555-555-5555 <br>
        email@mail.com
      </p>
    </div>
    <br><br><br><br>
      <div class="container">
        <h1>Employee Reviews</h1>
        <br>
        <div class="row text-center">
          <div class="col-md-4">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum soluta 
            quisquam impedit, ut laudantium suscipit eveniet. 
          </div>
          <div class="col-md-4">
            Ipsam pariatur fugiat quidem omnis cum? Asperiores 
            provident quidem. Obcaecati magnam asperiores fugit architecto!
          </div>
          <div class="col-md-4">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum soluta 
            quisquam impedit, ut laudantium suscipit eveniet. 
          </div>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  .hello {
    margin-top:70px;
    margin-left: 10px;
    margin-right: 10px;
  }
  .profile {
    background: url(https://cityoflavon.com/wp-content/uploads/blank-profile.png) no-repeat center center; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: 40vh;
  width: 60%;
  padding-top: 30px;
  padding-bottom:30px;
  color:teal!important;
  margin-left: auto;
  margin-right: auto;
  }
  /* https://cityoflavon.com/wp-content/uploads/blank-profile.png */
</style>
