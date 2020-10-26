<template>
  <q-page class="row items-center justify-evenly">
    <div>
      <h1>Home</h1>
    </div>
  </q-page>
</template>

<script lang="ts">
import { Todo, Meta } from 'components/models'
import ExampleComponent from 'components/ClassComponent.vue'
import { Vue, Component } from 'vue-property-decorator'

@Component({
  components: { ExampleComponent }
})
export default class Index extends Vue {
  todos: Todo[] = [
    {
      id: 1,
      content: 'ct1'
    },
    {
      id: 2,
      content: 'ct2'
    },
    {
      id: 3,
      content: 'ct3'
    },
    {
      id: 4,
      content: 'ct4'
    },
    {
      id: 5,
      content: 'ct5'
    },
    {
      id: 6,
      content: 'ct6 abc'
    }
  ];

  meta: Meta = {
    totalCount: 1200
  };
}
</script>
