<script setup>
const props = defineProps({developerCount: {type: Number, required: true}});
const {developerCount}=props;
</script>

<template>
<div>
  <p>Developer registered: {{ developerCount }}</p>
  <p><b>Note:</b> Unknown developers are not considered.</p>
</div>
</template>