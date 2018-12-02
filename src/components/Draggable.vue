<template>
    <div>
    <div>
</template>

<script>
export default {
    props:{
       resizeHorizontal:{
           type:Boolean,
       },
       resizeVertical:{
           type:Boolean,
       },
       scale:{
           type:Number,
       },
       onResize:{
           type:Function
       },
       onResizeStart:{
           type:Function
       },
       getSize:{
           type:Function
       }

    }
}
</script>

<style>

</style>

