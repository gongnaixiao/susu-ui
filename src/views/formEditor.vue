<script setup>
import { ref, onMounted, getCurrentInstance } from 'vue'
import { erFormEditor } from 'everright-formeditor'
const EReditorRef = ref(null)
</script>
<template>
  <er-form-editor
    ref="EReditorRef"/>
</template>
