<script lang="tsx">
export default defineComponent({
  render() {
    return (
      <div class="content">
        { this.$slots?.default() }
      </div>
    )
  }
})
</script>