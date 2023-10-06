<script setup>
import HeaderPart from './components/HeaderPart.vue'
</script>

<template>
  <HeaderPart/>
 

  <div class="mainbd">
    <RouterView />
  </div>
  
  <footer class="d-flex flex-wrap justify-content-between align-items-center py-3 my-4 border-top">
    <div class="col-md-4 d-flex align-items-center">
      <a href="/" class="mb-3 me-2 mb-md-0 text-body-secondary text-decoration-none lh-1">
        <svg class="bi" width="30" height="24"><use xlink:href="#bootstrap"></use></svg>
      </a>
      <span class="mb-3 mb-md-0 text-body-secondary">© Thonthus Prangpetch 6504101343</span>
    </div>

    <ul class="nav col-md-4 justify-content-end list-unstyled d-flex">
      <li class="ms-3"><a class="text-body-secondary" href="https://www.instagram.com/ts_thus.pp/" target="_blank"><img src="@/assets/instagram.png" alt="ig" width="31" height="31"></a></li>
      <li class="ms-3"><a class="text-body-secondary" href="https://facebook.com/thonthus.prangpech/" target="_blank"><img src="@/assets/febe.png" alt="fb" width="30" height="30"></a></li>
    </ul>
  </footer>
</template>

<style scoped>

</style>
