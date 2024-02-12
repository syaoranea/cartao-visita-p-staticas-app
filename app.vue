<template>
  <main>
    <Profile
        :photo="photo"
        title="Eduardo Rocha"
        subtitle="@syaoranea"
        headline="Front-End Developer"
    />
  
    <div class="max-w-xs mx-auto">
        <ButtonAction
            link="https://wa.me/5511957080582"
            icon="💬"
            text="Whatsapp" />

        <ButtonAction
            link="https://www.linkedin.com/in/eduardo-rocha-25870a1a6/"
            icon="💼"
            text="Linkedin" />

        <ButtonAction
            link="https://github.com/syaoranea"
            icon="🛠"
            text="Github" />

        <ButtonAction
            link="https://www.instagram.com/edurochaae/"
            icon="👨🏽‍💻"
            text="Instagram" />
    </div>
  </main>
</template>

<script setup>
  import photo from "./assets/img/edu.jpg";
</script>
