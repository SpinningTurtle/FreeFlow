<template>
    <div>
        <h1>Welcome to FreeFlow</h1>
    </div>

    <div class="color-mode-box">
    <select v-model="$colorMode.preference">
      <option value="system">System</option>
      <option value="light">Light</option>
      <option value="dark">Dark</option>
    </select>
  </div>
</template>

<script setup>
const colorMode = useColorMode()

console.log(colorMode.preference)
</script>