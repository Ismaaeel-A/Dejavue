<template>
    <div class="row gap-2">
        <h1>FRIENDS</h1>
    </div>
    <div class="row gap-2 justify-content-center">
        <Card v-for="(friend, id) in friends" :key="id">
            <template #cardHeader>
                <img class="img-fluid" :src="friend.profile" :alt="friend.firstName" loading="lazy">
            </template>
    
            <template #cardBody>
                <p>{{ friend.firstName }} </p>
                <p>{{ friend.lastName }}</p>
            </template>
        </Card>
    </div>
</template>

<script>
import Card from '../components/Card.vue'

export default {
    name: 'FriendS',
    components: { Card },

    data() {
        return {
            friends: [{
                firstName: "bobo",
                lastName: "bagins",
                id: "0404245325083",
                profile: "https://cdn.motor1.com/images/mgl/mrz1e/s1/coolest-cars-feature.webp"

            },

            {
                firstName: "bobo",
                lastName: "bagins",
                id: "0404245325083",
                profile: "https://cdn.motor1.com/images/mgl/mrz1e/s1/coolest-cars-feature.webp"

            },

            {
                firstName: "bobo",
                lastName: "bagins",
                id: "0404245325083",
                profile: "https://cdn.motor1.com/images/mgl/mrz1e/s1/coolest-cars-feature.webp"

            },

            {
                firstName: "bobo",
                lastName: "bagins",
                id: "0404245325083",
                profile: "https://cdn.motor1.com/images/mgl/mrz1e/s1/coolest-cars-feature.webp"

            },

            {
                firstName: "bobo",
                lastName: "bagins",
                id: "0404245325083",
                profile: "https://cdn.motor1.com/images/mgl/mrz1e/s1/coolest-cars-feature.webp"

            },

            {
                firstName: "bobo",
                lastName: "bagins",
                id: "0404245325083",
                profile: "https://cdn.motor1.com/images/mgl/mrz1e/s1/coolest-cars-feature.webp"

            },

            {
                firstName: "bobo",
                lastName: "bagins",
                id: "0404245325083",
                profile: "https://cdn.motor1.com/images/mgl/mrz1e/s1/coolest-cars-feature.webp"

            },

            {
                firstName: "bobo",
                lastName: "bagins",
                id: "0404245325083",
                profile: "https://cdn.motor1.com/images/mgl/mrz1e/s1/coolest-cars-feature.webp"

            }]
        }
    }
}
</script>

<style></style>