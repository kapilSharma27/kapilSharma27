<template>
  <div>
    <section class="skills" id="skills">
      <div class="max-width">
        <h2 class="title">My skills</h2>
        <div class="skills-content">
          <div class="column left">
            <div class="text">My creative skills & experiences.</div>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Dignissimos, ratione error est recusandae consequatur, iusto illum
              deleniti quidem impedit, quos quaerat quis minima sequi.
              Cupiditate recusandae laudantium esse, harum animi aspernatur
              quisquam et delectus ipsum quam alias quaerat? Quasi hic quidem
              illum. Ad delectus natus aut hic explicabo minus quod.
            </p>
            <a href="#" class="about-img">Read more</a>
          </div>
          <div class="column right">
            <div class="bars">
              <div class="info">
                <span>JavaScript</span>
                <span>100%</span>
              </div>
              <div class="line html"></div>
            </div>
            <div class="bars">
              <div class="info">
                <span>Angular 2+</span>
                <span>90%</span>
              </div>
              <div class="line ng"></div>
            </div>
            <div class="bars">
              <div class="info">
                <span>Vue-Js</span>
                <span>80%</span>
              </div>
              <div class="line css"></div>
            </div>
            <div class="bars">
              <div class="info">
                <span>HTML</span>
                <span>100%</span>
              </div>
              <div class="line html"></div>
            </div>
            <div class="bars">
              <div class="info">
                <span>CSS</span>
                <span>80%</span>
              </div>
              <div class="line css"></div>
            </div>
            <div class="bars">
              <div class="info">
                <span>BootStrap</span>
                <span>100%</span>
              </div>
              <div class="line html"></div>
            </div>
            <div class="bars">
              <div class="info">
                <span>React-JS</span>
                <span>70%</span>
              </div>
              <div class="line cc"></div>
            </div>
            <div class="bars">
              <div class="info">
                <span>Git & Github</span>
                <span>75%</span>
              </div>
              <div class="line opensource"></div>
            </div>
            <div class="bars">
              <div class="info">
                <span>JAVA</span>
                <span>70%</span>
              </div>
              <div class="line cc"></div>
            </div>
            <div class="bars">
              <div class="info">
                <span>JSP & Servlet</span>
                <span>50%</span>
              </div>
              <div class="line ne"></div>
            </div>
            <div class="bars">
              <div class="info">
                <span>Adobe Photoshop, Illustrator & Zeplin</span>
                <span>80%</span>
              </div>
              <div class="line css"></div>
            </div>
            <div class="bars">
              <div class="info">
                <span>Spring & Hibernate</span>
                <span>40%</span>
              </div>
              <div class="line sh"></div>
            </div>
            <div class="bars">
              <div class="info">
                <span>Node-Js & Express</span>
                <span>50%</span>
              </div>
              <div class="line ne"></div>
            </div>
            <div class="bars">
              <div class="info">
                <span>MySql & MongoDB</span>
                <span>70%</span>
              </div>
              <div class="line cc"></div>
            </div>
            <div class="bars">
              <div class="info">
                <span>FireBase</span>
                <span>70%</span>
              </div>
              <div class="line cc"></div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style>
.skills-content .right .html::before {
  width: 100%;
}
.skills-content .right .css::before {
  width: 80%;
}
.skills-content .right .ng::before {
  width: 90%;
}
.skills-content .right .opensource::before {
  width: 75%;
}
.skills-content .right .cc::before {
  width: 70%;
}
.skills-content .right .ne::before {
  width: 50%;
}
.skills-content .right .sh::before {
  width: 25%;
}
</style>
