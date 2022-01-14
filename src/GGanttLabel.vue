<template>
	<div class="g-gantt-label">
		<slot
			name="label"
			:label="label"
		>
			{{label || ""}}
		</slot>
	</div>
</template>

<script>

export default {
	name: "GGanttLabel",
	props: {
		label: { type: String },
	},
}
</script>
