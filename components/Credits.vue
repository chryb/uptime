<template>
  <div class="credits">
    <div>
      <span>made by</span> <a href="http://chryb.me"> chryb</a>
    </div>
    <div>
      <a href="https://github.com/chryb/uptime">github</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'credits'
}
</script>

<style scoped>
.credits {
  position: absolute;
  right: -40px;
  bottom: 140px;
  transform: rotateZ(90deg);
}

.credits > div {
  color: #555;
  position: relative;
  display: inline-block;
  letter-spacing: 1px;
  margin-right: 20px;
}

.credits span {
  border-bottom: 2px solid #555;
  padding-bottom: 5px;
}

.credits > div a {
  color: #999;
  text-decoration: none;
}

.credits > div a:hover {
  color: #fff;
}
</style>
