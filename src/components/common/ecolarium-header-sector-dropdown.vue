<template>
  <div class="dropdown-content-investor">
    <div class="investor-conteiner">
      <div class="our-for-conteiner">
        <div class="Our-Investment-conteiner">
          <div class="Renwable-Energy-conteiner">
            <div class="Renwable-Energy-icon">
              <i class="eci recycled-energy"></i>
              <h2>Renwable Energy</h2>
            </div>

            <p>
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint. Velit officia.
            </p>
          </div>
          <div class="Transportation-Logistic">
            <div class="Transportation-Logistic-icon">
              <i class="eci boat"></i>

              <h2>Transportation & Logistic</h2>
            </div>

            <p>
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint. Velit officia.
            </p>
          </div>
          <div class="Industrial-Area">
            <div class="Industrial-Area-icon">
              <i class="eci building-office"></i>

              <h2>Industrial-Area</h2>
            </div>

            <p>
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint. Velit officia.
            </p>
          </div>
        </div>
        <div class="for-Investment">
          <div class="Home-Solution">
            <div class="Home-Solution-icon">
              <i class="eci home-check"></i>

              <h2>Home Solution</h2>
            </div>

            <p>
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint. Velit officia.
            </p>
          </div>
          <div class="Climate-Change-and-RD">
            <div class="Climate-Change-and-RD-icon">
              <i class="eci leaf"></i>

              <h2>Climate Change and R&D</h2>
            </div>

            <p>
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint. Velit officia.
            </p>
          </div>
        </div>
      </div>
      <div class="Interested-to-learn-more">
        <h1>Interested to learn more?</h1>
        <p>
          Aliqua id fugiat nostrud irure ex duis ea quis id quis ad et. Sunt qui
          esse pariatur duis deserunt mollit dolore cillum minim tempor enim.
        </p>
        <button class="Talk-to-Us">Talk to Us</button>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style>
.dropdown-content-investor {
  display: none;
  position: fixed;
  background-color: #ffffff;
  color: #080e38;
  margin-top: 53px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  width: 100%;
  z-index: 1;
  left: 0px;
  right: 0;
  justify-content: space-between;
  font-weight: 600;
  font-size: 14px;
  line-height: 20px;
}
.investor-conteiner {
  display: flex;
}
.our-for-conteiner {
  display: flex;
  width: 64%;
  background-color: white;
  padding-left: 156px;
  padding-top: 40px;
  padding-bottom: 56px;
  padding-right: 70px;
}
.our-for-conteiner h1 {
  color: #1732f5;
}
.our-for-conteiner p {
  padding-top: 8px;
  padding-left: 25px;
  width: 239px;
  color: #6b6e88;
  font-weight: 400;
  font-size: 12px;
  line-height: 16px;
}
.Renwable-Energy-conteiner {
  padding-right: 116px;
}
.Interested-to-learn-more {
  width: 36%;
  background-color: #f1f2f6;
  padding-left: 56px;
  padding-top: 40px;
}

.Renwable-Energy-icon {
  display: flex;
  gap: 5px;
}
.Transportation-Logistic-icon {
  display: flex;
  padding-top: 24px;
  gap: 5px;
}

.completed-investment-conteiner {
  color: black;
}
.Industrial-Area-icon {
  display: flex;
  padding-top: 24px;
  gap: 5px;
}
.Home-Solution-icon {
  display: flex;
  gap: 5px;
}
.Climate-Change-and-RD-icon {
  display: flex;
  padding-top: 24px;
  gap: 5px;
}
.Interested-to-learn-more p {
  padding-top: 8px;
  width: 307px;
  padding-bottom: 16px;
  font-weight: 400;
  font-size: 12px;
  line-height: 16px;
}

.Interested-to-learn-more button {
  background: #4ed8f6;
  border: #4ed8f7;
  padding: 10px 16px;
  border-radius: 6px;
  font-weight: 600;
  font-size: 16px;
  line-height: 20px;
}
</style>
