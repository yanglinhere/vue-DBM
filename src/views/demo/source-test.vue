<!-- 布局测试组件 -->
<template>
  <div class="layout-source">
   <el-form ref="form" :model="form" label-width="80px">
  <el-form-item label="颜色">
    <el-input v-model="form.color" style="width:100px"></el-input>
  </el-form-item>
  <el-form-item label="形态">
    <el-input v-model="form.region" style="width:100px"></el-input>
  </el-form-item>
  <el-form-item label="气味">
    <el-input v-model="form.smell" style="width:100px"></el-input>
  </el-form-item>
  <el-form-item label="pH">
    <el-input v-model="form.ph" style="width:100px"></el-input>
  </el-form-item>
  <el-form-item label="含水率">
    <el-input v-model="form.water" style="width:100px"></el-input>
  </el-form-item>
  <el-form-item label="挥发分含量">
    <el-input v-model="form.huifa" style="width:100px"></el-input>
  </el-form-item>
  <el-form-item label="灰分含量">
    <el-input v-model="form.huifen" style="width:100px"></el-input>
  </el-form-item>
  <el-form-item label="其他参数...">
    <el-button @click="dialogFormVisible = false" >查询类别</el-button>
  </el-form-item>
   
</el-form>
  </div>
</template>

<script>
export default {
  name: "source",
  components: {},
  data() {
    return {
        form: {
          color: '',
          region: '',
          smell: '',
          ph: '',
          water:'',
          huifa:'',
          huifen:''
        }
      }
  },
  props: {},
  computed: {},
  methods: {},
  watch: {},
  created() {}
};
</script>

<style lang="less" scoped>
.layout-source {
  text-align: left;
  padding: 16px;
  span {
    font-size: 18px;
  }
  ul {
    padding-top: 20px;
  }
  li {
    text-align: left;
  }

}
</style>