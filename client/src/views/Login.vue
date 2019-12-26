<template>
  <div class="login container-fluid">
    <form @submit.prevent="login">
      <input type="text" placeholder="Enter your name..." />
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "login",
  components: {}
};
</script>
