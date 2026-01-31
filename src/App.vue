<script setup>
import ProfileCard from './components/ProfileCard.vue';

</script>

<template>
    <div class=" flex flex-col md:flex-row items-center justify-center gap-8 min-h-screen
     bg-gradient-to-br from-green-500 to-sky-400">
    <ProfileCard 
        background="./src/assets/workbg.jpg"
        profileimg="./src/assets/profileimg.jpg"
        name="Thanasorn Dusadeeroj"
        subheading="Full-stack Developer"
        followers="67k"
        following="67k"
        projects="67"
        githubicon="./src/assets/githubicion.png"
        facebookicon="./src/assets/facebookicon.png"
        instagramicon="./src/assets/instagram.png"
    />
    <ProfileCard 
        background="./src/assets/workbg.jpg"
        profileimg="./src/assets/nodprofile.jpg"
        name="Kanokpon suebyam"
        subheading="UX/UI Designer"
        followers="100M"
        following="1"
        projects="0"
        githubicon="./src/assets/githubicion.png"
        facebookicon="./src/assets/facebookicon.png"
        instagramicon="./src/assets/instagram.png"
    />
    <ProfileCard 
        background="./src/assets/workbg.jpg"
        profileimg="./src/assets/gapprofile.jpg"
        name="Supakorn ieamgomol"
        subheading="Full-stack Developer"
        followers="0"
        following="0"
        projects="1M"
        githubicon="./src/assets/githubicion.png"
        facebookicon="./src/assets/facebookicon.png"
        instagramicon="./src/assets/instagram.png"
    />
    </div>
</template>

<style scoped></style>
