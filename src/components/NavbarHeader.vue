<template>
  <div>
    <div>
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
          <div class="nav-img">
            <img src="../assets/herbal.png" class="card-img-top" alt="..." />
          </div>
          <button
            class="navbar-toggler"
            type="button"
            data-toggle="collapse"
            data-target="#navbarText"
            aria-controls="navbarText"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarText">
            <ul class="navbar-nav ml-auto">
              <li class="nav-item active">
                <router-link to="/" class="nav-link active">HOME</router-link>
              </li>

              <li class="nav-item">
                <router-link to="/shop" class="nav-link">SHOP</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/about" class="nav-link">ABOUT</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/faq" class="nav-link">FAQ</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/contact" class="nav-link"
                  >CONTACT</router-link
                >
              </li>
              <li class="slide"></li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
/*
nav ul li:hover{
  background-color: #b2bbb2;

} */
/* ul li.active {
  background-color: #b2bbb2;
  
} */

.navbar-nav {
  border-radius: 180px;
}
.nav-item {
  font-size: 14px;
}

@media (max-width: 570px) {
  .navbar {
    overflow-x: hidden;
  }
  .nav-img {
    width: 150px;
  }
  .card-img-top {
    width: 180px;
  }
  .navbar-nav {
    float: left;
    text-align: left;
  }
  .nav-item {
    font-size: 12px;
  }
}
</style>
