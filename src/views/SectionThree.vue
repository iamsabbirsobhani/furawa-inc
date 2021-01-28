<template>
  <div class="main-3">
    <h1>Success rate</h1>
    <div class="item-5">
      <div>
        <h1>91%</h1>
        <p>Graduate job placement rate</p>
      </div>
      <div>
        <h1>28 days</h1>
        <p>Average graduate to placement</p>
      </div>
      <div>
        <h1>90%</h1>
        <p>Satisfaction rate (switch-up)</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.main-3 {
  margin-bottom: 150px;
  background-color: #FDFDFC;
}
.item-5 {
  display: flex;
  justify-content: space-between;
  padding: 100px;
}
.item-5 h1 {
  font-size: 64px;
  border-left: 2px solid #ff08d7;
  margin: 0px;
  padding: 10px;
  color: #25ced8;
  box-sizing: border-box;
}
.item-5 p {
  font-size: 18px;
  color: rgba(79, 58, 101, 0.541);
}
.main-3 h1 {
  text-align: center;
  position: relative;
  padding: 10px;
}
@media (max-width: 375px) and (min-width: 320px){
  .item-5{
    flex-direction: column;
  }
  .item-5 h1 {
  font-size: 40px;
  }
}
</style>