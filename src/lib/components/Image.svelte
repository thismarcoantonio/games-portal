<div class="image">
  <img src={src} alt={alt} class="imageContent" />
</div>

<script lang="ts">
export let src: string;
export let alt: string = "";
</script>

<style scoped>
.image {
  width: 100%;
  height: 100%;
}

.imageContent {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
</style>