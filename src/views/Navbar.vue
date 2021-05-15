<template>
  <nav class="navbar">
    <div class="max-width">
      <div class="logo">
        <a
          href="#"
          class="hire about-img"
          style="padding: 20px; border-radius: 10px;"
          >Kapil <span>Sharma</span></a
        >
      </div>
      <ul class="menu about-img" style="padding: 20px; border-radius: 10px;">
        <li><a href="#home" class="menu-btn hire">Home</a></li>
        <li><a href="#about" class="menu-btn hire">About</a></li>
        <li><a href="#services" class="menu-btn hire">Services</a></li>
        <li><a href="#skills" class="menu-btn hire">Skills</a></li>
        <li>
          <a href="#teams" class="menu-btn hire" v-if="false">Testimonials</a>
        </li>
        <li><a href="#contact" class="menu-btn hire">Contact</a></li>
      </ul>
      <div class="menu-btn">
        <i class="fas fa-bars"></i>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style></style>
