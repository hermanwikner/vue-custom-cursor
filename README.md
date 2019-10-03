# Vue-Custom-Cursor

Include the component in `App.vue`. Also, you might want to hide the default cursor in CSS like `* { cursor: none; }`.

![alt text](https://raw.githubusercontent.com/hermanwikner/Vue-Custom-Cursor/master/vue-custom-cursor.gif)

## Settings

| Props      | Type         | Description |
| :------------- |:-------------|:-------------|
| targets     | Array | Class-names or tag-names which should trigger the hover animation | 
| circleColor | String | The color of the outer circle | 
| dotColor | String | The color of the inner dot | 
| circleColorHover | String | The color of the outer circle when hovering over a selected target | 
| dotColorHover | String | The color of the inner dot when hovering over a selected target| 
| hoverSize | Number | The size of the cursor when hovering over a selected target| 

## Example 

```
    <custom-cursor
      :targets="['img', 'a', 'button', 'your-hover-class']"
      :circleColor="'#fff'"
      :circleColorHover="'#2f2f2f'"
      :dotColor="'#2f2f2f'"
      :dotColorHover="'lightgray'"
      :hoverSize="1.8"
    ></custom-cursor>
``` 
