<template>
  <div class="food-add">
      <div class="food-add__con">
          <h2 class="food-add__con__title">{{foodAddData.title}}</h2>
          <div class="food-add__con__inp">
              <input type="text" class="food-add__con__inp__input">
              <button class="food-add__con__inp__button">Add</button>
          </div>
      </div>
    
  </div>
</template>

<script>
export default {
  name: 'AddFood',
  props: {
    msg: String
  },
  data() {
      return {
          foodAddData: {
              title: 'What food did you eat today?'
          }
      }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.food-add {
    padding: 1em 2em;

    &__con {
        &__title {
            text-align: center;
            padding-top: 1.4em;
            font-size: 2.8em;
        }

        &__inp {
            margin: 0 auto;
            display: flex;
            align-items: center;
            justify-content: center;
            padding-top: 1.2rem;

            &__input {
                
                border: 1px solid #AA5639;
                border-top-left-radius: 2px;
                border-bottom-left-radius: 2px;
                height: 2.2rem;
                font-size: 1.7rem;
                text-indent: .2rem;
                outline: none;
            }

            &__button {
                background: #AA5639;
                color: white;
                height: 2.2rem;
                font-size: 1.5rem;
                padding: 0 .5rem;
            }
        }
    }

    

    
}



.food-add__con__inp {
    margin: 0 auto;
}



</style>
