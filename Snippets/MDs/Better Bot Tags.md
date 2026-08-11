# Better Bot Tags
This snippet replaces the default "BOT" tag with a more descriptive "WEBHOOK" tag for webhook accounts, making it easier to identify bridged accounts for example.

> [!NOTE]
> This snippet only works on Canary.

## Installation
Canary Users: Import [this file](/Snippets/CSS/BetterBotTags.css) to your theme library.
CSS can still be manually inserted into Custom CSS if desired.

<details>
<summary>CSS</summary>

```css
[data-flx-author-webhook="true"] {
  .ChannelUserTag\.module__tag___XzY5Mm {
    span {
      font-size: 0;
      &:before {
        content: "WEBHOOK";
        font-size: 10px;
      }
    }
  }
}
```

</details>

## Preview

| Bot Message | Webhook Message |
| --- | --- |
| ![image](/Previews/BetterBotTags/Bot.png) | ![image](/Previews/BetterBotTags/Webhook.png) |




### Credit
@GH0STP4WZ#0001

<details>
<summary>Changelog</summary>

## 1.0

- Initial release

</details>