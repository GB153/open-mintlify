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

<div
  style="
    display: flex;
    gap: 12px;
    flex-wrap: wrap;
    align-items: flex-start;
  "
>
  <figure style="margin: 0; text-align: center;">
    <img
      src="/example/white_background.png"
      alt="Mobile (Light mode)"
      style="
        width: 100%;
        max-width: 90px;
        border-radius: var(--ot-radius-sm);
        border: 1px solid var(--ot-border);
      "
    />
    <figcaption style="margin-top: 6px; font-size: 0.75rem;">
      Mobile · Light
    </figcaption>
  </figure>

  <figure style="margin: 0; text-align: center;">
    <img
      src="/example/blue_background.png"
      alt="Desktop (Dark mode – Blue)"
      style="
        width: 100%;
        max-width: 90px;
        border-radius: var(--ot-radius-sm);
        border: 1px solid var(--ot-border);
      "
    />
    <figcaption style="margin-top: 6px; font-size: 0.75rem;">
      Desktop · Dark (Blue)
    </figcaption>
  </figure>

  <figure style="margin: 0; text-align: center;">
    <img
      src="/example/brown_background.png"
      alt="Desktop (Dark mode – Brown)"
      style="
        width: 100%;
        max-width: 90px;
        border-radius: var(--ot-radius-sm);
        border: 1px solid var(--ot-border);
      "
    />
    <figcaption style="margin-top: 6px; font-size: 0.75rem;">
      Desktop · Dark (Brown)
    </figcaption>
  </figure>
</div>
