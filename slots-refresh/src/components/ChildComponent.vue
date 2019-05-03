<template>
  <div class="card">
    <div class="card-body">
      <div class="card-title">
        <slot name="title"></slot>
      </div>
      <div class="card-subtitle">
        <slot name="subtitle"></slot>
      </div>
      <div class="card-text">
        <slot></slot>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ChildComponent',
};
</script>
