<template>
  <div class="home container">
    <img alt="Vue logo" src="../assets/logo.png">
    <hr />
    <div class="row">
      <div class="col col-12">
        <ChildComponent>
          <template v-slot:title>
            A simple content passed to named slot title!
          </template>
          <template v-slot:subtitle>
            A simple content passed to named slot subtitle!
          </template>
          Content for default slot.
        </ChildComponent>
      </div>
    </div>
  </div>
</template>

<script>
import ChildComponent from '@/components/ChildComponent.vue';

export default {
  name: 'home',
  components: {
    ChildComponent,
  },
};
</script>
