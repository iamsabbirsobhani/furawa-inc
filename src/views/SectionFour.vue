<template>
  <div class="main-4">
    <div class="item-6">
      <h1>Immersive Learning</h1>
      <p>
        Learning alone is tough. Sometimes it's better to surround yourself into
        the culture of what you want to master, including the experts, the like
        minded people and the content.
      </p>
    </div>
    <div class="item-7">
      <img src="../assets/immersive-learning.webp" alt="" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.main-4 {
  display: flex;
  padding: 20px;
  justify-content: space-evenly;
  text-align: left;
  font-family: "Inter", sans-serif;
  position: relative;
  margin-bottom: 300px;
}
.item-6 {
  width: 600px;
  margin: 0px;
}
.item-6 h1 {
  font-size: 40px;
}
.item-7 {
  width: 600px;
}
@media (max-width: 375px) and (min-width: 320px){
  .main-4 {
    flex-direction: column;
  }
  .item-7 img{
    width: 300px;
    margin-top: 20px;
  }
  .item-6{
    width: 300px;
  }
  .item-6 h1 {
  font-size: 19px;
}
.item-6 p {
  width: 300px;
  margin: unset;
}
.item-7 {
  width: 300px;
}
.item-6 h1 {
  font-size: 40px;
  width:300px;
  margin: 0px;
}
}
</style>