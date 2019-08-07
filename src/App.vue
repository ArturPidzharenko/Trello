<template>
	<div class="container">
        <kanban></kanban>
    </div>
</template>
<script>

import Kanban from './components/Kanban'

	export default {
		data() {
			return {
				
			}
        },
        components: {
            Kanban
        },
	}
</script>

<style scope>
    body {
        background: #33363d!important;      
    }
</style>