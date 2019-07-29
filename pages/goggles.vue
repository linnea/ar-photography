<template>
	<model-viewer
		class="viewer"
		src="/assets/goggles2.glb"
		auto-rotate
		camera-controls
		ar>
	</model-viewer>
</template>

<script>
import '@google/model-viewer';
export default {
	name: 'Goggles',
};
</script>
