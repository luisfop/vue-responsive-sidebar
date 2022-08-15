<template>
  <aside>
      SIDEBAR
  </aside>
</template>

<script setup>

</script>

<style lang="scss" scoped>

aside{
  display: flex;
  flex-direction: column;
  width: var(--sidebar-width);
  min-height: 100vh;
  overflow: hidden;
  padding: 1rem;
  transition: 0.2 ease-out ;

  background-color: var(--dark);
  color: var(--light);

  @media(max-width: 768px){
    position: fixed;
    z-index: 99;
  }
}
</style>