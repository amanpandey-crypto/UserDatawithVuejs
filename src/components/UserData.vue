<template>
    <p>Add User</p>
    <form @submit.prevent="">
        <div>
            <label>Name</label>
            <input type="text" />
        </div>
        <div>
            <label>Age</label>
            <input type="age" />
        </div>
        <div>
            <button>Add User</button>
        </div>
    </form>
</template>

<script>
export default {
    data() {
        return {
        };
    },
};
</script>
