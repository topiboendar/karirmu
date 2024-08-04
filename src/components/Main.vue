<script setup>
    import Hero from '@/components/Hero.vue';

    import jobData from '@/assets/dummy.json';
    import { ref, computed } from 'vue';

    const data = ref(jobData);

    const uniqueCategory = computed(() => {
        return [...new Set(data.value.map(item => item.category))];
    });

</script>
<template>
    <main>
        <Hero />
        <section class="category p-3">
            <h3 class="font-weight-bold text-capitalize text-center py-4">Kategori</h3>
            <div class="col-md-11 col-lg-10 mx-auto">
                <div class="categories d-flex flex-wrap gap-3">
                    <button v-for="category in uniqueCategory" v-bind:key="data.id" class="card main-category py-2 px-4 text-decoration-none btn border-dark">
                        <p class="m-auto text-center">{{ category }}</p>
                    </button>
                </div>
            </div>
        </section>
    </main>
    
</template>
