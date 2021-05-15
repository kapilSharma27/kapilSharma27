<template>
  <section class="about" id="about">
    <div class="max-width">
      <h2 class="title">About him</h2>
      <div class="about-content">
        <div class="column left">
          <img
            src="../../public/assets/fbprofile1.jpg"
            alt=""
            class="about-img"
            style="border-radius: 10px;"
          />
        </div>
        <div
          class="column right about-img"
          style="padding: 20px; border-radius: 10px;"
        >
          <div class="text">
            He is a Passionate <span class="typing-2"></span>
          </div>
          <p>
            A self taught programmer who is a Passionate contributor towards
            communities, Open Source & Hackathons, Who is Pursuing Knowledge to
            excel in future endeavor and helping people to enhance there
            learnings through providing them with practical experience and
            Knowledge.<br />
            I am professionally a programmer, front end Web developer and
            Trainer, who is motivated, enthusiastic and well organised, with a
            keen eye for beautiful design, primarily based around user
            interfaces. I regularly use version control systems <b>(GIT)</b> to
            maintain my code, and I specialise in responsive web design (RWD).
            The main areas of my expertise are
            <b>Angular 2+, Vue-Js, React-JS JavaScript. HTML(5), CSS(3), </b>
            but I have intermediate knowledge of Node and Firebase. Aside from
            my job, I like to create and contribute to open source projects.
            That helps me to learn a ton of new stuff, grow as a developer and
            support other open source projects. <br />In my free time, i play
            online games, study and reasearch about new technical thing and
            terms, explore Internet and Web.
          </p>
          <a
            @click="DownloadFile('Kapil Resume 7_04_21.pdf')"
            class="about-img"
            download
            >Download Resume</a
          >
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  methods: {
    DownloadFile(fileName) {
      let url = "assets/files/" + fileName;
      //Create XMLHTTP Request.
      let req = new XMLHttpRequest();
      req.open("GET", url, true);
      req.responseType = "blob";
      req.onload = function() {
        //Convert the Byte Data to BLOB object.
        let blob = new Blob([req.response], {
          type: "application/octetstream",
        });
        //Check the Browser type and download the File.
        let isIE = false || !!document.documentMode;
        if (isIE) {
          window.navigator.msSaveBlob(blob, fileName);
        } else {
          let url = window.URL || window.webkitURL;
          let link = url.createObjectURL(blob);
          let a = document.createElement("a");
          a.setAttribute("download", fileName);
          a.setAttribute("href", link);
          document.body.appendChild(a);
          a.click();
          document.body.removeChild(a);
        }
      };
      req.send();
    },
  },
};
</script>

<style></style>
