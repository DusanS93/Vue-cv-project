<template>
    <nav class="nav">
            <router-link :to="{ name: 'home' }" class="navLinks">
            Home
            </router-link>
            <router-link :to="{ name: 'about' }" class="navLinks">
            About
            </router-link>
            <router-link :to="{ name: 'education' }" class="navLinks">
            Education
            </router-link>
            <router-link :to="{ name: 'workplaces' }" class="navLinks">
            Workplaces
            </router-link>
            <router-link :to="{ name: 'skills' }" class="navLinks">
            Skills
            </router-link>
            <router-link :to="{ name: 'contact' }" class="navLinks">
            Contact
            </router-link>
        </nav>
</template>

<script>
export default {
    name: "NavBar"
}
</script>
