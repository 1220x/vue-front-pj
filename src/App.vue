<template>
	<div id="project_frame">
		<div class="color-red"></div>

    	<router-view/>
  	</div>
</template>

<script>
export default {
	name: 'App'
}
</script>

<style>

/* @import './style/common.scss'; */

* {
	margin: 0;
	padding: 0;
}

#project_frame {
	width: 100%;
	height: 100%;
}

</style>
