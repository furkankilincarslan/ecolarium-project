<template>
<div class="eco-header">
  <div class="üst-navigation-bar">
    <div class="üst-bar">
      <div class="başlık">ecolarium</div>
      <div class="contact">
        <div class="phone">
          <div class="phone-icon"><i class="eci call"></i></div>
          <div class="phone-number"><p>+1 123 456 789</p></div>
        </div>
        <div class="email">
          <div class="email-icon"><i class="eci mail"></i></div>
          <div class="email-"><p>ecolarium@mail.com</p></div>
        </div>
        <div class="konum">
          <div class="konum-icon"><i class="eci location"></i></div>
          <div><p>Ankara 06000, Turkey</p></div>
        </div>

        <div class="line"></div>
      </div>

      <div class="sosyal-medya">
        <div class="sosyal-medya-icons">
          <i class="eci linkedin-outline"></i>
          <i class="eci instagram-outline"></i>
          <i class="eci facebook-outline"></i>
        </div>
        <div class="line2"></div>
      </div>

      <div class="language">
        <p>EN</p>
        <i class="eci chevron-down"></i>
      </div>

      <div class="toggle-switch">
        <input id="toggle_switch" name="toggle_switch" type="checkbox" />

        <label for="toggle_switch"> </label>
      </div>
    </div>
  </div>
  <div class="alt-navigation-bar">
    <div class="dropdown-menu">
    <div class="dropdown-home">Home
  
  </div>
  <div class="dropdown-Company">
    <div class="company">
      <p>Company</p>
      <i class="eci chevron-down"></i>
    </div>
    
     <div class="dropdown-company-conteiner">
   <EcolariumHeaderCompanyDropdown  ></EcolariumHeaderCompanyDropdown> 
   </div>
  </div>
  <div class="dropdown-Sector">
    <div class="sector">
      <p>Sector</p>
      <i class="eci chevron-down"></i>
    </div>
    <div class="dropdown-sector-conteiner">
<EcolariumHeaderSectorDropdown/>
    </div>
   
    
    
  </div>
  <div class="dropdown-investor">
    <div class="invester">
      <p>Investor</p>
    <i class="eci chevron-down"></i>
    </div>
    <div class="dropdown-investor-conteiner">
    
    <EcolariumHeaderInvestorDropdown />
    </div>
  </div> 
  <div class="dropdown-Document">Document
  
  </div>
  <div class="dropdown-News">News
   
  </div>
  <div class="dropdown-Contact-us">Contact us
  </div>
    

      
    </div>
    
</div>
    <div >
      <button class="connect_button">Connect ecolarium Finance</button>
    </div>
  </div>


</template>

<script setup>
import EcolariumHeaderInvestorDropdown from "./ecolarium-header-investor-dropdown.vue";
import EcolariumHeaderCompanyDropdown from "./ecolarium-header-company-dropdown.vue";
import EcolariumHeaderSectorDropdown from "./ecolarium-header-sector-dropdown.vue";
</script>

<style>

.eco-header{
 position: absolute;
  top: 0;
  width: 100%;
  border-bottom: 1px solid rgba(255, 255, 255, 0.08);;
  
  
}

.üst-navigation-bar {


  display: flex;
  justify-content: space-evenly;
  align-items: center;
  
  border-bottom: 1px solid rgb(255,255,255,0.16);
}

.başlık {
  display: flex;
  justify-content: space-between;
  color: #ffffff;
  font-family: Mukta;
  font-size: 32px;
  font-weight: 600;
  line-height: 38px;
  letter-spacing: 0em;
  text-align: center;

  margin-left: 40px;
  padding: 9px;
  padding-right: 550px;
}
.üst-bar {
  display: flex;
  width: 100%;
  height: 56px;
}
.contact {
  display: flex;
  justify-content: space-between;
  color: #ffffff;
  padding: 16px;
  /*margin-left: 580.5px;*/
}

.phone {
  display: flex;
  justify-content: space-between;
  font-family: "Mukta";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
}

.phone-icon {
  padding-right: 5px;
}

.email {
  display: flex;
  justify-content: space-between;
  font-family: "Mukta";
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 24px;
  padding-left: 18.5px;
}
.email-icon {
  padding-right: 5px;
}
.konum {
  display: flex;
  justify-content: space-between;
  font-family: "Mukta";
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 24px;
  padding-left: 18.5px;
}
.konum-icon {
  padding-right: 5px;
}
.line {
  width: 32px;
  height: 0px;

  opacity: 0.6;
  /* Black and White/White */

  border: 1px solid #ffffff;
  transform: rotate(90deg);

  /* Inside auto layout */

  flex: none;
  order: 1;
  flex-grow: 0;

  margin-top: 12px;
}
.sosyal-medya {
  display: flex;
  justify-content: space-between;
  color: #ffffff;
  margin-top: 15.5px;
}
.sosyal-medya-icons {
  padding-right: 5px;
}
.sosyal-medya-icons .eci {
  font-size: 18px;
  padding: 5px;

}

.line2 {
  width: 32px;
  height: 0px;
  opacity: 0.6;
  /* Black and White/White */
  border: 1px solid #ffffff;
  transform: rotate(90deg);
  /* Inside auto layout */
  flex: none;
  order: 1;
  flex-grow: 0;
  margin-top: 13px;
}

.language {
  display: flex;
  justify-content: space-between;
  margin-top: 20.5px;
  padding-right: 20px;

  color: #ffffff;
}
.toggle-switch {
  width: 56px;
  height: 32px;
  right: 40px;
} 

input[type="checkbox"] {
  width: 0;
  height: 0;
  visibility: hidden;
}

label {
  display: block;
  width: 50px;
  height: 30px;
  background-color: #ffffff;
  border-radius: 100px;
  position: relative;
  cursor: pointer;
  transition: 0.5s;
}

/*toggle switch buton */
label::after {
  content: "";
  width: 25px;
  height: 25px;
  background-color: #ffc841;
  position: absolute;
  border-radius: 70px;
  top: 2px;
  left: 2px;
  transition: 0.3s;
}
input:checked + label::after {
  left: calc(100% - 2px);
  transform: translateX(-100%);
}

.alt-navigation-bar{
  display:flex;
  justify-content: space-between;
height: 72px;
width: 100%;
left: 0px;
top: 56px;
border-radius: 0px;

}
 .dropdown-menu {
  position: relative;
  height: auto;
  top: 21px;
  left: 50px;
  font-size: 16px;
font-weight: 400;
line-height: 20px;
letter-spacing: 0em;
text-align: left;
display: flex;
color: #f9f9f9;
 gap: 25px;
  
}
.dropdown-home{
  display: flex;

  }
 .dropdown-Company{
  display: flex;
  color: white;
font-size: 16px;
font-weight: 400;
line-height: 20px;
text-align: left;
}
.dropdown-Sector{
  display: flex;
  color: white;
font-size: 16px;
font-weight: 400;
line-height: 20px;
text-align: left;
}
  
 .dropdown-investor{
display: flex;
color: white;
font-size: 16px;
font-weight: 400;
line-height: 20px;
text-align: left;

}


  .dropdown-documents{
    display: flex;
  
  }
  .dropdown-news{
    display: flex;

  }
  .dropdown-contact-us{
    display: flex;
  
  }
 .connect_button{
  background: rgba(255, 255, 255, 0.08);
  box-sizing: border-box;
  border: 1px solid #ffffff;
  border-radius: 6px;
  color: #ffffff;
  display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 10px 16px;
gap: 10px;

position: absolute;
width: 200px;
height: 40px;
left: 1290px;
right: 40px;
top: 72px;
padding-top: 16px;
padding-bottom: 16px;
font-family: 'Mukta';
font-style: normal;
font-weight: 600;
font-size: 14px;
line-height: 20px;
/* identical to box height, or 143% */

text-align: center;

 }

.company{
  border-bottom: 1px solid white;
  display: flex;
  height: 20px;

}
.sector{
   border-bottom: 1px solid white;
  display: flex;
  height: 20px;
}
.invester  {
  border-bottom: 1px solid white;
  display: flex;
  height: 20px;
}
.dropdown-investor:hover .dropdown-content-investor {
  display: block;
}
.dropdown-Company:hover .dropdown-content-investor {
  display: block;
}
.dropdown-Sector:hover .dropdown-content-investor {
  display: block;
}
</style>
