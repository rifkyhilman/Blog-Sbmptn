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
  <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
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
            <div class="col-3 row w-50">
              <div
                class="nav flex-column nav-pills"
                id="v-pills-tab"
                role="tablist"
                aria-orientation="vertical">
                <a
                  class="nav-link active dropdown-item"
                  id="v-pills-home-tab"
                  data-toggle="pill"
                  href="#v-pills-home"
                  role="tab"
                  aria-controls="v-pills-home"
                  aria-selected="true">
                  Home
                </a>
                <a
                  class="nav-link dropdown-item"
                  id="v-pills-profile-tab"
                  data-toggle="pill"
                  href="#v-pills-profile"
                  role="tab"
                  aria-controls="v-pills-profile"
                  aria-selected="false">
                  Profile
                </a>
                <a
                  class="nav-link dropdown-item"
                  id="v-pills-messages-tab"
                  data-toggle="pill"
                  href="#v-pills-messages"
                  role="tab"
                  aria-controls="v-pills-messages"
                  aria-selected="false">
                  Messages
                </a>
                <a
                  class="nav-link dropdown-item"
                  id="v-pills-settings-tab"
                  data-toggle="pill"
                  href="#v-pills-settings"
                  role="tab"
                  aria-controls="v-pills-settings"
                  aria-selected="false">
                  Settings
                </a>
              </div>
            </div>
            <div class="col-3 row">
              <div class="tab-content" id="v-pills-tabContent">
                <div
                  class="tab-pane fade show active"
                  id="kls-7"
                  role="tabpanel"
                  aria-labelledby="v-pills-home-tab">
                  matematika
                </div>
                <div
                  class="tab-pane fade"
                  id="kls-8"
                  role="tabpanel"
                  aria-labelledby="v-pills-profile-tab">
                  matematika
                </div>
                <div
                  class="tab-pane fade"
                  id="kls-9"
                  role="tabpanel"
                  aria-labelledby="v-pills-messages-tab">
                  matematika
                </div>
              </div>
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
            <a class="" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <a class="dropdown-item" href="#">Something else here</a>
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
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <a class="dropdown-item" href="#">Something else here</a>
          </div>
        </li>
        <li class="nav-item m-3">
          <a class="nav-link" href="/blog" use:link>Blog</a>
        </li>
      </ul>
    </div>
  </nav>
</div>
