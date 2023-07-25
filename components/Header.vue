<template>
    <header id="main-header">
        <nav>
            <v-container>
                <v-row>
                    <v-col class="shrink">
                        <a href="" id="logo" />
                    </v-col>
                    <v-col class="shrink">
                        <v-btn v-for="item in ['products', 'contact us', 'company', 'resources']"
                            :key="item">Products</v-btn>
                    </v-col>
                </v-row>
            </v-container>
        </nav>
    </header>
</template>

<style lang="scss">
header#main-header {
    nav {
        #logo {}
    }
}
</style>