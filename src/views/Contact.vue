<template>
  <div class="contact">
    <h3>Contact Page</h3>
    <div class="form">
      <p>House: #88</p>
      <p>Road: 3, Los Angeles</p>
      <p>Email: sabbirsobhani@gmail.com</p>
    </div>
    <slot></slot>
  </div>
</template>

<script>
export default {};
</script>
<style>
  .form{
    width: 300px;
    border-radius: 10px;
    background-color: white;
    margin: 100px auto;
    padding: 20px;
    color: black;
    font-size: 16px;
    text-align: left;
    box-shadow: 1px 1px 10px .5px gray;
    box-sizing: border-box;
}
.contact{
    position: relative;
    top: 80px;
    width: 300x;
}
.contact h3{
    margin: 0;
}
</style>