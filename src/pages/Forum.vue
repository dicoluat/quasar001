<template>
  <q-page class="row items-center justify-evenly">
    <div>
      <h1>Our Service</h1>
    </div>

  </q-page>
</template>

<script lang="ts">
import ExampleComponent from 'components/ClassComponent.vue'
import { Vue, Component } from 'vue-property-decorator'

@Component({
  components: { ExampleComponent }
})
export default class Forum extends Vue {
}
</script>
