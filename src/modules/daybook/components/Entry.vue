<template>
  <div 
    class="entry-container mb-3 pointer p-2"
    @click="$router.push({name:'entry', params:{id:10}})">
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">15</span>
        <span class="mx-1 fs-5">Marzo</span>
        <span class="mx-2 fw-light" >2024, Jueves</span>
    </div>
    <div class="entry-description">
        Reprehenderit irure aliqua laboris velit eiusmod exercitation minim eiusmod velit anim.
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover{
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }

    .enttry-description{
        font-size: 12px;
    }
}
</style>