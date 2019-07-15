<template>
	<div>
		<model-viewer
			class="viewer"
			src="/assets/freshhat.gltf"
			auto-rotate
			camera-controls
			ar>
		</model-viewer>
	</div>
</template>

<script>
import '@google/model-viewer';
export default {
	name: 'Hat',
};
</script>
