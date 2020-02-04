<template>
  <div class="body">

      <div class="detailsBackground">
        <div class="details">
           <h3>Address</h3>
           <p>Kralja Tvrtka 3/21, <br/>Novi Travnik 72290, Bosnia & Herzegovina</p>
            <h3>Let's talk</h3>
           <p>+387611122333</p>
            <h3>General Support</h3>
           <p>contactus@hotmail.com</p>

        </div>
      </div>

      <div class="contact">
        <h3>Contact us</h3>
  <form action="">
    <input type="text" placeholder="name">
    <input type="text" placeholder="email">
    <input type="text" id='msg' placeholder="message">

   
    <button type="submit" >Submit</button>
  </form>
      </div>

  </div>
</template>
<script>
export default {
  data() {
    return {
      
    };
  }
};
</script>
<style scoped>
.body{
  margin: 5% 20%;
  background-color: rgb(33, 116, 46);
  width:60%;
  height: 700px;
  position: relative;
}
img{
  width: 100%;
  opacity: 30%;
}
.detailsBackground{
  display: inline-block;
  width: 50%;
  height: 100%;
  background-color:rgba(0, 0,0, 0.7);
  margin: 0;
  background-image: url('../Assets/background.jpg');
  background-size: auto 100%;
  background-repeat: no-repeat;
  background-position: left top; 
  position: relative;
}
.details{
 width: 100%;
 height: 100%;
 background-color:rgba(0, 0,0, 0.6);
 margin-top: 0%;
 position: absolute;
}
.details h3{
  color:rgb(45, 170, 82);
  font-size: 2.2vw;
}
.details p{
  color:beige;
  font-size:1.5vw;
}
.contact{
  position: relative;
 width: 50%;
 height: 100%;
 float:right;
 background-color: rgb(236, 236, 236);
 margin-left: 0%;
 color: black;
 text-align: center;
}
.contact form{
  margin:0% 10%;

}
.contact h3{
  font-size: 2.2vw;
  margin-left:20%;
  
}
h3{
  margin-top:15%;
  margin-left: 5%;
  font-family: serif;
  font-style: oblique;
  width: 60%;
}

p{
  margin-top: 5%;
  margin-left: 15%;
}
input{
  width: 100%;
  height: 40px;
  text-align: center;
  border-radius: 10px;
  margin-top: 10%;
}
#msg{
  height: 150px;
}
button{
  background-color: rgb(33, 116, 46);
  border: none;
  width: 70%;
  height: 60px;
  margin-top:15%;
  color: rgb(236, 236, 235);
  font-size: 1.8vw;
  border-radius: 15px;
}

</style>