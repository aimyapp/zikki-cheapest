<template>
    <div class="rakuten">
        <h2>{{ title }}</h2>
            <div class="rakutenCard" v-for="zikki in zikkiList" :key="zikki.id">
                {{ zikki.name }}
            </div>
    </div>
</template>

<script>
export default {
    data(){
        return {
            title: "楽天市場",
            zikkiList: [
                { id: 1, name: "HANABI"},
                { id: 2, name: "VERSUS"},
                { id: 3, name: "サンダーvリボルト"}
            ]
        }
    }
}
</script>

<style scoped>
.rakuten {
    border: 1px solid gray
}

.rakutenCard {
    display: inline-block;
    
}
</style>