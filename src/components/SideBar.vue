<template>
    <v-navigation-drawer
        expand-on-hover
        rail
    >
        <v-list>
            <v-list-item
                prepend-avatar="https://lh3.googleusercontent.com/a/AGNmyxaH0xSB_04VJoC5KLblOf52m5P8bf7YTIUsMQyNRw=s288"
                title="Fernando Gonzalez"
                subtitle="fgpaolini@gmailcom"
            ></v-list-item>
            </v-list>

            <v-divider/>

            <v-list density="compact" nav>
                <v-list-item
                    prepend-icon="mdi-image"
                    title="Color Gallery"
                    value="color"
                />
                <v-list-item
                    prepend-icon="mdi-dialpad"
                    title="Greyspace Gallery"
                    value="color"
                />
                <v-list-item
                    prepend-icon="mdi-message-text"
                    title="Message"
                    value="color"
                />
                <v-list-item
                    prepend-icon="mdi-audio-video"
                    title="Message"
                    value="color"
                />
            </v-list>


    </v-navigation-drawer>
</template>