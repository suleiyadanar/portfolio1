<template>
  <div class="container-fluid" style="width: 100%; height: 100%">
    <!-- <nav>
			<NuxtLink to="/">Home</NuxtLink>
			<NuxtLink to="/about">About</NuxtLink>
		</nav> -->
    <NuxtPage />
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
$bg-light: #e3c0c0;
$bg-dark: #817091;

* {
  background-image: linear-gradient($bg-light, $bg-dark);
}
</style>
