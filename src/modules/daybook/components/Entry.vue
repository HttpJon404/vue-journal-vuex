<template>
  <div class="entry-container mb-3 pointer p-2"
  @click="$router.push({name: 'entry', params: {id:10}})">
    <!-- Titulo -->
    <div class="entry-title d-flex">
      <span class="text-success fs-5 fw-bold">02</span>
      <span class="mx-1 fs-5">Abril</span>
      <span class="mx-2 fw-light">2022</span>
    </div>
    <div class="entry-description">
     <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Magni sunt
      voluptatibus quisquam ipsum minima! Vitae quod nam ab blanditiis
      repudiandae odit, provident, voluptas tempora adipisci optio sint quos
      accusamus quo?
     </p>
    </div>
  </div>



</template>

<style lang="scss" scoped>

.entry-container{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover{
        background-color: lighten($color: gray, $amount: 45);
        transition: 0.2s all ease-in;
    }
    .entry-description{
    font-size: 12px;
}
    
}



</style>



