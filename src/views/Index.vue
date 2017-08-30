<template>
	<div> memory leak demo</div>
</template>

<script>

  import Vue from 'vue';

  let MyPlugin = {
    install(Vue, options) {
    	// do something
    }
  };
  Vue.use(MyPlugin);
  export default {
		data() {
			return {}
		}
	}
</script>
