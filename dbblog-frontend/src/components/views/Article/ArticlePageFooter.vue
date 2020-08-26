<template>
  <div class="article-page-footer">
    <license-tag></license-tag>
    <social-section :type="'Article'" :postId="postId"></social-section>
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
