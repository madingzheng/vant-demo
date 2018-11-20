<template>
  <div>
    <button @click="handlePopp">弹出Popup</button>
    <van-popup class="popup" v-model="show" position="bottom">
      <input class="input" placeholder="在这里输入笔记的标签（*必填）">
      <p class="font">课程内容</p>
      <textarea class="textare" placeholder="在这里复制你粘贴的笔记吧（*必填）"></textarea>
      <p class="font">课程感悟</p>
      <textarea class="textare" placeholder="在这里写下你的心得吧（*选填）"></textarea>
      <button class="btn-sure">确定</button>
    </van-popup>
  </div>
</template>
<script>
export default {
  name: 'Popup',
  data () {
    return {
      show: false
    }
  },
  methods: {
    handlePopp () {
      this.show = true
    }
  }
}
</script>
<style lang="less">
.popup {
  border-radius: 15px 15px 0 0;

  .btn-sure {
    width: 348px;
    height: 44px;
    background-color: #437dff;
    color: #fff;
    margin-bottom: 20px;
  }
  .font {
    color: #333;
    float: left;
    margin-left: 25px;
  }
  .textare {
    width: 321px;
    height: 155px;
  }
  .input {
    width: 321px;
    height: 33px;
    margin-top: 30px;
  }
}
</style>

