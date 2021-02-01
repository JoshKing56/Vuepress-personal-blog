<template>
<div>
    <p> {{totalVuePackages}} </p>
    <!-- <div v-for="user in get_dummy_profile">
        <p> test </p>
        <p>{{ user }} </p>
    </div> -->
</div>
</template>

<script>
export default {
    // got the code here: https://jasonwatmore.com/post/2020/04/30/vue-fetch-http-get-request-examples
  name: "get-request",
  data() {
    return {
      totalVuePackages: null
    };
  },
//   created() {
//     // Simple GET request using fetch
//     fetch("https://api.npms.io/v2/search?q=vue")
//       .then(response => response.json())
//       .then(data => (this.totalVuePackages = data.total));
//   }
};
</script>
