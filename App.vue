<template>
  <div>
    <svg width=320 height=240 viewBox="0 0 320 240">
      <!-- <defs>
        <symbol id="chip">
          <image href="./chip.png"></image>
        </symbol>
      </defs>
      <use fill="#db8c81" x="16" y="16" width="16" height="16" xlink:href="#chip"></use> -->
      <image
        xlink:href="./chip.png" x=0 y=0 height=16 width=16></image>
    </svg>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  }
};
</script>
<style>
svg{
  background: white;
  -ms-interpolation-mode: nearest-neighbor;
  image-rendering: pixelated;
  width: 640px;
  height: 480px;
}
body{
  background: #eee;
}
image{
  shape-rendering: crispEdges;
}
</style>
