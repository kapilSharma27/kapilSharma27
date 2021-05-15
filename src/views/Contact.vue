<template>
  <div>
    <section class="contact" id="contact">
      <div class="max-width">
        <h2 class="title">Contact me</h2>
        <div class="contact-content">
          <div class="column left">
            <div class="text">Get in Touch</div>
            <p></p>
            <div class="icons">
              <div class="row">
                <!-- <i class="fas fa-user"></i> -->
                <lord-icon
                  src="https://cdn.lordicon.com/dxjqoygy.json"
                  trigger="loop"
                  colors="primary:#e8308c,secondary:#66eece"
                  stroke="100"
                  style="width:48px;height:48px"
                >
                </lord-icon>
                <div class="info">
                  <div class="head">Name</div>
                  <div class="sub-title">Kapil Sharma</div>
                </div>
              </div>
              <div class="row">
                <lord-icon
                  src="https://cdn.lordicon.com/zzcjjxew.json"
                  trigger="loop"
                  colors="primary:#e8308c,secondary:#30e8bd"
                  style="width:48px;height:48px"
                >
                </lord-icon>
                <!-- <i class="fas fa-map-marker-alt"></i> -->
                <div class="info">
                  <div class="head">Address</div>
                  <div class="sub-title">Ghaziabd, Uttar Pradesh, India</div>
                </div>
              </div>
              <div class="row">
                <lord-icon
                  src="https://cdn.lordicon.com/rhvddzym.json"
                  trigger="loop"
                  colors="primary:#e8308c,secondary:#08a88a"
                  style="width:48px;height:48px"
                >
                </lord-icon>
                <!-- <i class="fas fa-envelope"></i> -->
                <div class="info">
                  <div class="head">Email</div>
                  <div class="sub-title">kapils23498@gmail.com</div>
                </div>
              </div>
            </div>
          </div>
          <div class="column right">
            <div class="text">Message me</div>
            <form action="https://formspree.io/f/mqkgooqj" method="POST">
              <div class="fields">
                <div class="field name">
                  <input type="text" placeholder="Name" name="Name" required />
                </div>
                <div class="field email">
                  <input
                    type="email"
                    placeholder="Email"
                    name="email_id"
                    required
                  />
                </div>
              </div>
              <div class="field">
                <input
                  type="text"
                  placeholder="Subject"
                  name="subject"
                  required
                />
              </div>
              <div class="field textarea">
                <textarea
                  cols="50"
                  rows="20"
                  placeholder="Message..."
                  name="message"
                  required
                ></textarea>
              </div>
              <div class="button">
                <button type="submit">Send message</button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
