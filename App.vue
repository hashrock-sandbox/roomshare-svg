<template>
  <div>
    <svg width="320" height="240" viewBox="0 0 320 240">
      <defs>
        <symbol id="chip">
          <image :xlink:href="chip" x="0" y="0" height="16" width="16" />
        </symbol>
      </defs>
      <use x="0" y="0" xlink:href="#chip" />
    </svg>
  </div>
</template>
<script>
const asset01 =
  "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAAAXNSR0IArs4c6QAAAGdJREFUOI2l07kRgDAMBdEVQx1uDGqAWtyDG4NGIPNw+JBk5W9/JAEuBm4GWLbDDFMMiAiTZzXFwLqfAPbAE5sDX2wKlLA6UMOqQAt3Az3cDGhwNaDFxYAF/wJW/Ap4cA54MYAw+M43+rMsH0nhAQwAAAAASUVORK5CYII=";

export default {
  data() {
    return {
      chip: asset01
    };
  }
};
</script>
<style>
svg {
  background: white;
  image-rendering: pixelated;
  width: 640px;
  height: 480px;
}
body {
  background: #eee;
}
image {
  shape-rendering: crispEdges;
}
</style>
