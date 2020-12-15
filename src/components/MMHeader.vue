<template>
  <div id="mm-header">
    <div id="logo-div">
      <img id="logo" alt="Memo logo" src="../assets/logo4.png">
      <div id="logo-text">MeMo</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MMHeader'
}
</script>

<style>
#logo-div {
  width: 400px;
  text-align: left;
}

#logo {
  height: 100px;
  width: 100px;
  vertical-align: -12px;
}

#logo-text {
  display: inline-block;
  font-size: 45px;
  font-weight: bold;
}
</style>
