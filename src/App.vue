<template>
    <v-app>
        <v-app-bar app flat>
            <v-toolbar-title>Scrum Planning Helper</v-toolbar-title>
        </v-app-bar>

        <v-main>
            <router-view />
        </v-main>

        <v-footer>
            <v-col class="text-center" cols="12">
                {{ new Date().getFullYear() }} — 
                Made with
                <v-icon color="red">mdi-heart</v-icon> 
                by Hamid Yaftian.
            </v-col>
        </v-footer>
    </v-app>
</template>

<script>
    export default {
        name: "App",
    };
</script>
