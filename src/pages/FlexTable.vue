<template>
  <q-page>
    <!-- Page content goes here -->
    <q-tabs v-model="selectedTab" align="justify">
      <q-tab name="general" label="General" />
      <q-tab name="columns" label="Columns" />
      <q-tab name="constraints" label="Constraints" />
      <q-tab name="sql" label="SQL" />
    </q-tabs>

    <!-- Tab content based on the selected tab -->
    <q-tab-panels v-model="selectedTab">
      <q-tab-panel name="general">
        <!-- Content for the General tab -->
        <div>
          <h2>General Tab Content</h2>
          <!-- Add your content here -->
        </div>
      </q-tab-panel>

      <q-tab-panel name="columns">
        <!-- Content for the Columns tab -->
        <div>
          <h2>Columns Tab Content</h2>
          <!-- Add your content here -->
        </div>
      </q-tab-panel>

      <q-tab-panel name="constraints">
        <!-- Content for the Constraints tab -->
        <div>
          <h2>Constraints Tab Content</h2>
          <!-- Add your content here -->
        </div>
      </q-tab-panel>

      <q-tab-panel name="sql">
        <!-- Content for the SQL tab -->
        <div>
          <h2>SQL Tab Content</h2>
          <!-- Add your content here -->
        </div>
      </q-tab-panel>
    </q-tab-panels>
  </q-page>
</template>

<!-- <script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'FlexTable'
})
</script> -->

<script>
export default {
  data() {
    return {
      selectedTab: 'general' // Set the default selected tab
    }
  }
}
</script>

<style scoped>
h2 {
  color: yellow;
}
</style>
