<template>
    <div class="card" style="width: 18rem;">

                <div class="card-header">
            <slot name="cardHeader"></slot>
        </div>

        <div class="card-body">
            <slot name="cardBody"></slot>
        </div>

    </div>
</template>

<script>
export default {
    name: "CardS",
    /* props: ["firstName", "lastName", "id"] */

}
</script>

<style>
img {
    width: 200px;
    height: 200px;
}

/* .card {
    width: 4rem;
    padding: 0px;
    background-color: rgb(81, 0, 255);
} */

/* .card-head,
.card-body {
    width: 50%;
    background-color: aqua;
} */
</style>