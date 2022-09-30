<template>
  <q-page class="constrain q-pa-md">
    <q-card class="card-post" flat bordered>
      <q-item>
        <q-item-section avatar>
          <q-avatar>
            <img src="https://cdn.quasar.dev/img/boy-avatar.png">
          </q-avatar>
        </q-item-section>

        <q-item-section>
          <q-item-label text-bold>carla_lawrence</q-item-label>
          <q-item-label caption>
            Cape Town, South Africa
          </q-item-label>
        </q-item-section>
      </q-item>
      <q-separator />
    </q-card>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'PageHome'
})
</script>
