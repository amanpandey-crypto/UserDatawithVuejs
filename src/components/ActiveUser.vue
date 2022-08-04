<template>
    <ul>
        <li>
            <strong>Name: </strong>
            {{ name }}<br><br>
            <strong>Age: </strong>{{ age }}
        </li>
    </ul>
</template>

<script>
export default {
    props: {
        id: {
            type: String,
            required: true
        },
        name: {
            type: String,
            required: true,
        },
        age: {
            type: String,
            required: true,
        },
    },
    data() {
        return {

        };
    },
};
</script>
