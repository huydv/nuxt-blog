<template>
  <div>
    <h1>{{ $route.params.id }}</h1>
    <NuxtLink to="/users">Back to Users</NuxtLink>
  </div>
</template>
<script>
export default {
  validate ({ params }) {
    return /^\d+$/.test(params.id);
  }
}
</script>
