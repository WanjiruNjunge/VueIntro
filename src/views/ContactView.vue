<template>
    
    <div class="contact">
        <v-img alt="Our Logo" 
        max-height="200"
        max-width="300"
        justify="center"
        src="../assets/logo.png">
</v-img>
    <div id="contact">
    <h2>Contact us</h2>
    <p>Contact us by phone on {{ phoneNumber }}, or via our address at 123 Fake Street,
    New York City.</p>
    </div>
    <footer>
    </footer></div>
    </template>
    <script>
    export default {
    name: 'ContactView',
    data() {
    return {
    phoneNumber: '+'
    }
    }
    }
    </script>
    <style scoped="">
    #contact {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu,
    Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    padding: 2rem;
    margin: 2rem;
    border: 1px solid #ddd;
    border-radius: 10px;
    }
    h2 {
    margin: 0 0 1.5rem 0;
    }
    </style>