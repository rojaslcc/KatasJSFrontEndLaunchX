<template>
    <div class="footer w-100 mt-5">
        <div class="d-flex flex-row justify-content-between">
            <div class="p-5">
                <h2 class="footer-title">Pokédex</h2>
                <p class="footer-text">Katas de JS para LaunchX</p>
                <p class="footer-text">Lic. Jesus Humberto Rojas Rangel</p>
            </div>
        </div>
        <div class="d-flex flex-row justify-content-between mt-5">
            <div class="px-5">
                <h6>2022 ⓒ - Pokédex. All rights reserved</h6>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style>
ul {
    list-style: none;
    padding: 0px 100px;
}

ul li {
    padding: 5px 0px;
    color: #6d7b93;
}

.footer {
    height: 20em;
    background-color: #eef3ff;
}

.footer-title {
    color: #3050cd;
    font-size: 2em;
    font-weight: bold;
}

.footer-text {
    color: #6d7b93;
}

.list-title {
    padding: 15px 0px;
    color: #1f3e72;
    font-size: 1.5em;
    font-weight: bold;
}
</style>