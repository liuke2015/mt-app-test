<template>
    <div id="index">
      <el-row :gutter="15">
        <el-col :span="6">
          <geo/>
        </el-col>
        <el-col :span="6">
          <user/>
        </el-col>
        <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
      </el-row>
    </div>
</template>

<script>
    import geo from "./geo.vue"
    import user from "./user.vue"
    export default {
        name: "index",
        msg: "",
        data() {
            return {}
        },
       components:{
         geo,
         user
       }
    }
</script>

<style lang="scss">
   @import "@/assets/css/public/layout.scss";
</style>
