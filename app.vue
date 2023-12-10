<template>
  <div>
    <div class="container"> 
      <NuxtLayout>
        <NuxtPage/>
      </NuxtLayout>
    </div>
  </div>
</template>
<script>
</script>
<style>
@import url('~/public/assets/style.css');
.container {
  width: 390px;
  margin: auto;
  padding: 0 5px;
}

section, form {
  display: flex;
  flex-direction: column;
}

h4 {
    border-bottom: 1px solid grey;
}

a {
    color: black;
    text-decoration: none;
    padding: 0 5px;
}
</style>