<script setup>
import Ingredients from "../sections/Ingredients/Ingredients.vue";

</script>

<template>
  <section class="product">
    <div class="container">
      <div class="product__box">
        <img
          src="../../assets//images/image-omelette.jpeg"
          alt=""
          class="product__box-img"
        />

        <h1 class="product__box-title title">Simple Omelette Recipe</h1>
        <p class="product__box-subtitle">An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs cooked to perfection, optionally filled with your choice of cheese, vegetables, or meats.</p>

        <div class="product__box-prep">

          <h2 class="product__box-prep__title">Preparation time</h2>

          <ul class="product__box-prep__list">

            <li class="product__box-prep__item">
              <p class="product__box-prep__txt"> <span>Total: </span> Approximately 10 minutes</p>
            </li>
            <li class="product__box-prep__item">
              <p class="product__box-prep__txt"> <span>Preparation: </span>5 minutes</p>
            </li>
            <li class="product__box-prep__item">
              <p class="product__box-prep__txt"> <span>Total: </span>5 minutes</p>
            </li>

          </ul>

        </div>

        <ingredients />

        <hr class="line">
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.product {
  margin: 100px 0;

  &__box {
    background: var(--boxBgColor);
    width: 100%;
    border-radius: 30px;
    overflow: hidden;
    padding: 40px;

    &-img {
      width: 100%;
      object-fit: cover;
      border-radius: 25px;
      margin-bottom: 30px;
      
    }

    &-title {
      font-size: 40px;
      color: var(--darkColor);
      font-weight: 400;
      margin-bottom: 12px;
    }
    
    &-subtitle {
      line-height: 24px;
      color: var(--keyTextsColor);
      font-weight: 400;
      margin-bottom: 30px;
    }

    &-prep {
      padding: 28px;
      background: var(--lightMainColor);
      border-radius: 10px;
      margin-bottom: 24px;

      &__title {
        color: var(--secTitleColor);
        margin-bottom: 13px;
      }
      &__list {
        margin-left: 24px;
        display: flex;
        flex-direction: column;
        gap: 10px;
      }

      &__txt {
        margin-left: 16px;
        color: var(--keyTextsColor);

        span {
          color: var(--darkColor);
        }
      }

    }
  }
}
</style>

<!--    Ingredients 2-3 large eggs Salt, to taste Pepper, to taste 1 tablespoon of butter or oil Optional fillings: cheese, diced vegetables, cooked meats, herbs Instructions Beat the eggs: In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed. You can add a tablespoon of water or milk for a fluffier texture. Heat the pan: Place a non-stick frying pan over medium heat and add butter or oil. Cook the omelette: Once the butter is melted and bubbling, pour in the eggs. Tilt the pan to ensure the eggs evenly coat the surface. Add fillings (optional): When the eggs begin to set at the edges but are still slightly runny in the middle, sprinkle your chosen fillings over one half of the omelette. Fold and serve: As the omelette continues to cook, carefully lift one edge and fold it over the fillings. Let it cook for another minute, then slide it onto a plate. Enjoy: Serve hot, with additional salt and pepper if needed. Nutrition The table below shows nutritional values per serving without the additional fillings. Calories 277kcal Carbs 0g Protein 20g Fat 22g -->
