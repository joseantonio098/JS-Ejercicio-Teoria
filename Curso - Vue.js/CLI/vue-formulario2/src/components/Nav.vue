<template>
  <!-- Menú style Bootstrap -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
        <a class="navbar-brand" href="#">DIWPROG</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll" aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarScroll">
        <ul class="navbar-nav me-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">
            <li class="nav-item">
                <router-link to="/" class="nav-link" aria-current="page">
                    Home
                </router-link>
            </li>
            <li class="nav-item">
                <router-link to="/about" class="nav-link" aria-current="page">
                    About
                </router-link>
            </li>
            <li class="nav-item">
                <router-link to="/setting" class="nav-link" aria-current="page">
                    Setting
                </router-link>
            </li>
            <li class="nav-item">
                <router-link to="/blog" class="nav-link" aria-current="page">
                    Blog
                </router-link>
            </li>
        </ul>
        <form class="d-flex">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
        </form>
        </div>
    </div>
  </nav>
</template>

<script>
export default {

}
</script>
