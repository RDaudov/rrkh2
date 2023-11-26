<template>
  <div>
    <div class="container"> 
      <NuxtLayout>
        <NuxtPage/>
      </NuxtLayout>
    </div>
  </div>
</template>
<style>
.container {
  width: 392px;
  margin: auto;
  height: calc(100vh - 70px);
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