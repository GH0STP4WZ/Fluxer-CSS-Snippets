# Dynamic Send Button
Dynamically hides the Send button (if enabled) until there is actually something to send

> [!WARNING]
> DOES NOT WORK ON FLUXER STABLE

## Installation
Import [this file](/Snippets/CSS/DynamicSendButton.css) to your theme library or paste the following CSS into your custom CSS

<details>
<summary>CSS</summary>

```css
.TextareaInput\.module__buttonContainerDense___XzJmNz {
    transition: all 0.2s ease-in-out;
    margin-right: 35px;
    transition-property: opacity, margin-right;
    .TextareaButton\.module__button___XzgyZD:last-child {
        transition: all 0.2s ease-in-out;
        position: absolute;
        right: 0;
        &:disabled {
            opacity: 0;
            right: -25px;
        }
    }
    &:has(.TextareaButton\.module__button___XzgyZD:last-child:disabled) {
        margin-right: -15px;
    }
}
```

</details>

## Preview
![image](/Previews/DynamicSendButton/Dynamic%20Send%20Button.gif)

### Credit
@GH0STP4WZ#0001

<details>
<summary>Changelog</summary>

## 1.0

- Initial release

</details>