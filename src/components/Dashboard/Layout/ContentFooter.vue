<template>
  <footer class="footer">
    <div class="container-fluid">
      <nav class="pull-left">
        <ul>
          <li>
            <router-link :to="{path:'/admin'}">Dashboard</router-link>
          </li>
        </ul>
      </nav>
      <div class="copyright pull-right">
        &copy; Coded with
        <i class="fa fa-heart heart"></i> by
        <a href="https://github.com/blimps/web" target="_blank"> Blimp</a>
      </div>
    </div>
  </footer>
</template>
<script>
  export default {}
</script>
<style>

</style>
