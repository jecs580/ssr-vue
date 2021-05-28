<template>
    <div>
        <p>{{id}} - {{title}}</p>
    </div>
</template>
<script>
export default {
    name:'Post',
    props:['id','title']
}
</script>