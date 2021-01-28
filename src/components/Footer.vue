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
      <h3>Featured Courses</h3>
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

<style scoped>
.footer {
  background-color: #cadefc;
  display: flex;
  justify-content: space-between;
  padding: 20px;
    font-family: 'Inter', sans-serif;
  font-size: 16px;
}
.footer h3, a, p, li, ul{
  font-size: 16px;
    text-decoration: none;

}
.footer a{
  color: rgba(79, 58, 101, 0.719);

}
input{
    display: block;
    width: 250px;
    height: 20px;
    margin: 20px 14px;
    border-radius: 30px;
    outline: none;
    border: .1px solid rgba(197, 197, 197, 0.788);
    padding: 10px;
    font-size: 16px;
}
input:hover{
      border: .1px solid  #FF08D7;

}
ul{
        padding-inline-start: 0px;
}
li{
    list-style-type: none;
}
form{
  position: relative;
  top: 100px;
  border: 1px solid  #574f7d ;
  border-radius: 10px;
  box-shadow: 1px 1px 10px 0.5px #574f7d9f;
  transition: all 0.2s;
}
form h3{
  margin-left: 17px;
  font-size: 16px;
}
form:hover{
  box-shadow: 1px 1px 10px 0.7px #574f7de3;
}
.quick-links p{
    width: 400px;
}
.logo{
  padding-left: 30px;
}
.btn-submit{
  display: block;
  margin: 20px 15px;
  border-radius: 30px;
  outline: none;
  cursor: pointer;
  border: none;
  background-color: #25CED8;
    width: 265px;
    height: 40px;
  color: white;
  font-size: 16px;
  font-weight: bold;
}
.btn-submit:hover{
    background-color: #4eccd3;
}
@media (max-width: 375px) and (min-width: 320px) {
  .footer{
    flex-direction: column;
  }
  form{
    top: 10px;
    /* bottom: 10px; */
  }
  .quick-links p{
    width: 300px;
}
.featured-courses{
  margin-top: 20px;
}
}
</style>