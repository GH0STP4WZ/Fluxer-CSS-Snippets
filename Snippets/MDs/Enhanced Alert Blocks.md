# Enhanced Alert Blocks
More Stylized Alert Blocks which stand out a bit more.

## Installation

Enhanced Alert Blocks has Three variants. Chose your preferred flavor:

#### Canary users:
Import one of the following files to your theme library
- [Variant One](/Snippets/CSS/EnhancedAlertBlocks_var1.css)
- [Variant Two](/Snippets/CSS/EnhancedAlertBlocks_var2.css)
- [Variant Three](/Snippets/CSS/EnhancedAlertBlocks_var3.css)


#### Stable Users:
Copy and paste the CSS below into your Custom CSS field.

<details>
<summary>Variant One</summary>

```css
.Markup\.module__alert___XzQ5ZD.Markup\.module__alert___XzQ5ZD {
    position: relative;
    max-width: 100%;
    width: fit-content;

    background:
        linear-gradient(
            90deg,
            color-mix(
                in srgb,
                currentcolor 20%,
                transparent
            ) 15%,
            color-mix(
                in srgb,
                currentcolor 5%,
                transparent
            ) 50%,
            transparent 70%
        );
}

.Markup\.module__alert___XzQ5ZD.Markup\.module__alert___XzQ5ZD::after {
    content: "";
    position: absolute;
    left: 0;
    bottom: 0;

    width: 100%;
    height: 3px;

    border-radius: 4px;

    background:
        linear-gradient(
            90deg,
            color-mix(
                in srgb,
                currentcolor 80%,
                transparent
            ) 15%,
            color-mix(
                in srgb,
                currentcolor 45%,
                transparent
            ) 50%,
            transparent 70%
        );
}

.Markup\.module__alertTitle___XzQ5ZD {
    width: fit-content;
    padding: 0 5px;

    margin: 0 -3px;

    border: 1px solid
        color-mix(
            in srgb,
            currentcolor 70%,
            transparent
        );

    border-radius: 5px;

    background:
        linear-gradient(
            180deg,
            color-mix(
                in srgb,
                currentcolor 10%,
                transparent
            ),
            color-mix(
                in srgb,
                currentcolor 30%,
                transparent
            )
        );

    filter:
        drop-shadow(
            0 0 1px
            color-mix(
                in srgb,
                currentcolor 20%,
                transparent
            )
        );
}

```

</details>

<details>
<summary>Variant Two</summary>

```css
.Markup\.module__alert___XzQ5ZD.Markup\.module__alert___XzQ5ZD::before {
    display: none;
}

.Markup\.module__alert___XzQ5ZD.Markup\.module__alert___XzQ5ZD {
    width: fit-content;
    max-width: 100%;

    margin: 0 -3px;
    margin-left: 0 !important;

    border: 1px solid
    color-mix(
        in srgb,
        currentcolor 70%,
        transparent
    );

    border-radius: 5px;

    background:
    linear-gradient(
        180deg,
        color-mix(
            in srgb,
            currentcolor 10%,
            transparent
        ),
        color-mix(
            in srgb,
            currentcolor 30%,
            transparent
        )
    );

    filter:
    drop-shadow(
        0 0 1px
        color-mix(
            in srgb,
            currentcolor 20%,
            transparent
        )
    );
}

.Markup\.module__alertTitle___XzQ5ZD {
    position: relative;

    filter:
    drop-shadow(
        0 0 5px
        currentcolor
    );
}

.Markup\.module__alertTitle___XzQ5ZD::after {
    content: "";

    position: absolute;

    width: 100%;
    height: 100%;

    border-radius: 4px;

    color: inherit;

    background:
    color-mix(
        in srgb,
        currentcolor 20%,
        transparent
    );

    filter:
    invert(1)
    hue-rotate(180deg);
}
```

</details>

<details>
<summary>Variant Three</summary>

```css
.Markup\.module__alert___XzQ5ZD.Markup\.module__alert___XzQ5ZD {
    width: fit-content;
    max-width: 100%;

    border: 1px solid
    color-mix(
        in srgb,
        currentcolor 70%,
        transparent
    );

    background-image:
    radial-gradient(
        circle at bottom center,
        color-mix(
            in srgb,
            currentcolor 30%,
            transparent
        ) 0%,
        color-mix(
            in srgb,
            currentcolor 10%,
            transparent
        ) 50%
    );
}
```

</details>


## Preview
| Variant 1 | Variant 2 | Variant 3 |
| --- | --- | --- |
| ![image](/Previews/EnhancedAlertBlocks/Variant1.png) | ![image](/Previews/EnhancedAlertBlocks/Variant2.png) | ![image](/Previews/EnhancedAlertBlocks/Variant3.png) |

### Credit
@GH0STP4WZ#0001

<details>
<summary>Changelog</summary>

## 1.0.0

- Initial release

</details>