<template>
  <Page>
    <!-- <ActionBar>
      <Label text="Home" class="font-bold text-lg" />
    </ActionBar> -->

    <GridLayout columns="*, *" rows="*, *">
      <button text="Take Attendance" @tap="onButtonTap" />
      <label text="0,1" row="0" col="1" />
      <label text="1,0" row="1" col="0" backgroundColor="#289062" />
      <label text="1,1" row="1" col="1" backgroundColor="#43b883" />
    </GridLayout>
  </Page>
</template>

<script lang="ts">
import Vue from 'nativescript-vue';
// import {} from '@nativescript/core';

export default Vue.extend({
  computed: {
    message() {
      return 'Blank {N}-Vue app';
    },
  },

  methods: {
    logMessage() {
      console.log('You have tapped the message!');
    },
    onButtonTap() {},
  },
});
</script>

<style>
/* .info {
    font-size: 20;
  } */
</style>
