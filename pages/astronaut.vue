<template>
	<model-viewer
		class="viewer"
		src="/assets/astrobaut.glb"
		auto-rotate
		camera-controls
		ar>
	</model-viewer>
</template>

<script>
import '@google/model-viewer';
export default {
	name: 'Astronaut',
};
</script>
