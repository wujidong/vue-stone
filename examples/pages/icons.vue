<template>

  <div>
    <tmpl-back></tmpl-back>
    <v-panel>
      <div slot="header" class="c-panel-header row-1 u-cross-center">Icons set</div>

      <div slot="body" class="c-panel-body">
        <span class='icon v-icon-mode-smart'></span>
        <span class='icon v-icon-quick-wash-30'></span>
        <span class='icon v-icon-quick-wash-15'></span>
        <span class='icon v-icon-mode-sleep'></span>
        <span class='icon v-icon-mode-automatic'></span>
        <span class='icon v-icon-small-volume'></span>
        <span class='icon v-icon-large-volume'></span>
        ...
      </div>
    </v-panel>
  </div>
</template>

<script>

  export default {
    name: 'Icons',

    data() {
      return {
      };
    },

    methods: {
    },
  };
</script>

<style>

  .c-panel-body {
    .icon {
      margin-right: 10px;
      margin-left: 10px;
      margin-top: 10px;
      margin-bottom: 10px;
      display: inline-block;
    }
  }
</style>
