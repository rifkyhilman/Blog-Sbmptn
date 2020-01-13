<script>
  import { link } from "svelte-routing";
</script>

<style>
  h1 {
    font-family: "Ma Shan Zheng", cursive;
    font-family: "Girassol", cursive;
    font-size: 80px;
    color: whitesmoke;
  }

  a {
    color: whitesmoke;
  }
</style>

<div class="h-50 p-5 bg-secondary text-white">
  <div class="container mt-2">
    <div class="row">
      <div class="col text-center">
        <a class="navbar-brand" href="/">
          <h1>Ribook</h1>
        </a>
      </div>
      <div class="col text-center mt-2">
        <h2>About</h2>
        <ul class="nav flex-column">
          <li class="nav-item">
            <a class="nav-link" href="/blog" use:link>Blog</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Sbmptn</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Ujian Nasional</a>
          </li>
        </ul>
      </div>
      <div class="col text-center mt-2">
        <h2>Contact</h2>
        <ul class="nav flex-column">
          <li class="nav-item">
            <a class="nav-link active" href="#">Whatshapp</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Instagram</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Gmail</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</div>
