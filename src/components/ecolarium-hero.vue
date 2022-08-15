<template>
  <div class="hero">
    <img src="../assets/image/back.png" alt="" />
    <div class="write">
      <div class="our-investment">
        <p style="font-size: bold">Our İnvestment</p>
      </div>
      <div class="ecolarium-investment">
        <p>
          Ecolarium <br />
          Investment
        </p>
      </div>
      <div class="amet-minim-write">
        <p>
          Amet minim mollit non deserunt ullamco est sit aliqua dolor<br />do
          amet sint. Velit officia consequat duis enim velit mollit.
        </p>
      </div>
      <div class="rectangle2"></div>

      <div class="mouse-scroll">
        <div class="mouse-icon">
          <i class="eci mouse-alt"></i>
        </div>
        <div class="scroll">
          <p>Scroll down</p>
        </div>
      </div>
</div>

    <div class="completed-ongoing-investment">
      <div class="completed-button">
        <div class="completed-investment">
          <p>Completed Investment</p>
        </div>
      </div>
      <div class="ongoing-button">
        <div class="Ongoing-investment">
          <p>Ongoing Investment</p>
        </div>
      </div>
      
    </div>
    <div class="card">
      <EcolariumInvestmentCard  v-for="(item, index) in cardsarray" :key="index" :data="item"></EcolariumInvestmentCard>
    </div>
  
  </div>
</template>

<script setup>
import EcolariumInvestmentCard from "./ecolarium-investment-card.vue";
const cardsarray=[{
  'image':'solar-panel-1.png',
  'button': 'Renewable Energy',
  'title':'Solar Panel Maintance',
  'subtitle': 'Aliqua id fugiat nostrud irure ex duis ea quis id quis ad et. Sunt qui esse pariatur duis deserunt mollit dolore cillum minim. '
  
 },
 {
   'image':'solar-panel-2.png',
   'button': 'Industrial Area',
  'title':'Solar panel station',
  'subtitle': 'Aliqua id fugiat nostrud irure ex duis ea quis id quis ad et. Sunt qui esse pariatur duis deserunt mollit'
  

 },
 {
   'image':'solar-panel-3.png',
   'button': 'Renewable Energy',
  'title':'Solar panel Maintance',
  'subtitle':'Aliqua id fugiat nostrud irure ex duis ea quis id quis ad et. Sunt qui esse pariatur duis deserunt cillum minim'
 

 },
 {
  'image':'solar-panel-4.png',
  'button': 'Renewable Energy',
  'title':'Solar Panel Maintance',
  'subtitle': 'Aliqua id fugiat nostrud irure ex duis ea quis id quis ad et. Sunt qui esse pariatur duis deserunt mollit dolore cillum minim. '
 },
 {
   'image':'solar-panel-5.png',
   'button': 'Industrial Area',
  'title':'Solar panel station',
  'subtitle': 'Aliqua id fugiat nostrud irure ex duis ea quis id quis ad et. Sunt qui esse pariatur duis deserunt mollit'
  

 },
 {
   'image':'solar-panel-6.png',
   'button': 'Renewable Energy',
  'title':'Solar panel Maintance',
  'subtitle':'Aliqua id fugiat nostrud irure ex duis ea quis id quis ad et. Sunt qui esse pariatur duis deserunt cillum minim'
  

 },
 {
  'image':'solar-panel-7.png',
   'button': 'Renewable Energy',
  'title':'Solar Panel Maintance',
  'subtitle': 'Aliqua id fugiat nostrud irure ex duis ea quis id quis ad et. Sunt qui esse pariatur duis deserunt mollit dolore cillum minim. '
  
 },
 {
   'image':'solar-panel-8.png',
   'button': 'Industrial Area',
  'title':'Solar panel station',
  'subtitle': 'Aliqua id fugiat nostrud irure ex duis ea quis id quis ad et. Sunt qui esse pariatur duis deserunt mollit'
 

 },
 {
  'image':'solar-panel-9.png',
  'button': 'Renewable Energy',
  'title':'Solar panel Maintance',
  'subtitle':'Aliqua id fugiat nostrud irure ex duis ea quis id quis ad et. Sunt qui esse pariatur duis deserunt cillum minim'

 }
 
 ]
</script>

<style>
.hero > img {
  width: 100%;
  height: auto;
}
.write {
  position: absolute;
  top: 274px;
  left: 156px;
  color: white;
}
.our-investment {
  font-style: normal;
  font-weight: 700;
  font-size: 16px;
  line-height: 20px;
}

.ecolarium-investment {
  font-style: normal;
  font-weight: 700;
  font-size: 64px;
  line-height: 110%;
  width: 452px;
  height: 140px;
}
.amet-minim-write {
  opacity: 0.72;
}
.rectangle2 {
  position: absolute;
  display: flex;
  height: 80px;
  width: 2px;
  background-color: rgb(255, 255, 255);
  margin-top: 40px;
  margin-left: 7px;
}
.mouse-scroll {
  display: flex;
  margin-top: 141.25px;
}

.mouse-icon {
  width: 9px;
  height: 13.5px;
  padding-right: 17px;
}
.scroll {
  font-size: 14px;
  font-weight: 400;
  letter-spacing: 0em;
  text-align: left;
  margin-top: 1.5px;
}

.completed-ongoing-investment {
  display: flex;
  position: absolute;
  background: #f1f2f6;
  height: 56px;
  width: 359px;
  margin-left: 541px;
  margin-top: 124px;
  border-radius: 6px;
  font-size: 14px;
  font-weight: 700;
  line-height: 32px;
  letter-spacing: 0em;
}
.completed-button {
  height: 52px;
  width: 177.5px;
  left: 543px;
  top: 126px;
  border-radius: 6px;
  margin: 2px;
  background: #ffffff;
}
.ongoing-button {
  height: 52px;
  width: 177.5px;
  left: 721px;
  top: 126px;
  border-radius: 6px;
  background: #f1f2f6;
  margin: 2px;
}
.completed-investment {
  padding-top: 10px;
  padding-left: 19px;
  color: #1732f5;
}
.Ongoing-investment {
  padding-top: 10px;
  padding-left: 26px;
  color: #9c9faf;
}
.card{
  margin-left: 148px;
  margin-top: 202px;
  
}


</style>
