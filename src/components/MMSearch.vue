<template>
  <div id="mm-search-div">
    <div id="tools-div">
      <div class="tools">A</div>
      <div class="tools">B</div>
      <div class="tools">C</div>
    </div>
    <div id="input-div">
      <div id="options">
        all
        <img id="arrow-down" src="../assets/arrow-down.png">
      </div>
      <input id="search" placeholder="words or text">
      <img id="clean" src="../assets/close.png">
      <img id="search-ico" src="../assets/search.png">
    </div>
  </div>
</template>

<script>
export default {
  name: 'MMSearch'
}
</script>

<style>

#mm-search-div {
  text-align: left;
  height: 50px;
}

#tools-div {
  display: inline-block;
  width: 8%;
}

.tools {
  display: inline-block;
  font-size: 32px;
}

#input-div {
  display: inline-block;
  background-color: #ffffff;
  border: 4px #dbdbdb solid;
  border-radius: 4px;
  width: 90%;
}

#options {
  display: inline-block;
}

#search{
  height: 36px;
  outline: none;
  border: none;
  font-size: 30px;
  width: 90%;
}

#arrow-down {
  height: 10px;
  width: 10px;
}

#clean {
  height: 24px;
  width: 24px;
}

#search-ico {
  height: 24px;
  width: 24px;
  background-color: #e6e6e6;
}

</style>
