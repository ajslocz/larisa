<script>
  import "./app.css";
  import Sidebar from "./lib/Sidebar.svelte";
  import Navbar from "./lib/Navbar.svelte";
  import Footer from "./lib/Footer.svelte";
  import Main from "./lib/Main.svelte";
</script>

<div class="wrapper">
  <div class="left">
    <Sidebar />
  </div>
  <div class="right">
    <Navbar />
    <Main />
    <Footer />
  </div>
</div>

<style>
  .wrapper {
    display: flex;
  }
  .left {
    width: 115px;
  }
  .right {
    flex: 1;
  }
</style>
