<template>
    <div class="container">
        <div class="top">{{msg}}</div>
    </div>
</template>
<script>
export default {
    data() {
        return {
            msg: '我是预览内容预览内容'
        }
    },
    created() {
        document.querySelector('title').innerText = '我是预览内容'
    }
}
</script>
