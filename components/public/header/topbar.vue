<template>
    <div id="index">
      <el-row :gutter="0" class="m-header">
        <el-col :span="5">
          <geo/>
        </el-col>
        <el-col :span="5">
          <user/>
        </el-col>
        <el-col :span="14" class="m-nav">
          <navbar/>
        </el-col>
      </el-row>
    </div>
</template>

<script>
    import geo from "./geo.vue"
    import user from "./user.vue"
    import navbar from "./nav.vue"
    export default {
        name: "index",
        msg: "",
        data() {
            return {}
        },
       components:{
         geo,
         user,
         navbar
       }
    }
</script>

<style lang="scss">
  @import "@/assets/css/public/layout.scss";
  @import "@/assets/css/public/header/index.scss";
</style>
