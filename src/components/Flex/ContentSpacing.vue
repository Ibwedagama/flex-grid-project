<template>
  <article class="card resizable">
    <div class="card__header">
      <h1 class="card__title">Lorem ipsum dolor sit amet.</h1>
      <button class="card__button">Click Me</button>
    </div>
    <div class="card__body">
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum veniam quod
        asperiores facilis saepe velit quibusdam? Perspiciatis soluta explicabo
        impedit laboriosam atque perferendis aspernatur quis quod. Temporibus
        ipsum animi dolorum!
      </p>
    </div>
  </article>
</template>

<script>
export default {};
</script>

<style scoped>
.card {
  padding: 30px 48px;
  width: 500px;
  border: 1px solid #ccc;
  border-radius: 12px;
}

.card__header {
  text-align: left;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 16px;
}

.card__body > p {
  text-align: left;
}

.card__title {
  font-size: 20px;
  font-weight: bold;
  color: gray;
  margin: 0;
  padding: 0;

  margin-right: 3rem;
}

.card__button {
  padding: 12px 16px;
  background: blue;
  margin-left: auto;
  white-space: nowrap;
  color: white;
}
</style>
