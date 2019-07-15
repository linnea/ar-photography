<template>
	<div>
		<model-viewer
			class="viewer"
			src="assets/t2.glb"
			auto-rotate
			camera-controls
			ar>
		</model-viewer>
	</div>
</template>

<script>
import '@google/model-viewer';
export default {
	name: 'T2',
};
</script>
