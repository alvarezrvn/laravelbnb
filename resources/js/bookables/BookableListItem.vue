<template>
    <div class="card">
        <div class="card-body">
            <h5 class="card-title">{{itemTitle}}</h5>
            <p class="card-text">{{itemContent}}</p>
        </div>
    </div>
</template>

<script>
export default {
    props: {"itemTitle" : String, "itemContent" : String,"price" : Number},
    mounted() {
        console.log(this.itemTitle);
        //should neve modify a prop directly
        // this.itemTitle = "New Title"
        // setTimeout(() => {
        //     this.itemTitle = "New Title";
        // }, 1500);
    }
}
</script>

<style>

</style>
