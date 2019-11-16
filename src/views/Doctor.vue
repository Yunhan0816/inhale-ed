<template>
	<div>
	<Chart :d="d" />
</div>
</template>

<script>

import Chart from '../components/Chart'
export default{
	name: "Doctor",
	components: {
		Chart
	},
	data(){
		return {
			d: [0, 2, 5, 9, 5, 10, 3, 5, -4, -10, 1, 8, 2, 9, 0]
		}
	}
}
</script>