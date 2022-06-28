<template>
  <div>
    <h1>買い物リスト</h1>
    <ul>
      <li>
        <input type="checkbox" />
        <span>ぶどう</span>
      </li>
    </ul>
    <input type="text" />
    <div>
      <button>リストアイテムを追加する</button>
      <button>選択したアイテムを消去する</button>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [],
    };
  },
  methods: {},
  computed: {},
};
</script>

<style scoped>
ul {
  list-style-type: none;
}

.selected-item {
  text-decoration: line-through;
}
</style>
