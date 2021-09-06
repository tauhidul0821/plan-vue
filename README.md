- Props − Type for props is an array of string or object. It takes an array-based or object-based syntax. They are said to be attributes used to accept data from the parent component.

```JS
ex: 
   props: ['size', 'myMessage']

or 
props: {
      // just type check
      height: Number,
      
      // type check plus other validations
      age: {
         type: Number,
         default: 0,
         required: true,
         validator: function (value) {
            return value >= 0
         }
      }
   }

   ```


