<template>
  <div>
    <div class="scroll-up-btn">
      <i class="fas fa-angle-up"></i>
    </div>
    <!-- navbar -->
    <div><Navbar /></div>

    <!-- HomeScreen -->
    <div><Profile /></div>

    <!-- About -->
    <div>
      <About />
    </div>

    <!-- 3rd -->
    <!-- services section start -->
    <div>
      <Services />
    </div>

    <!-- 5th -->
    <!-- skills section start -->
    <div>
      <Skills />
    </div>

    <!-- 5th -->
    <!-- teams section start -->
    <div>
      <Teams v-if="false" />
    </div>

    <!-- 6th -->
    <!-- contact section start -->
    <div>
      <Contact />
    </div>

    <!-- 7th -->
    <!-- footer section start -->
    <div>
      <Footer />
    </div>
  </div>
</template>

<script>
import Navbar from "../views/Navbar";
import Profile from "../views/Profile";
import About from "../views/About";
import Services from "../views/Services";
import Skills from "../views/Skills";
import Teams from "../views/Teams";
import Contact from "../views/Contact";
import Footer from "../views/Footer";
export default {
  components: {
    Navbar,
    Profile,
    About,
    Services,
    Skills,
    Teams,
    Contact,
    Footer,
  },

  data() {
    return {};
  },
};
</script>

<style scoped></style>
