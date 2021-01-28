<template>
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
</template>

<script>
export default {};
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
</style>