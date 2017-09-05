<template>
    <div class="container">
        <status-header></status-header>
        <hr>
        <div class="row">
            <server-list></server-list>
            <div class="col-xs-12 col-sm-6">
                <p>Server Details are currently not updated</p>
            </div>
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
  export default {
    components: {
      'status-header': Header,
      'server-list': ServerList,
    }
  }
</script>

<style>

</style>
