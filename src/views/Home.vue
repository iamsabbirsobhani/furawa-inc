<template>
  <div class="home">
    <div class="main">
      <div class="item-1">
        <h1>Your New Tech Career Starts Here</h1>
        <p>
          Do you have the career you deserve? It's time to become the next, best
          you. Learn in-demand tech skills that boost your professional life.
        </p>
        <button class="btn-1">
          View courses
          <p>></p>
        </button>
      </div>
      <div class="item-2">
        <img src="../assets/career-focused.webp" alt="" />
      </div>
    </div>
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
          Kickstart your new journey with proactive methods for ideal job
          matches.
        </p>
        <h3>Be Prepared</h3>
        <p>Learn how to prepare for traditional and technical interviews.</p>
      </div>
      <div class="item-4">
        <img src="../assets/img-2.webp" alt="" />
      </div>
    </div>

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

 <div class="main-4">
      <div class="item-6">
        <h1>Immersive Learning</h1>
        <p>
          Learning alone is tough. Sometimes it's better to surround yourself into the culture of what you want to master, including the experts, the like minded people and the content.
        </p>
      </div>
      <div class="item-7">
        <img src="../assets/immersive-learning.webp" alt="" />
      </div>
    </div>

  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>

<style>
.main {
  display: flex;
  padding: 20px;
  justify-content: space-evenly;
  text-align: left;
  font-family: "Inter", sans-serif;
  position: relative;
  top: 100px;
  margin-bottom: 300px;
}
.item-1 {
  width: 600px;
  margin: 0px;
}
.item-1 h1 {
  font-size: 64px;
}
.item-2 {
  width: 600px;
}
.btn-1 {
  background-color: #25ced8;
  outline: none;
  cursor: pointer;
  height: 60px;
  width: 180px;
  font-weight: bold;
  font-size: 18px;
  border-radius: 30px;
  color: #ffffff;
  border: none;
}
.btn-1:hover {
  background-color: #4eccd3;
}
.btn-1 p {
  display: inline;
  font-weight: normal;
}
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
.item-5{
  display: flex;
  justify-content: space-between;
  padding: 100px;
}
.item-5 h1{
  font-size: 64px;
  border-left: 2px solid #ff08d7;
  margin: 0px;
  padding: 10px;
  color: #25CED8;
  box-sizing: border-box;
}
.item-5 p{
  font-size: 18px;
}
.main-3{
  margin-bottom: 150px;
  background-color: #cadefc;
}
.main-3 h1{
  text-align: center;
  position: relative;
  padding: 10px;
}
.main-4{
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
</style>
