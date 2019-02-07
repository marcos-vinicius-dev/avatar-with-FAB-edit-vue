<template>
    <v-card color="white">
        <v-card-text>
            <div class="text-xs-center">
            <v-avatar
              size="90px"
            >
            <img
                src="https://avatars0.githubusercontent.com/u/9064066?v=4&s=460"
                alt="Avatar"
            >
            <v-btn
              absolute
              class="avatar-edit"
              dark
              small
              fab
              color="blue_2"
            >
                <v-icon>edit</v-icon>
            </v-btn>
            </v-avatar>
            </div>
        </v-card-text>
    </v-card>
</template>

<script>
    export default {

    }
</script>
<style>
    .avatar-edit{
        margin-top: 30px;
        margin-left: 40px;
    }
</style>

