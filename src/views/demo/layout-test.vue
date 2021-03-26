<!-- 布局测试组件 -->
<template>
  <div class="layout-test">
    <!-- <span class="fixed-top">超长时出现下拉条，这句话相对父元素固定在顶部</span> -->
    <span class="fixed-top">敬请期待</span>
    <!-- <ul>
      <li v-for="i in 100">数据{{i}}</li>
    </ul> -->
    <!-- <p>敬请期待</p> -->
  </div>
</template>

<script>
export default {
  name: "test",
  components: {},
  data() {
    return {};
  },
  props: {},
  computed: {},
  methods: {},
  watch: {},
  created() {}
};
</script>

<style lang="less" scoped>
.layout-test {
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
  .fixed-top {
    position: fixed; /*固定作用*/
    margin: 0 auto;
  }
}
</style>