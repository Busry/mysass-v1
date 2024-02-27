# Documentation

## Utilities

### Marging

To add margin use
`m-4` for all round margin of 4 which is equivalent to 1rem.  
`mr-2` for margin right.
`ml-2` for margin left.
`mt-2` for margin top.
`mb-2` for margin bottom.
`mx-2` for margin left and right.
`my-2` for margin top and bottom.

### padding

To add padding use `p` .
`p-4` all round padding of 4 which is equivalent to 1rem
`pr-2` for padding right.
`pl-2` for padding left.
`pt-2` for padding top.
`pb-2` for padding bottom.
`px-2` for padding left and right.
`py-2` for padding top and bottom.

### Opacity

To add opacity use
`o-40` opacity of 40%.  
`o-2` opacity of 20%.

### Display

To change display use
`d-n` means display none.  
`d-b` means display block.  
`d-f` means display flex.  
`d-i` means display inline.  
`d-ib` means display inline-block.

## Text

### Text color

`tx-primary` means text color of primary
`tx-primary-100` means text color of primary with is lighter
Other color types are :

- primary
- secondary
- success
- info
- warning
- error
- light
- dark

### Text font size

`tx-sm` text with font size of small
`tx-md` text with font size of medium
`tx-lg` text with font size of large
`tx-xl` text with font size of extra large
`tx-xxl` text with font size of extra extra large

## Background

### color

`bg-primary` means fill color of primary
`bg-primary-100` means fill color of primary with is lighten adn `bg-primary-900` is the dark version of it.
Other color types are :

- primary
- secondary
- success
- info
- warning
- error
- light
- dark

### complement

`complement-primary` will suggest a complementary text color for primary background color used.

## Grid

This grid system was built using flex box
Each row is made up of 12 grid

```html
<div class="row gap-2 justify-center">
  <div class="xs:col-12 sm:col-5 xl:col-3">
    <div class="card shadow">
      <h3 class="card-title">Hello, ninjas This is busry</h3>
      <p class="card-body">
        Lorem ipsum, dolor sit amet consectetur adipisicing elit.
      </p>
    </div>
  </div>
  <div class="xs:col-12 sm:col-5 xl:col-3">
    <div class="card shadow">
      <h3 class="card-title">Hello, A ninjas</h3>
      <p class="card-body">
        Lorem ipsum, dolor sit amet consectetur adipisicing elit.
      </p>
    </div>
  </div>
</div>
```

`row` to turm the div to a row and
`col-6` to tell a content the number of column it will occupied.
`lg:col-6` to tell a content the number of column it will occupied on a large screen.

## Hover

`hover:tx-primary-100` is how to invoke the hover state with primary background.
similarly `hover:bg-primary-100` is how to invoke the hover state with primary text color.
