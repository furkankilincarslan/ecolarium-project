<template>
<div class="ecolarium-footer">
    <div class="footer-bar">
        <div class="footer-başlık">
            <p>ecolarium</p>
        </div>
        <div class="footer-contact">
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
        <div class="footer-sosyal-medya">
          <div class="linkedin"><i class="eci linkedin-outline"></i></div>
          <div class="instagram"><i class="eci instagram-outline"></i></div>
          <div class="facebook"><i class="eci facebook-outline"></i></div>
        
        </div>

        <div class="footer-line"></div>
    
    
    </div>

    
    <div class="footer-hero">
        <div class="about-ecolarium">
            <h1>About ecolarium</h1> 
             
               <p> Our Story</p>
               <p>Miles Tones</p>
               <p>Our Core Values</p>
               <p> Team</p>
        </div>
        <div class="sectors">
            <h1>Sectors</h1>
            <p>Renewable Energy</p>
            <p>Transportation & Logistic</p>
            <p>Industrial Areas</p>
            <p>Residences</p>
            <p>Climate Change and R&D</p>
            
        </div>
        <div class="ecolarium">
            <h1>Ecolarium</h1>
            <p>Our News</p>
            <p>Document</p>
            <p>FAQ</p>
        </div>
        <div class="get-news">
            <h1>Get News and Update</h1>
            
            <div class="get-button"><p>Get News and Update</p></div>

            
        </div>
        <div class="submit">
                <p>submit</p>
            </div>
    </div>
    <div class="footer-footer">
        <h1> © 2022. All rights reserved</h1>
        <h2>Protection of Personel Data</h2>
        <p>Copyrights and Conditions of Use</p>
    </div>
</div>

</template>

<script setup>
</script>

<style>
.ecolarium-footer{

width: 100%;
height: 577px;
left: 0px;
top: 2878px;
    background: #080E38;
}

.footer-bar{
    display: flex;
    color: white;
    
}
.footer-başlık{
font-size: 32px;
font-weight: 600;
line-height: 38px;
letter-spacing: 0em;
text-align: center;
margin-top: 80px;
margin-left: 156px;
}
.footer-contact{
    display: flex;
    justify-content: space-between;
font-size: 14px;
font-weight: 400;
line-height: 24px;
letter-spacing: 0em;
text-align: left;
margin-top: 87px;
margin-left: 372.5px;
gap:10px;

}
.line{
    background-color: white;
}

.footer-sosyal-medya{
display: flex;
flex-direction: row;
align-items: flex-start;
padding: 0px;
gap: 16px;
justify-content: space-between;

position: absolute;
width: 104px;
height: 24px;
left: 1180px;
margin-top:90.5px;
}

.footer-sosyal-medya,.eci{
    font-size: 18px;
}
.linkedin{
height: 24px;
width: 24px;
left: 0px;
top: 0px;
border-radius: 0px;
}
.instagram{
    height: 24px;
width: 24px;
left: 0px;
top: 0px;
border-radius: 0px;

}
.facebook{
    height: 24px;
width: 24px;
left: 0px;
top: 0px;
border-radius: 0px;

}
.footer-line{
position: absolute;
width: 1128px;
height: 0px;
left: 156px;
top: 2968px;

opacity: 0.16;
/* Black and White/White */

border: 1px solid #FFFFFF;
}

.footer-hero{
    display: flex;
    color: white;
    border-bottom: 1px solid rgb(255, 255,255,0.16);

    height: 358px;
   
}
 
 .about-ecolarium{
    margin-top: 80px;
    margin-left: 156px;
 }
 .about-ecolarium>h1{
font-size: 18px;
font-weight: 700;
line-height: 24px;
letter-spacing: 0em;
text-align: left;
padding-bottom: 16px;

 }
 .about-ecolarium>p{
width: 100px;
height: 24px;
font-style: normal;
font-weight: 400;
font-size: 14px;
line-height: 24px;
display: flex;
align-items: center;
color: #FFFFFF;
opacity: 0.72;
padding-bottom: 16px;
 }
  .sectors{
    margin-top: 80px;
    margin-left: 98px;
 }
 .sectors>h1{
font-size: 18px;
font-weight: 700;
line-height: 24px;
letter-spacing: 0em;
text-align: left;
padding-bottom: 16px;

 }
 .sectors>p{
width: 200px;
height: 24px;
font-style: normal;
font-weight: 400;
font-size: 14px;
line-height: 24px;
display: flex;
align-items: center;
color: #FFFFFF;
opacity: 0.72;
padding-bottom: 16px;
 }

   .ecolarium{
    margin-top: 80px;
    margin-left: 30px;
 }
 .ecolarium>h1{
font-size: 18px;
font-weight: 700;
line-height: 24px;
letter-spacing: 0em;
text-align: left;
padding-bottom: 16px;

 }
 .ecolarium>p{
width: 200px;
height: 24px;
font-style: normal;
font-weight: 400;
font-size: 14px;
line-height: 24px;
display: flex;
align-items: center;
color: #FFFFFF;
opacity: 0.72;
padding-bottom: 16px;
 }
 .get-news{ 
    margin-top: 80px;
    margin-left: 68px;
    justify-content: space-around;
 }

 .get-button{
    display: flex;
width: 266px;
height: 56px;
left: 0px;
top: 0px;
background: #393E60;
border-radius: 6px;
margin-top: 8px;
margin-right: 8px;

 }
 .get-button>p{
    display: flex;
width: 160px;
height: 20px;
left: 24px;
top: 18px;
font-style: normal;
font-weight: 400;
font-size: 16px;
line-height: 20px;
padding-left: 24px;
padding-top: 18px;
color: #9C9FAF;
}
.submit{
display: flex;
justify-content: center;
align-items: center;
width: 130px;
height: 56px;
background: #4ED8F7;
border-radius: 6px;
margin-right: 156px;
margin-top: 103.5px;
color: #080E38;
}
.submit>p{
    width: 50px;
height: 20px;
font-style: normal;
font-weight: 600;
font-size: 16px;
line-height: 20px;
text-align: center;
color: #080E38;
flex: none;
order: 0;
flex-grow: 0;
}

.footer-footer{display: flex; 
justify-content: space-between;
    margin-left: 156px;
    color: white;
    margin-top: 32px;
}

.footer-footer>h2{
    display: flex;
    margin-left: 731px;
    opacity: 0.56;
    position: absolute;
width: 162px;
height: 24px;
font-style: normal;
font-weight: 400;
font-size: 14px;
line-height: 24px;
}
.footer-footer>p{
    display: flex;
    margin-left: 933px;
    opacity: 0.56;
    position: absolute;
width: 195px;
height: 24px;
font-style: normal;
font-weight: 400;
font-size: 14px;
line-height: 24px;
}

</style>