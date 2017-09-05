<template>
    <div class="container">
        <status-header></status-header>
        <hr>
        <div class="row">
            <server-list></server-list>
            <server-details></server-details>
        </div>
        <hr>
        <status-footer></status-footer>
    </div>
</template>

<script>
  import Header from './Header.vue';
  import ServerList from './ServerList.vue';
  import ServerDetails from './ServerDetails.vue';
  import Footer from './Footer.vue'
  export default {
    components: {
      'status-header': Header,
      'server-list': ServerList,
      'server-details': ServerDetails,
      'status-footer': Footer
    }
  }
</script>

<style>

</style>
