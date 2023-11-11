<template>
  <q-toolbar class="Grey1 text-Grey 4">
    <q-toolbar-title class="text">
      <q-avatar>
        <img src="https://tse4.mm.bing.net/th/id/OIP.jWyHp3aKhnYLzTLDnGgvxwHaHa?pid=ImgDet&rs=1" />
      </q-avatar>
      Create Table
    </q-toolbar-title>
  </q-toolbar>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'UserTable'
})
</script>

<style>
.q-avatar__content,
.q-avatar img:not(.q-icon):not(.q-img__image) {
  border-radius: inherit;
  height: 80%;
  width: 80%;
}
</style>
