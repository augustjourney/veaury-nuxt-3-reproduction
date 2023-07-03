<template>
	<div>
		Hello world
		<TestReactComponent />
	</div>
</template>
<script>
import TestReactComponent from './test-react-component.jsx'
import { applyReactInVue } from 'veaury'
export default {
	components: {
		TestReactComponent: applyReactInVue(TestReactComponent),
	},
}
</script>
