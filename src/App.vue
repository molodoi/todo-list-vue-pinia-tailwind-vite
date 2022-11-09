<script setup>
import TaskList from './components/TaskList.vue';
import TaskForm from './components/TaskForm.vue'
import TaskStats from './components/TaskStats.vue'
</script>

<template>
  <div class="min-h-screen md:flex">
    <div class="w-full md:w-3/5 bg-slate-200 py-20">
      <div class="w-4/5 mx-auto">
        <task-stats />
        <task-list/>
      </div>
    </div>
    <div class="w-full md:w-2/5 bg-white py-10">
      <task-form />
    </div>
  </div>
</template>

<style>

</style>
