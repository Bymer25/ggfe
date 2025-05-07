<template>
    <div>
      <h1>{{ part.title }}</h1>
      <div>{{ part.description }}</div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Partinfo',
    data() {
      return {
        part: {
          title: "НАЗВАНИЕ",
          description: "ОПИСАНИЕ",
        }
      }
    }
  }
  </script>
  