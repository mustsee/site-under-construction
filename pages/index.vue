<template>
    <div class="wrapper">
        <div class="title">
            site en construction
        </div>
    </div>
</template>

<style lang="scss">
    .wrapper {
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        .title {
            text-transform: uppercase;
            font-size: 25px;
            font-weight: 200;
            @media (min-width: 768px) {
                font-weight: 100;
                font-size: 50px;
            }
        }
    }

</style>
