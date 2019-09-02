<template>
        <div id='footer' >
                <span>Written by {{this.author}}</span>
        </div>
</template>

<script>
export default {
   
    data() {
        return {
            author:'liang'
        }
    }

}
    

</script>


<style lang="stylus" scoped>
#footer
    text-align center
    color #fff
    font-size 10px
    margin-top 40px
</style>