<script setup>
import Navbar from '@/components/Navbar.vue'
import Main from '@/components/Main.vue'
import Footer from '@/components/Footer.vue'
</script>

<template>
    <!-- Modal -->
    <div class="modal fade show" id="signInModal" tabindex="-1" aria-labelledby="signInModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered">
        <div class="modal-content">
        <div class="modal-header">
            <h1 class="modal-title fs-5" id="exampleModalLabel">Login KarirMu</h1>
            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
            <form>
                <div class="mb-3">
                    <label for="exampleInputEmail1" class="form-label">Email address</label>
                    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                </div>
                <div class="mb-3">
                    <label for="exampleInputPassword1" class="form-label">Password</label>
                    <input type="password" class="form-control" id="exampleInputPassword1">
                </div>
                <div class="form-text"><a class="text-decoration-none" href="#">Lupa kata sandi ?</a></div>
            </form>
        </div>
        <div class="modal-footer">
            <!-- <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button> -->
            <button type="button" class="btn btn-primary w-100">Login</button>
        </div>
        </div>
    </div>
    </div>

    <Navbar />
    <Main />
    <Footer />
</template>

<style scoped>

</style>
