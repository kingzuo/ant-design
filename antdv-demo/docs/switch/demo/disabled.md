<cn>
#### 不可用
Switch 失效状态。
</cn>

<us>
#### Disabled
Disabled state of `Switch`.
</us>

```vue
<template>
  <div>
    <a-switch default-checked :disabled="disabled" style="margin-bottom:5px" />
    <br />
    <a-button type="primary" @click="onToggle">
      Toggle disabled
    </a-button>
  </div>
</template>
<script>
export default {
  data() {
    return {
      disabled: true,
    };
  },
  methods: {
    onToggle() {
      this.disabled = !this.disabled;
    },
  },
};
</script>
```
