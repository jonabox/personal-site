<template>
  <v-layout>
    <v-flex>
      <v-card flat color="transparent" class="my-3">
        <v-card-text class="display-1 text-center text-wrap" style="word-break: normal">Background</v-card-text>
      </v-card>

      <v-card flat color="transparent" class="my-3">
        <v-card-title>Education</v-card-title>
        <v-card-subtitle>Massachusetts Institute of Technology</v-card-subtitle>
        <v-card-text>
          <p>Candidate for Masters of Engineering Program in Computer Systems</p>
          <p>Bachelor of Science in Computer Science, 2019</p>
        </v-card-text>
      </v-card>

      <v-card flat color="transparent" class="my-3">
        <v-card-title>Work and Research</v-card-title>
        <v-card-text>
          <h4 class="display-7 font-weight-bold">CSAIL Document Processing Research Assistant and Project Coordinator</h4>
          <ul>
            <li>Collaborated with 8 fintech companies to coordinate internal project proposals relating to the processing of corporate documents using preprocessing techniques and OCR</li>
            <li>Held weekly meetings to discuss progress and timelines with team members and company sponsors</li>
          </ul>
        </v-card-text>
        <v-card-text>
          <h4 class="display-7 font-weight-bold">Multi-Party Computation Project</h4>
          <ul>
            <li>Designed the foundation for a web platform that would encapsulate a bare-bones C++ implementation of several cryptographic and multi-party computations</li>
            <li>Worked on transcribing the C++ codebase into JavaScript using Emscripten, a tool that compiles C++ into WebAssembly</li>
            <li>Setup a MySQL database for the storage of credentials and an SMTP server to handle email tokens</li>
            <li>Followed many security best practices, including salting/hashing passwords, CSRF tokens, CSP headers, and creating TLS certificates using Let'sEncrypt</li>
          </ul>
        </v-card-text>

        <v-card-text>
          <h4 class="display-7 font-weight-bold">Vivint SmartHome Internship</h4>
          <ul>
            <li>Worked on circumventing corporate firewalls using NAT traversing servers for WebRTC applications</li>
            <li>Used Docker, Kubernetes, Terraform, and Google’s Cloud Platform to automate the setup of said servers and scale the infrastructure</li>
          </ul>
        </v-card-text>

        <v-card-text>
          <h4 class="display-7 font-weight-bold">Cells for Cells Internship</h4>
          <ul>
            <li>Worked with a team of biotech investigators and facilitated CAD design, 3D printing, and Arduino circuit logistics to design a syringe pump embedded robotic arm to be used for precise bio-filament placement</li>
          </ul>
        </v-card-text>
      </v-card>

      <v-card flat color="transparent" class="my-3">
        <v-card-title>Skills</v-card-title>
        <v-container>
          <v-row>
            <v-col>
              <v-card-text>
                <h4
                  class="display-7 font-weight-bold"
                >Proficient Programming Languages and Frameworks</h4>
                <ul>
                  <li>Python</li>
                  <li>JavaScript</li>
                  <li>Vue.js</li>
                  <li>React.js</li>
                  <li>Java</li>
                  <li>Git</li>
                </ul>
              </v-card-text>
            </v-col>
            <v-col>
              <v-card-text>
                <h4 class="display-7 font-weight-bold">Familiar Programming Languages and Frameworks</h4>
                <ul>
                  <li>Rust</li>
                  <li>HTML/CSS</li>
                  <li>SQL</li>
                  <li>Angular.js</li>
                  <li>React.js</li>
                  <li>C++</li>
                </ul>
              </v-card-text>
            </v-col>
          </v-row>
          <v-row>
            <v-col>
              <v-card-text>
                <h4 class="display-7 font-weight-bold">Software Tools</h4>
                <ul>
                  <li>Amazon Web Services</li>
                  <li>Google Cloud</li>
                  <li>Docker</li>
                  <li>Terraform</li>
                  <li>MySQL</li>
                  <li>MongoDB</li>
                  <li>Unix Command-Line</li>
                </ul>
              </v-card-text>
            </v-col>
            <v-col>
              <v-card-text>
                <h4 class="display-7 font-weight-bold">Other Skills</h4>
                <ul>
                  <li>Fully Bilingual (Spanish, English)</li>
                  <li>Photoshop</li>
                  <li>Adobe After Effects</li>
                  <li>FL Studio</li>
                  <li>Intermediate Music Theory</li>
                  <li>AutoCAD</li>
                  <li>Makerspace Tools</li>
                  <li>Arduino and Teensy Microcontrollers</li>
                  <li>Electronic Lab Tools</li>
                </ul>
              </v-card-text>
            </v-col>
          </v-row>
        </v-container>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import Logo from "~/components/Logo.vue";
import VuetifyLogo from "~/components/VuetifyLogo.vue";

export default {
  components: {
    Logo,
    VuetifyLogo,
  },
};
</script>