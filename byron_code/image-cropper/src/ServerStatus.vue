<template>
    <div>
      <p>Server Status: {{ status }}</p>
      <hr>
      <button @click="changeStatus">Change Status</button>
    </div>
</template>

// This component is for console purposes, I am not using it for now, dont worry about it ;)

<script>
export default {
  data: function() {
    return {
      status: 'Critical'
    }
  },
  methods: {
    changeStatus() {
      this.status = 'Normal';
    }
  }
}
</script>

