<template>
  <div class="container">
    <div class="form">
      
<div class="form-header">
  
<p class="form-header__title">
  to do list
</p>
</div>
<div class="form-tasks">
  
    <div class="form-tasks__item">
      <div class="form-tasks__container">
       <img class="form-tasks__img3" src="./img/3.svg" />
      <p class="form-tasks__item--text">Task 1</p>
      </div>      
      <img class="form-tasks__img2"  src="./img/2.svg" />
    </div>

    <div class="form-tasks__item">
      <div class="form-tasks__container">
        <img class="form-tasks__img3" src="./img/3.svg" />
       <p class="form-tasks__item--text">Task 2</p>
       </div>       
       <img class="form-tasks__img2"  src="./img/2.svg" />
    </div>

    <div class="form-tasks__item">
      <div class="form-tasks__container">
      <img class="form-tasks__img3" src="./img/3.svg" />
     <p class="form-tasks__item--text">Task 3</p>
     </div>     
     <img class="form-tasks__img2"  src="./img/2.svg" />
    </div>        
    
     
</div>
<div class="form-add">
  <p class="form-add__text">Add a new task</p>
</div>
<div class="form-footer">
<div class="form-footer__left">
  <p class="form-footer__text">1/3 left</p>
</div>
<div class="form-footer__right">
  <p class="form-footer__content border">All</p>
  <p class="form-footer__content">Active</p>
  <p class="form-footer__content">Completed</p>
</div>
</div>
    </div>
   
   <div class="img">
    <img src="./img/1.svg" />
    </div> 
   
      
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
body {
  background: linear-gradient(104.11deg, #ff7e5f 14.52%, #feb567 87.26%);  
}

.container {
  margin: auto;  
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;  
}

.form {  
  position: relative;  
  width: 540px;
  //width: 50vw;
  max-width: 540px;
  background-color: #FFF4E9;  
  z-index: 1;
  left: 258px;
  bottom: 3px;
  box-shadow: 0px 8px 35px 5px #FE9262; 
}

.img {  
  right: 425px;  
}

.form-header { 
  max-width: 540px;
  height: 50px;
  background-color: #FFCA93;
  display: flex;
  //flex-direction: row;
  justify-content: center;
  align-items: center;  
  z-index: 1;
}

.form-header__title {
  color: #7F4B13;
  font-size: 20px;
  font-weight: 600;
} 

.form-tasks {
  display: flex;
  flex-direction: column;
  margin-right: 30px;
}

.form-tasks__img3 {  
  margin-left: 20px;
  margin-right: 23px;
  height: 24px;
  width: 24px;
}

.form-tasks__img2 {
  height: 24px;
  width: 24px;
  margin-right: 20px;
  margin-left: 23px;
}

.form-tasks__container {
  display: flex;
  justify-content: center;
  align-items: center;
}

.form-tasks__item {
  display: flex;  
  justify-content: space-between;
  align-items: center;
  max-width: 480px;
  //height: 50px;
  background-color: #FFDFBE;
  border-radius: 10px;
  margin-left: 30px;
  margin-top: 30px; 
 
}

.form-tasks__item--text {
  color: #7F4B13;
  font-size: 20px;
  font-weight: 400;
  margin-top: 11px;
  margin-bottom: 11px;
  
}

.form-footer {
 
 display: flex;
 //flex-direction: row;
 justify-content: space-between;
 align-items: center;
 //width: 540px;
 //width: 50vw;
// max-width: 540px;
 //height: 50px;
 background-color: #FFCA93;
 bottom: 50px;
 font-weight: 600;
 font-size: 20px;
 
}

.form-add {
  display: flex;
  border: 1.5px dashed #FFCA93;
  border-spacing: 10px;
  justify-content: center;
  align-items: center;
  max-width: 480px;
 // height: 50px;
  border-radius: 10px;
  margin-top: 25px;
  margin-bottom: 30px;
  margin-right: 30px;
  margin-left: 30px;
  background-color: #FFECD8;
}

.form-add__text {  
  color: #FFCA93;
  font-size: 20px;
  font-weight: 400; 
  margin-top: 11px;
  margin-bottom: 11px;
  margin-right: 20px;
  margin-left: 20px;
   
}

.form-footer__text {
  color: #7F4B136B;
  margin-left: 30px;
  margin-top: 11px;
  margin-bottom: 11px;  
}

.form-footer__right {
 display: flex;
 
 
 align-items: center;
 margin-right: 30px;
}

.form-footer__content {
  color: #7F4B136B;
  margin-left: 25px;
  margin-top: 8px;
  margin-bottom: 8px;
}



.border {
  border: 1px solid #C9955D;
  border-radius: 10px; 
  padding-right: 10px;
  padding-left: 10px;
  padding-top: 3px;
  padding-bottom: 3px;
}



</style>
