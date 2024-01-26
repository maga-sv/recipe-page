<script setup>



</script>

<template>

<div class="ingredients">
    <h2 class="ingredients__title title">Ingredients</h2>

    <ul class="ingredients__list">

        <li class="ingredients__item"><p>2-3 large eggs</p></li>
        <li class="ingredients__item"><p>Salt, to taste</p></li>
        <li class="ingredients__item"><p>Pepper, to taste</p></li>
        <li class="ingredients__item"><p>1tablespoon of butter or oil</p></li>
        <li class="ingredients__item"><p>Optional filings: cheese, diced vegetables, cooked meats, hearbs</p></li>

    </ul>

</div>

</template>

<style lang="scss" scoped>
    
    .ingredients {
        &__title {
            color: var(--titlesColor);
            font-weight: 400;
            margin-bottom: 16px;
        }

        &__list {
            margin-left: 24px;
            display: flex;
            flex-direction: column;
            gap:12px;
            margin-bottom:7px;
        }

        &__item {
            color: var(--keyTextsColor);
            &::marker {
                color: var(--titlesColor);

            }

            p {

                margin-left: 16px;
            }

        }
    }

</style>