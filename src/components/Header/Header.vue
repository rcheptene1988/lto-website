<template>
    <header>
        <div class="container">
            <div class="row">
                <div class="logo-wrap col col-4">
                    <router-link to="/">
                        <img alt="Vue logo" src="/dist/img/logo.svg">
                    </router-link> 
                </div>
                <div class="nav-wrap col"> 
                    <nav class="nav-main">
                        <li class="nav-item dropdown">
                            <router-link class="aaa" to="/lto">Networks</router-link>
                            <div class="dropdown-content">
                                <router-link  to="/lto">LTO Networks</router-link>
                            </div>
                        </li>
                        <li class="nav-item dropdown">
                            <router-link to="/contact">Contact</router-link>
                        </li>
                    </nav>
                </div>
            </div>
        </div>
    </header>
</template>

<script>

export default {
  name: "Header",
  computed: {},
  methods: {},
};

</script>
