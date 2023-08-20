<script setup>
</script>

<template>
<header>
  <img class="Group3" src="./../../public/Group3.svg" alt="">
  <div class="intro">
    <div class="text">
      <h2 class="hello">Hello</h2>
      <p>I am here again. Any thing you what to know about me YOu will find it here!!</p>
    </div>
    <div class="Box"></div>
  </div>
  <div class="show">
    <div class="box-1"></div>
    <div class="box-2"></div>
    <div class="box-3"></div>
    <div class="box-4"></div>
    <div class="box-5"></div>
    <div class="box-6"></div>
  </div>
</header>
</template>

<style scoped>
header{
  width: 100%;
  height: 3228px;
}
.Group3{
    width: 100%;
    top: -10px;
    position: absolute;
    
}
.intro{
    display: flex;
    flex-direction: row;
    align-items: center;
    flex-wrap: wrap;
    
    justify-content: center;  
}
.hello{
  font-family: 'Butcherman', cursive;
  font-size: 10vw;
  z-index: 100;
  margin: 0;
  padding: 6vw;
  color: aliceblue;
  width: auto;
  transform: rotate(-6.711deg);
  flex-shrink: 0;
  padding-bottom: 0;
}
.Box{
  margin: 10px;
  height: 600px;
  background-color: #587c9c;
  margin-top: 20px;
  min-width: clamp(500px, 50%,800px);
  
}
.text{
  display: flex;
  flex-direction: column;
}
.text p{
  width: auto;
  padding: 4vw;
  max-width: 300px;
  padding-top: 0;
transform: rotate(-1.956deg);
flex-shrink: 0;
color: #03A63C;
font-family: 'Architects Daughter', cursive;
font-size: 2.5vw;
font-style: normal;
font-weight: 400;
margin-top: 0;
line-height: normal;
}
.show{
  display: flex;
  align-items: center;
}
.show div{
  height: 919px;
  width: 16.67%;
  background-color: #03A63C;
  
}
.show div:hover{
  background-color: #587c9c;
  height: 1019px;
  width: calc(16.67% + 100px);
  border-radius: 8px;

}
</style>
