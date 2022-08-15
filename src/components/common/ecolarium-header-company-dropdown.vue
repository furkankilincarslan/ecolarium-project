<template>
    <div class="dropdown-content-investor">
        <div class="investor-conteiner">
          <div class="our-for-conteiner">
            <div class="Our-Investment-conteiner">
    <div class="Our-story-conteiner">
      <div class="Our-story-icon">
        <i class="eci home-check"></i>
      <h2>Our Story</h2> 
      </div>
      
      <p>Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia.</p>
      </div>
      <div class="Milestone-Investment">
        <div class="Milestone-icon">
          <i class="eci check-circle-alt"></i>
        <h2>Milestone</h2>
        </div>
        
        <p>Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia.</p>
      </div>
      <div class="Our-Ecosystem">
      <div class="Our-Ecosystem-icon">
        <i class="eci building-office"></i>

      <h2>Our Ecosystem</h2>
       </div>
      
      <p>Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia.</p>
      </div>
      </div>
      <div class="for-Investment"> 
    
      
      <div class="team">
        <div class="team-icon">
          <i class="eci boat"></i>
    
        <h2>Team</h2>
        </div>
        
        <p>Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia.</p>
      </div>
      <div class="Our-Core-Values-investment">
        <div class="Our-Core-Values-icon"><i class="eci recycled-energy"></i>
    
        <h2>Our Core Values</h2>
        </div>
        
        <p>Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia.</p>
      </div>
      </div>
      </div>
        <div class="growth-with-us">  
          <h1>Growth with us</h1> 
          <p>  Aliqua id fugiat nostrud irure ex duis ea quis id quis ad et. Sunt qui esse pariatur duis deserunt mollit dolore cillum minim tempor enim.   </p>
          <button class="invest-to-ecolarium">Invest to Ecolarium</button>
    
        </div>
        
      </div>
      </div>  
       
</template>

<script setup>


</script>

<style>
  .dropdown-content-investor {
  display:none;
  position:fixed;
  background-color: #ffffff;
  color: #080E38;
  margin-top: 53px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  width: 100%;
  z-index: 1;
  left: 0px;
  right: 0;
  justify-content: space-between;
  font-weight: 600;
font-size: 14px;
line-height: 20px;
  
}
.investor-conteiner{
  display: flex;
}
.our-for-conteiner{
  display: flex;
  width: 64%;
  background-color: white;
  padding-left: 156px;
  padding-top: 40px;
  padding-bottom: 56px;
  padding-right: 70px;
  
  
}
.our-for-conteiner  h1{
  color: #1732F5;
}
.our-for-conteiner p{
  padding-top: 8px;padding-left: 25px;
  width:239px;
  color:#6B6E88;
  font-weight: 400;
font-size: 12px;
line-height: 16px
}
.Our-story-conteiner{
  padding-right: 116px;
}
.growth-with-us{
  width: 36%;
  background-color: #F1F2F6;
  padding-left: 56px;
  padding-top: 40px;
}


.Our-story-icon{
  display: flex;
  gap: 5px;
}
.Milestone-icon{
  display: flex;
  padding-top: 24px;
  gap: 5px;
}


.completed-investment-conteiner{
  color: black;
}
.Our-Ecosystem-icon{
  display: flex;
   padding-top: 24px;
  gap: 5px;
}
.team-icon{
  display: flex; 
  gap: 5px;
}
.Our-Core-Values-icon{
  display: flex;
   padding-top: 24px;
  gap: 5px;
}
.growth-with-us p{
  padding-top: 8px;
  width: 307px;
  padding-bottom: 16px;
  font-weight: 400;
font-size: 12px;
line-height: 16px
}

.growth-with-us button{
  background: #4ED8F6;
  border: #4ED8F7;
  padding: 10px 16px;
  border-radius: 6px;
  font-weight: 600;
font-size: 16px;
line-height: 20px;


}
</style>