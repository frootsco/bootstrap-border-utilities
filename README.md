# bootstrap-border-utilities
responsive border utilities for bootrap v4.0.0-alpha.6


## notation
```
b   - border
```
```
t  - top
b  - bottom
l  - left
r  - right
x  - left + right
y  - top + bottom
```
```
1   - $border-width-x or $border-width-y
2   - ($border-width-x * 2) or ($border-width-y * 2)
3   - ($border-width-x * 3) or ($border-width-y * 3)
```

## examples
```css
.br-1 {
    border-right: $border-width-x $border-style $border-color;
}


.by-2 {
    border-top: ($border-width-y * 2) $border-style $border-color;
    border-bottom: ($border-width-y * 2) $border-style $border-color;
}


@edia (min-width: 992px) {
    .bb-lg-3 {
        border-bottom: ($border-width-y * 3) $border-style $border-color;
    }
}
```

