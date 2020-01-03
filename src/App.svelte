<script>
  import { Router, Link, Route } from "svelte-routing";
  import Navbar from "./components/navbar.svelte";
  import Footer from "./components/footer.svelte";
  import Home from "./page/Home.svelte";
  import Blog from "./page/Blog.svelte";
  export let url = "";
</script>

<Router {url}>
  <Navbar />
  <div class="body">
    <Route path="/blog" component={Blog} />
    <Route path="/" component={Home} />
  </div>
  <Footer />
</Router>
