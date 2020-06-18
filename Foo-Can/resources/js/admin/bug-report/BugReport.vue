<template>
    <div>
        BUG Report Page
    </div>
</template>
<script></script>
export default {
    mounted(){
        console.log("this is bug report page");
        const self = this;

            self.$store.commit('setBreadcrumbs',[
                {label:'Bug Report',name:''}
            ]);
    }
}
</script>