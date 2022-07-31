<template>
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark sticky-top">
            <div class="container-fluid">
                <router-link to="/" class="navbar-brand text-light">
                    <img alt="Logo" src="../assets/logo.png" width="45" height="45" class="d-inline-block ">
                    Company X
                    </router-link>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                    aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
                    <ul class="navbar-nav  mb-2 mb-lg-0">
                        <li class="nav-item">
                            <router-link to="/">Home</router-link>
                        </li>
                        <li class="nav-item">
                            <router-link to="/about">About</router-link>
                        </li>
                        <li class="nav-item">
                            <router-link to="/contact">Contact</router-link>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
</template>

<style>
header {
    display: inline;
}

nav {
   background-color: #27AE60;
}

.navbar-brand
{
  font-size: 35px;
  font-weight: bold;
  margin-left: 10px;
}

nav li {
    display: inline;
    list-style-type: none;
    margin-right: 20px;
}

nav li a {
    font-size: 20px;
    font-weight: 400;
    text-decoration: none;
    color: white;
}

nav li a:hover {
    color: white;
    font-weight: bold;
}
</style>