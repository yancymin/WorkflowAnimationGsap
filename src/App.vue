<template>
  <div id="app" class="font-sans text-black min-h-screen bg-grey-dark p-24">
    <WorkflowAnimation/>
  </div>
</template>

<script>
import WorkflowAnimation from './components/WorkflowAnimation.vue'

export default {
  name: 'app',
  components: {
    WorkflowAnimation,
  }
}
</script>
