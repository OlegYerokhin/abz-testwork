<template>
  <q-layout view="lHh Lpr lFf">
    <q-header class="bg-light-gray">
      <q-toolbar>
        <q-toolbar-title>
          <q-img src="../assets/Logo.svg" alt="" />
        </q-toolbar-title>

        <div>btn-1</div>
        <div>btn-2</div>
      </q-toolbar>
    </q-header>

    

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>



export default {
  name: 'MainLayout',
  components: {},
  data () {
    return {
    }
  }
}
</script>
