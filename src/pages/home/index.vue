<template>

  <div class="container">
      <h1>CV翻译</h1>
    <div class="input1">
      <h2 class="text_area_label1">Android</h2>
      <textarea class="from_input1" placeholder="输入安卓待翻译文本">

      </textarea>

      <h2 class="label2">iOS</h2>
      <textarea class="from_input2" placeholder="输入安卓待翻译文本">

      </textarea>
    </div>
  </div>
</template>

<script>
export default {
  name: "index",
}
</script>

<style scoped>

  .container {
    width: 100%;
    width: 800px;
    background: #42b983;
  }

  .input1 {
    display: flex;
    flex-flow: column;
    align-items: start;
  }

  .text_area_label1 {
    margin-left: 20px;
  }
  .label2 {
    margin-left: 20px;
  }


  .from_input1 {
    width: 400px;
    height: 200px;
    resize: none;
  }
  .from_input2 {
    width: 400px;
    height: 200px;
    resize: none;
  }


</style>