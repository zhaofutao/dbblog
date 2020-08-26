<template>
  <div class="article-page-footer">
    <license-tag></license-tag>
    <social-section :post-id="postId" :type="'BookNote'"></social-section>
  </div>
</template>

<script type="text/ecmascript-6">

export default {
  components: {
  },
  props: {
    postId: Number
  }
}
</script>
