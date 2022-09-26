<template>
  <div>

  </div>
</template>

<script>
import node from 'node.vue'
export default {
    name:'tree',
    components:{
        node
    },
    props:{
        showCheckbox:{
            type:Boolean,
            default:false
        }
    },
    data(){
        return {
            data:{
                    title: 'parent 1',
                    expand: true,
                    children: [
                    {
                        title: 'parent 1-1',
                        expand: true,
                        children: [
                        {
                            title: 'leaf 1-1-1'
                        },
                        {
                            title: 'leaf 1-1-2'
                        }
                        ]
                    },
                    {
                        title: 'parent 1-2',
                        children: [
                        {
                            title: 'leaf 1-2-1'
                        },
                        {
                            title: 'leaf 1-2-1'
                        }
                        ]
                    }
                    ]
            }
        }
    },
    methods:{
        ontoggleexpand(){}
    }
}
</script>

<style>

</style>