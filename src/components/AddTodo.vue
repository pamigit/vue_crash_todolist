<template>
    <div>
        <form>
            <input v-model="title" type="text" name="title" placeholder="Add title..">
            <input type="submit" value="Submit" class="btn btn-success">
        </form>
    </div>
</template>

<script>
export default {
    name: "AddTodo",
    data() {
        return {
            title: ''
        }
    }
}
</script>

<style scoped>
    form {
        display: flex;
    }
    input[type="text"] {
        flex: 10;
        padding: 5px;
    }
    input[type="submit"] {
        flex: 2;
    }
</style>