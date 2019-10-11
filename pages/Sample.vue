<template>
  <div id="samplePage">
    <div class="main">
      <h1>サンプルページ</h1>
      <ViewModal v-if="viewFlg" />
      <button @click="showViewModal">モーダル表示</button>
    </div>
  </div>
</template>
<script lang="ts">
import { Vue, Component } from "nuxt-property-decorator";
import ViewModal from "~/components/ViewModal.vue";

@Component({
  components: { ViewModal }
})
export default class Sample extends Vue {
  public viewFlg: boolean;
  constructor() {
    super();
    this.viewFlg = false;
  }

  public showViewModal(): void {
    this.viewFlg = true;
  }
}
</script>
<style>
.main {
  margin-left: 10%;
}
</style>
