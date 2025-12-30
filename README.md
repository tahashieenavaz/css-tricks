- [Class-Prefixed Buttons](#class-prefixed-buttons)


## Class-Prefixed Buttons

Instead of having two classes of `button` and for instance `button-primary` for your buttons. You can channel the base rules using a selector which selects all the classes that start with `button` string.

```css
[class|="button"] {
    // base rules go here
}
.button-primary {
    background: navy;
}
```

```html
<a href="#" class="button-primary">
    Click me
</a>
```

Credits: https://www.youtube.com/shorts/-evhup81D8M