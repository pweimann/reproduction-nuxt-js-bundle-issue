<template lang="pug">
div
  h1 Hello World
  BaseBody
    TextContainer(align='center')
      p Test
</template>

<script setup lang="ts">
import BaseBody from "~/components/layout/body/BaseBody.vue";
import TextContainer from "@/components/base/textContainer/TextContainer.vue";</script>
