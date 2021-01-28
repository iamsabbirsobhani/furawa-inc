<template>
  <div class="footer">
    <div class="sign-up">
    <img class="logo" src="@/assets/logo.svg" />
      <form>
        <h3>Sign up to our newsletter</h3>
        <input type="text" placeholder="Name" required />
        <input type="email" placeholder="Email" required />
        <button class="btn-submit">Submit</button>
      </form>
    </div>
    <div class="featured-courses">
      <ul>
        <li><a href="">Full-Stack Web Developement Immersive</a></li>
        <li><a href="">Data Science & Machine Learning Immersive</a></li>
        <li><a href="">Full-Stack UX Design Immersive</a></li>
        <li><a href="">Web Development for Absolute Beginners</a></li>
        <li><a href="">Data Science & Machine Learning</a></li>
        <li><a href="">Introduction to FinTech</a></li>
        <li><a href="">Introduction to Python</a></li>
        <li><a href="">User Experience Design (Fundamentals)</a></li>
        <li><a href="">User Interface Design</a></li>
        <li><a href="">Introduction to Product Management</a></li>
      </ul>
      <h3>Contact Us</h3>
      <p>+852 68838583</p>
      <p>hello@furawa.co</p>
    </div>
    <div class="quick-links">
      <h3>Quick Links</h3>
      <ul>
        <li><a href="">About</a></li>
        <li><a href="">Corporate Training</a></li>
        <li><a href="">Hire Xccelerate Top Talent</a></li>
        <li><a href="">Events</a></li>
        <li><a href="">Blog</a></li>
        <li><a href="">All Courses</a></li>
        <li><a href="">Join Us</a></li>
        <li><a href="">Teach With Us</a></li>
        <li><a href="">FAQs</a></li>
        <li><a href="">Entrepreneur X</a></li>
        <li><a href="">School Ambassador Program</a></li>
        <li><a href="">Future Education Foundation</a></li>
        <li><a href="">COVID-19 Economic Recovery Education Fund</a></li>
        <li><a href="">Women in Tech Scholarship</a></li>
        <li><a href="">1-on-1 Career Consultation</a></li>
      </ul>
      <div>
        <h3>Office Address</h3>
        <p>
          New York City<br />
          200 West Street is the global headquarters of the Goldman Sachs
          investment banking firm, located in New York City.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.footer {
  background-color: #cadefc;
  display: flex;
  justify-content: space-between;
  padding: 20px;
}
input{
    display: block;
}
ul{
        padding-inline-start: 0px;
}
li{
    list-style-type: none;
}
.quick-links p{
    width: 400px;
}
</style>