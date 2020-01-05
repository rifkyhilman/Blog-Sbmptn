<script>
  import { Router, Link, Route } from "svelte-routing";
  import Navbar from "./components/navbar.svelte";
  import Footer from "./components/footer.svelte";
  import Home from "./page/Home.svelte";
  import Blog from "./page/Blog.svelte";
  import Mtksoshum from "./page/Mtksoshum.svelte";
  import Mtksaintek from "./page/Mtksaintek.svelte";
  export let url = "";
</script>

<Router {url}>
  <Navbar />
  <div class="body">
    <Route path="/blog" component={Blog} />
    <Route path="/" component={Home} />
    <Route path="/mtksoshum" component={Mtksoshum} />
    <Route path="/mtksaintek" component={Mtksaintek} />
  </div>
  <Footer />
</Router>
