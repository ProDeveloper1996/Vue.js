<template>
    <div id="app_1">
        {{msg}}
        VUE
        <!-- <button v-on: click="reverseMessage">ReverseMessage</button> -->
    </div>
</template>
<script>
// var app1 = new vue({
//     el: "#app_1",
//     data: {
//         message: 'My First Vue'
//     },
//     methods: {
//         reverseMessage: function() {
//             this.message = this.message.split('').reverse('').join('')
//         }
//     }
// })
export default {
    name: 'MyfirstVue',
    // app1,
    props: {
        msg: Object
    }
}
</script>