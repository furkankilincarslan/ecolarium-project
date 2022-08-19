<template>
  <div class="grid-cards">
    <img :src="'/src/assets/image/' + data.image" alt="" />
    <h1>{{ data.title }}</h1>
    <h2>{{ data.button }}</h2>
    <p>{{ data.subtitle }}</p>

    <div class="icon">
      <div class="price-tag1">
        <i class="eci price-tag"></i>
        <div class="price-tag-write">
          <h1>$123</h1>
          <p>Price/hour</p>
        </div>
      </div>
      <div class="piggy-bank1">
        <i class="eci piggy-bank"></i>
        <div class="piggy-bank-write">
          <h1>$3.000</h1>
          <p>Savings</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
defineProps({
  data: null,
});
</script>

<style>
.grid-cards {
  display: inline-block;
  padding: 10px;
}
.grid-cards > h1 {
  height: 32px;
  width: 362px;
  font-size: 24px;
  font-weight: 700;
  line-height: 32px;
  letter-spacing: 0em;
  text-align: left;
  padding-top: 24px;
  padding-bottom: 8px;
}
.grid-cards > h2 {
  border-radius: 300px;
  color: #1732f5;
  background: rgba(255, 255, 255, 0.8);
  backdrop-filter: blur(16px);
  position: absolute;
  margin-top: -109.6px;
  margin-left: 12px;
  font-size: 14px;
  font-weight: 600;
  line-height: 20px;
  letter-spacing: 0em;
  text-align: left;
  padding: 4px 10px;
}
.grid-cards > p {
  font-size: 16px;
  font-weight: 400;
  line-height: 24px;
  letter-spacing: 0em;
  text-align: left;
  height: 72px;
  width: 362px;
  padding-bottom: 14px;
  border-bottom: 1px solid #e6e7eb;
}
.icon {
  display: flex;
  padding-top: 17px;
  padding-bottom: 10px;
}

.price-tag1 {
  display: flex;
  padding-right: 72px;
}
.price-tag.eci {
  border-radius: 100%;
  background-color: #1732f5;
  color: white;
  padding: 10px;
  margin-right: 8px;
}
.price-tag-write > h1 {
  font-size: 16px;
  font-weight: 600;
  line-height: 20px;
  letter-spacing: 0em;
  text-align: left;
  color: #080e38;
}
.price-tag-write > p {
  font-style: normal;
  font-weight: 400;
  font-size: 12px;
  line-height: 16px;
  color: #6b6e88;
}
.piggy-bank1 {
  display: flex;
}
.piggy-bank-write > h1 {
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 20px;
  color: #080e38;
}
.piggy-bank-write > p {
  font-style: normal;
  font-weight: 400;
  font-size: 12px;
  line-height: 16px;
  color: #6b6e88;
}
.piggy-bank1 .eci {
  border-radius: 100%;
  background-color: #1732f5;
  color: white;
  padding: 10px;
  margin-right: 8px;
}
</style>
