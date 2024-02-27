<script setup>
import Card from './Card.vue'

const onClickAdd = () => {
  alert('Добавит!')
}
</script>
<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      imageUrl="/sneakers/sneakers-1.jpg"
      title="Мужские кроссовки Nike Blazer Mid Suede"
      :price="1205"
      :isFavorite="true"
      :isAdded="true"
      :onClickAdd="onClickAdd"
    />
  </div>
</template>
