<template>
    <div>
        <h1>{{title}}</h1>
        <ul>
            <li>eerste boek</li>
            <li>nog veel mooier boek</li>
            <li>laatste boek</li>
        </ul>
    </div>
</template>

<script>
  export default {
    name: 'Booklist',
    data() {
        return {
            title: 'All Books'
        }
    }
  }
</script>

<style>
h1, h2 {
    font-weight: normal
}
</style>
