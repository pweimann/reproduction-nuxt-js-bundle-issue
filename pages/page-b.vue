<template lang="pug">
div
  h1 Hello World
  LayoutBody
    BaseTextContainer(align='center')
      p Test
</template>

<script setup lang="ts">
import LayoutBody from "~/components/layout/body/LayoutBody.vue";
import BaseTextContainer from "~/components/base/textContainer/BaseTextContainer.vue";</script>
