<template>
    <div>
        <h1>{{title}}</h1>
        <ul>

        </ul>
    </div>
</template>

<script>
  export default {
    name: 'Booklist',
    data() {
        return {
            title: 'All Books',
            books: [
              {title: 'Self-Reliance', author: 'Ralph Waldo Emerson'},
              {title: 'American Gods', author: 'Neil Gaiman'},
              {title: 'Amusing Ourselves to Death', author: 'Neil Postman'},]


        }
    }
  }
</script>

<style>



</style>
