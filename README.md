# Styling your docs your way

This project is very simply the mintlify starter kit but with a custom **style.css** added to it. The idea behind this demonstration is that you can tweak the colors, borders, radii and more in **theme/tokens.css**.

```css
:root {
    --ot-bg: #faf3e0;
    --ot-fg: #36251e;
```

 Adjust these colors above to change background and foreground colors simply, to invert them simply change the following in **theme/tokens.css**
 
 ```css
 html.dark {
    --ot-bg: #36251e;
    --ot-fg: #faf3e0;
```

To adjust radius borders for consistent styling, just change the following three variables:

```css
    --ot-radius-xs: 15px;
    --ot-radius-sm: 15px;
    --ot-radius-md: 15px;
```

All done! Here are some examples below that only require changing the color schemes and radii. You are also able to fully customise indiviudal selectors on a case-by-case basis without manually looking for each <div></div> yourself.


## Images

<figure>
  <img
    src="/examples/white_background.png"
    alt="Mobile (Light mode) – White background"
    style="max-width: 720px; width: 100%; border-radius: var(--ot-radius-md); border: 1px solid var(--ot-border);"
  />
  <figcaption>Mobile (Light mode) – White background</figcaption>
</figure>

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 16px;">
  <figure style="margin: 0;">
    <img
      src="/examples/blue_background.png"
      alt="Desktop (Dark mode) – Blue background"
      style="width: 100%; border-radius: var(--ot-radius-md); border: 1px solid var(--ot-border);"
    />
    <figcaption>Desktop (Dark mode) – Blue background</figcaption>
  </figure>

  <figure style="margin: 0;">
    <img
      src="/examples/brown_background.png"
      alt="Desktop (Dark mode) – Brown background"
      style="width: 100%; border-radius: var(--ot-radius-md); border: 1px solid var(--ot-border);"
    />
    <figcaption>Desktop (Dark mode) – Brown background</figcaption>
  </figure>
</div>
