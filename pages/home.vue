<template>
    <div>
        <h1>Home</h1>
        <Cards id="1" width="200"/> <Cards id="2" width="300"/><Cards id="3" width="400"/><Cards id="4" width="600"/>
    </div>
</template>

<script>
import Cards from './../components/Cards'
export default {
    components:{Cards},
    layout:'login'
}

</script>