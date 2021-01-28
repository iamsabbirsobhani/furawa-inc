<template>
  <div class="main-2">
    <div class="item-3">
      <h1>Optimized Job Search</h1>
      <p>Learning new skills is good, getting a new job is even better.</p>
      <h3>Strategy</h3>
      <p>
        Work with our career coaches and learn how to optimize yourself for
        hirability.
      </p>
      <h3>Execution</h3>
      <p>
        Kickstart your new journey with proactive methods for ideal job matches.
      </p>
      <h3>Be Prepared</h3>
      <p>Learn how to prepare for traditional and technical interviews.</p>
    </div>
    <div class="item-4">
      <img src="../assets/img-2.webp" alt="" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.main-2 {
  display: flex;
  justify-content: space-evenly;
  margin-bottom: 100px;
}
.item-3 h1 {
  font-size: 40px;
}
.main-2 h3 {
  border-left: 2px solid #ff08d7;
  padding: 10px;
}
@media (max-width: 375px) and (min-width: 320px){
  .main-2 {
    flex-direction: column;
    padding: 10px;
  }
  .item-3 h1 {
  font-size: 19px;
}
.item-4 img{
  width: 300px;
}
}
</style>