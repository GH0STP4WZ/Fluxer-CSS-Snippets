# Improved User Area
Enhances the user area by hiding the Voice Call buttons and showing you more information.

## Installation
Canary Users: Import [this file](/Snippets/CSS/ImprovedUserArea.css) to your theme library.
Stable Users: Copy and paste the following CSS into your Custom CSS field.

<details>
<summary>CSS</summary>

```css
.GuildsLayout\.module__userAreaWrapper___XzI4MD {
  .UserArea\.module__userAreaContainer___XzI2YW {
    .BaseAvatar\.module__container___ZmRhMD {
      margin-left: -15px;
      width: 43px!important;
      height: 43px!important;
    }
    .UserArea\.module__userInfoText___XzI2YW {
      height: 43px;
    }
    .UserArea\.module__hoverRoll___XzI2YW {
      contain: layout;
      height: 30px;
      .UserArea\.module__hovered___XzI2YW {
        opacity: 1!important;
        transform: none;
        translate: 0 0px;
        &:before {
          content: "@";
          font-weight: 800;
          color: var(--text-chat-muted);
        }
      }
      .UserArea\.module__defaultState___XzI2YW {
        transform: none!important;
        opacity: 1!important;
        translate: 0 15px;
      }
    }
    .UserArea\.module__controlsContainer___XzI2YW,
    .UserArea\.module__controlsContainer___XzI2YW * {
      transition: all ease 0.5s;
      padding-left: 0;
      &:not(:hover) {
        [data-flx="app.user-area.user-area-inner.focus-ring"],
        [data-flx="app.user-area.user-area-inner.focus-ring--2"] {
          opacity: 0;
          margin-right: -40px;
        }
      }
    }
  }
}

```

</details>

## Preview
![image](/Previews/ImprovedUserArea/record-2026-07-29_10-54-37.gif)

### Credit
@GH0STP4WZ#0001 — Aurora Dess "GH0STP4WZ" Hartman

<details>
<summary>Changelog</summary>

## 1.0

- Initial release

</details>