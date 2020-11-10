<template>
  <div class="hello">
      <div class="top-content">
        <div class="container title">
          <h1 class="header display-4 text-center">Today's Fashion</h1>
          <h3 class="header text-center">MAde With React.js</h3>
        </div>
        <center>
          <button class="info btn btn-primary">More Info</button>
        </center>
      </div>
      <div class="jumbotron text-center">
        <h4>Making Reviews Our Priority</h4>
      </div>
      <div class="middle-content text-center">
        <div class="container">
          <h1 class="header display-4">Clothes for Now</h1>
        </div>
        <p>Making outstounding Lines for all backgrounds</p>
        <center>
          <button class="btn btn-primary">More Info</button>
        </center>
      </div>
      <div class="jumbotron text-center">
        <h4>Seasonal Lines Coming Soon</h4>
      </div>
      <div class="center-content text-center">
        <div class="container">
          <h1 class="display-4 header">New Trends</h1>
        </div>
        <p>Making outstounding Lines for all backgrounds</p>
        <center>
          <button class="btn btn-primary">More Info</button>
        </center>
      </div>
      <div class="jumbotron text-center">
        <h4>Now Hiring for Models</h4>
      </div>
      <div class="bottom-content text-center">
        <div class="container">
          <h1 class="display-4 header">Have What it Takes?</h1>
        </div>
        <p>Models needed for the upcoming lines, contact us for more info</p>
        <center>
          <button class="btn btn-primary">More Info</button>
        </center>
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
.App {
  text-align: center;
}

.App-logo {
  height: 40vmin;
  pointer-events: none;
}

@media (prefers-reduced-motion: no-preference) {
  .App-logo {
    animation: App-logo-spin infinite 20s linear;
  }
}

.top-content { 
  background: url(https://images.unsplash.com/photo-1469334031218-e382a71b716b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80) no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: 80vh;
  width: 100%;
}

.jumbotron {
  background-color: black!important;
}

.jumbotron h4 {
  color: white!important;
}

.middle-content { 
  background: url(https://images.unsplash.com/photo-1537832816519-689ad163238b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1040&q=80) no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: 80vh;
  width: 100%;
  padding-top: 10%;
}

.middle-content p {
  font-size: 20px;
  color: teal;
}

.center-content { 
  background: url(https://images.unsplash.com/photo-1543087903-1ac2ec7aa8c5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1074&q=80) no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: 80vh;
  width: 100%;
  padding-top: 13%;
}

.center-content p {
  font-size: 20px;
  color: teal;
}

.middle-content p {
  font-size: 20px;
  color: teal;
}

.contact-content { 
  /* background: url(https://images.unsplash.com/photo-1506152983158-b4a74a01c721?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1052&q=80) no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover; */
  height: 80vh;
  width: 100%;
  padding-top: 5%;
}

.bottom-content { 
  background: url(https://images.unsplash.com/photo-1471341971476-ae15ff5dd4ea?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1189&q=80) no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: 80vh;
  width: 100%;
  padding-top: 10%;
}

.bottom-content p {
  font-size: 20px;
  color:teal;
}

.title {
  padding-top: 15%;
  padding-bottom: 3%;
}
/* sliding title */
.header {
  animation-duration: 2s;
  animation-name: slidein;
  color:teal;
}

@keyframes slidein {
  from {
    margin-left: 100%;
    width: 300%; 
  }

  to {
    margin-left: 0%;
    width: 100%;
  }
}

/* sliding button */
.info {
  animation-duration: 3s;
  animation-name: slideinfo;
  max-width: 130px;
}

@keyframes slideinfo {
  from {
    margin-left: 100%;
    width: 300%; 
  }

  to {
    margin-left: 0%;
    width: 100%;
  }
}

/*.App-header {
  
}*/

.App-link {
  color: #61dafb;
}

@keyframes App-logo-spin {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

.download a {
  color:grey!important;
  margin-top:190px;
  font-size: 2em;
  text-decoration:none;
}

.download a:hover {
  color:#cea135!important;
  transition-delay: 0.2s;
  text-decoration:none;
}

footer {
  margin-top: 40px;
  padding-top: 40px;
  padding-bottom: 70px;
  background-color: black;
}

.col-md-4 {
  margin-top:20px!important;
}

.footer {
  color:white!important;
}

.footer h1 {
  color:white!important;
}

.footer a {
  color:white!important;
}

footer address {
  color:white!important;
}

.footer h5 {
  color:white!important;
}
</style>
