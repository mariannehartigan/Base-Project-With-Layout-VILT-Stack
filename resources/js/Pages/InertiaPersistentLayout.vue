<template>
  <div class="header">
    <Header />
  </div>
  
  <div class="column1"></div>

	<div class="column2">
	  <slot>Default</slot>
	</div>

  <div class="column3"></div>
  
  <div class="footer"></div>
</template>

<script setup>
import Header from '../Pages/Header.vue'
</script>