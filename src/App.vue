<template>
    <div class="container">
        <status-header></status-header>
        <hr>
        <div class="row">
            <server-list></server-list>
            <server-details></server-details>
        </div>
        <hr>
        <div class="row">
            <div class="col-xs-12">
                <footer>
                    <p>All Servers are managed here</p>
                </footer>
            </div>
        </div>
    </div>
</template>

<script>
  import Header from './Header.vue';
  import ServerList from './ServerList.vue'
  import ServerDetails from './ServerDetails.vue'
  export default {
    components: {
      'status-header': Header,
      'server-list': ServerList,
      'server-details': ServerDetails,
    }
  }
</script>

<style>

</style>
