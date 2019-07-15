<template>
	<div>
		<model-viewer
			class="viewer"
			src="/assets/tea.glb"
			auto-rotate
			camera-controls
			ar>
		</model-viewer>
	</div>
</template>

<script>
import '@google/model-viewer';
export default {
	name: 'Tea',
};
</script>
