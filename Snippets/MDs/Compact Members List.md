# Compact Members List
Fluxer on a Small Screen can be annoying. This snippet hides the Members List until you hover over it, giving you more space to view messages.

## Installation
Canary Users: Import [this file](/Snippets/CSS/CompactMembersList.css) to your theme library.
Stable Users: Copy and paste the following CSS into your Custom CSS field.

<details>
<summary>CSS</summary>

```css
.ChannelIndexPage\.module__memberListDivider___XzNmOW,
.MemberListContainer\.module__memberListContainer___XzJhOT {
    transition: all ease 0.3s!important;
}
body:not(:has(.MemberListContainer\.module__memberListContainer___XzJhOT:hover)) {
    .ChannelIndexPage\.module__memberListDivider___XzNmOW,
    .MemberListContainer\.module__memberListContainer___XzJhOT {
        margin-right: -210px;
    }
}
```

</details>

## Preview
![image](/Previews/CompactMembersList/record-2026-08-06_23-58-48.gif)

### Credit
@GH0STP4WZ#0001

<details>
<summary>Changelog</summary>

## 0.1

- Initial release. This snippet is currently functional, but could use a few more tweaks.

</details>