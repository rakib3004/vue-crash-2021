<template>
<header>
    <div :key="task.id" v-for="task in tasks">
    <h3>{{task.text}}</h3>
    </div>
    </header>
</template>

<script>

export default {
  name: 'Tasks',
  props:{
      tasks: Array,
  },
}
</script>
