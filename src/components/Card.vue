<template>
    <div class="container">
        <div class="card">
            <div class="card-head">
                <slot name="card-header"></slot>
            </div>

            <div class="card-body">
                <slot name="card-body"></slot>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style></style>