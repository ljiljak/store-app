<template>
    <div>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <router-link class="navbar-brand" to="/">Joe's General Store</router-link>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
               <li class="nav-item active">
                <router-link class="nav-link" to="/customers">Customers</router-link>
                </li>
                <li class="nav-item">
                <router-link class="nav-link" to="/products">Products</router-link>
                </li>
            </ul>
      </div>
        </nav>
    </div>
</template>

<script>
    export default {

    }
</script>