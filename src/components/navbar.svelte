<script>
  import { link } from "svelte-routing";
</script>

<style>
  .brand {
    font-family: "Ma Shan Zheng", cursive;
    font-family: "Girassol", cursive;
  }

  .dropdown:hover > .dropdown-menu {
    display: block;
  }
</style>

<div>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <a class="navbar-brand" href="/" use:link>
      <h1 class="brand">Ribook</h1>
    </a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNavDropdown"
      aria-controls="navbarNavDropdown"
      aria-expanded="false"
      aria-label="Toggle navigation">
      <span class="navbar-toggler-icon" />
    </button>
    <div
      class="collapse navbar-collapse d-flex justify-content-end"
      id="navbarNavDropdown">
      <ul class="navbar-nav">
        <li class="nav-item dropdown m-3">
          <a
            class="nav-link dropdown-toggle"
            href="#"
            id="navbarDropdownMenuLink"
            role="button"
            data-toggle="dropdown"
            aria-haspopup="true"
            aria-expanded="false">
            SMP
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
            <p>
              <a
                class="btn btn-primary dropdown-item"
                data-toggle="collapse"
                href="#collapseExample"
                role="button">
                kelas 7
              </a>
            </p>
            <div class="collapse" id="collapseExample">
              <div class="card card-body">Anim pariatur</div>
            </div>
            <p>
              <a
                class="btn btn-primary dropdown-item"
                data-toggle="collapse"
                href="#collapses"
                role="button">
                kelas 8
              </a>
            </p>
            <div class="collapse" id="collapses">
              <div class="card card-body">Anim pariatur</div>
            </div>
            <p>
              <a
                class="btn btn-primary dropdown-item"
                data-toggle="collapse"
                href="#collapse3"
                role="button">
                kelas 9
              </a>
            </p>
            <div class="collapse" id="collapse3">
              <div class="card card-body">Anim pariatur</div>
            </div>
          </div>
        </li>
        <li class="nav-item dropdown m-3">
          <a
            class="nav-link dropdown-toggle"
            href="#"
            id="navbarDropdownMenuLink"
            role="button"
            data-toggle="dropdown"
            aria-haspopup="true"
            aria-expanded="false">
            SMA
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
            <p>
              <a
                class="btn btn-primary dropdown-item"
                data-toggle="collapse"
                href="#collapseExample"
                role="button">
                kelas 10
              </a>
            </p>
            <div class="collapse" id="collapseExample">
              <div class="card card-body">Anim pariatur</div>
            </div>
            <p>
              <a
                class="btn btn-primary dropdown-item"
                data-toggle="collapse"
                href="#collapses"
                role="button">
                kelas 11
              </a>
            </p>
            <div class="collapse" id="collapses">
              <div class="card card-body">Anim pariatur</div>
            </div>
            <p>
              <a
                class="btn btn-primary dropdown-item"
                data-toggle="collapse"
                href="#collapse3"
                role="button">
                kelas 12
              </a>
            </p>
            <div class="collapse" id="collapse3">
              <div class="card card-body">Anim pariatur</div>
            </div>
          </div>
        </li>
        <li class="nav-item dropdown m-3">
          <a
            class="nav-link dropdown-toggle"
            href="#"
            id="navbarDropdownMenuLink"
            role="button"
            data-toggle="dropdown"
            aria-haspopup="true"
            aria-expanded="false">
            UTBK
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
            <p>
              <a
                class="btn btn-primary dropdown-item"
                data-toggle="collapse"
                href="#collapseExample"
                role="button">
                Soshum UTBK
              </a>
            </p>
            <div class="collapse" id="collapseExample">
              <a href="/mtksoshum" class="card card-body" use:link>
                MTK soshum
              </a>
              <a href="/ekonomi" class="card card-body" use:link>
                Ekonomi soshum
              </a>
            </div>
            <p>
              <a
                class="btn btn-primary dropdown-item"
                data-toggle="collapse"
                href="#collapses"
                role="button">
                Saintek UTBK
              </a>
            </p>
            <div class="collapse" id="collapses">
              <a href="/mtksaintek" class="card card-body" use:link>
                MTK-IPA saintek
              </a>
            </div>
          </div>
        </li>
        <li class="nav-item m-3">
          <a class="nav-link" href="/blog" use:link>Blog</a>
        </li>
      </ul>
    </div>
  </nav>
</div>
