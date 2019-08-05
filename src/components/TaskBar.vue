<template>
        
</template>

<script>
    import { mapState } from 'vuex';
    import { mapMutations } from 'vuex';
    import { mapActions } from 'vuex';

    import TaskBar from './TaskBar'

	export default {
        name: 'home',
		data() {
			return {
                
			}
        },
        components: {
            TaskBar
        },
        computed: {
            ...mapState([
                
            ]),
            
        },
		methods: {
            ...mapMutations([
               
            ]),
            ...mapActions([
               
            ])
		}
    }	
</script>

<style scope>
    
</style>
