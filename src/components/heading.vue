<script>
export default {
    name:'heading',
    props:{
        level:{
            type:Number,
            required:true
        }
    },
    render(h){
        return h(
            'h'+this.level,
            this.$slots.default
        )
    }
}
</script>

<style>

</style>