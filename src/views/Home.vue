<template>
  <div class="home">
    <NavComponent />
    <HeaderComponent />
    <AboutComponent />
    <SectionComponent />
    <TeamComponent />
    <ContactComponent />
    <RegisterComponent />
    <FooterComponent />
  </div>
</template>

<script>
// @ is an alias to /src
import NavComponent from "@/components/Nav.vue";
import HeaderComponent from "@/components/Header.vue";
import AboutComponent from "@/components/About.vue";
import SectionComponent from "@/components/Section.vue";
import TeamComponent from "@/components/Team.vue";
import ContactComponent from "@/components/Contact.vue";
import RegisterComponent from "@/components/Register.vue";
import FooterComponent from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    NavComponent,
    HeaderComponent,
    AboutComponent,
    SectionComponent,
    TeamComponent,
    ContactComponent,
    RegisterComponent,
    FooterComponent
  },
};
</script>
