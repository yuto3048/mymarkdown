<template>
  <div id="home">
    <h1>{{ msg }}</h1>
    <button>login with Google Account</button>
  </div>
</templete>
<script>
export default {
  name: "home",
  data() {
    return {
      msg: "Welcome to MyMarkdown"
    };
  }
};
</script>
