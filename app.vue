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
@import url('~/public/assets/index.scss');

/* @media (min-width: 768px) { 
  .container {
    width: 768px;
  }
}

@media (min-width: 992px) { 
  .container {
    width: 1240px;
  }
} */

section, form {
  display: flex;
  flex-direction: column;
}

a {
    color: black;
    text-decoration: none;
    padding: 0 5px;
}
</style>
