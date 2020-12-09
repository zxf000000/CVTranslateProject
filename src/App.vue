<template>
  <div id="app">
    <h1>CV翻译</h1>
    <div class="container">
      <div class="input_container">
        <h2 class="text_area_label1">Android</h2>
        <textarea class="from_input1" placeholder="输入安卓待翻译文本">
        </textarea>
        <h2 class="label2">iOS</h2>
        <textarea class="from_input2" placeholder="输入安卓待翻译文本">
        </textarea>
      </div>

      <button class="convert_button button"><p>翻译</p><img class="button_img" src="@/assets/arrow-right.png"></button>

      <div class="output_container">
        <h2 class="output_label1">Android</h2>
        <textarea class="output_text1"></textarea>
        <h2 class="output_label2">iOS</h2>
        <textarea class="output_text2"></textarea>
      </div>

    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

/*.output_container {*/
/*  background: aqua;*/
/*  width: 800px;*/
/*  height: 800px;*/
/*}*/

.output_text1 {
  width: 400px;
  height: 200px;
  resize: none;
}

.output_text2 {
  width: 400px;
  height: 200px;
  resize: none;
}

.button_img {
  width: 20px;
  height: 20px;
}

.button {
  width: 100px;
  height: 30px;
  display: flex;
  align-items: center;
  flex-flow: row;
  justify-content: space-around;
}

.convert_button {
  margin-right: 10px;
}

.container {
  width: 100%;
  height: 800px;
  background: #42b983;
  display: flex;
  flex-flow: row;
  align-items: center;
  justify-content: space-evenly;
}

.input_container output_container {
  display: flex;
  flex-flow: column;
  align-items: flex-start;
  justify-content: flex-start;
  width: 800px;
  height: 800px;
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
