# Username Plates
A small redesign of Usernames in message headers to give them a little extra flair.</br>
Role Color Agnostic, Should work with any role color. Name Legibility with darker role colors on dark mode, or lighter role colors on light mode is not guaranteed.

## Installation
Canary Users: Import [this file](/Snippets/CSS/UserNamePlates.css) to your theme library.

Stable Users: Copy and paste the following CSS into your Custom CSS field.

<details>
<summary>CSS</summary>

```css
.Message\.module__messageUsername___YzRhZj {
  padding: 0 3px;
  &:before {
    content: "";
    position: absolute;
    width: 100%;
    height: 100%;
    background: linear-gradient(
      180deg, color-mix(
        in srgb, currentcolor 10%, transparent
      ), 
      color-mix(
        in srgb, currentcolor 30%, transparent
      )
    );
    border: 
      1px
      solid
      color-mix(
        in srgb, currentcolor 70%, transparent
      );
    border-radius: 5px;
    margin: 0 -3px;
    filter:
      drop-shadow(
        0
        0
        1px
        color-mix(
          in srgb, currentcolor 20%, transparent
        )
      )
      invert(1)
      hue-rotate(180deg)
    ;
  }
}

```

</details>

## Preview
![image](/Previews/UserNamePlates/image.png)
![image](/Previews/UserNamePlates/image2.png)


### Credit
@GH0STP4WZ#0001

<details>
<summary>Changelog</summary>

## 0.1

- Initial release

</details>