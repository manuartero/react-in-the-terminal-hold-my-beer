<template>
  <div :style="boxStyle"></div>
</template>

<script>
export default {
  props: {
    x1: {
      type: Number,
      required: true,
    },
    y1: {
      type: Number,
      required: true,
    },
    x2: {
      type: Number,
      required: true,
    },
    y2: {
      type: Number,
      required: true,
    },
    color: {
      type: String,
      default: "green", // Default color is green
    },
    width: {
      type: Number,
      default: 2, // Default width is 2
    },
  },
  computed: {
    boxStyle() {
      return {
        position: "absolute",
        left: `${this.x1}px`,
        top: `${this.y1}px`,
        width: `${this.x2 - this.x1}px`,
        height: `${this.y2 - this.y1}px`,
        border: `${this.width}px solid ${this.color}`,
      };
    },
  },
};
</script>
