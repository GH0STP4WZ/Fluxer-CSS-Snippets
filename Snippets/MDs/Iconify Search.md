# Iconify Search
Collapses the search bar in the Channel header into an icon that matches the style of the other buttons;
Allowing it to take up less space and expand when needed.

> [!WARN]
> Not Tested For Stable.

## Installation
Canary Users: Import [this file](/Snippets/CSS/IconifySearch.css) to your theme library.
Stable Users: Copy and paste the following CSS into your Custom CSS field.

<details>
<summary>CSS</summary>

```css
:root {/* These root variables are the same as the default ones, except these are only defined in the actual bar object.
          They need to be redefined here so that the anchor element has the pretend to be the background, which allows for the
          smooth transitional effect. Fluxer is weird sometimes, man. */
    --search-input-border-color: var(--background-modifier-accent);
    --search-input-border-focus-color: var(--background-modifier-accent-focus);
    --search-input-background: var(--background-textarea);
    --search-icon-color: var(--text-tertiary);
    --search-icon-hover-color: var(--text-primary);
    --search-scope-badge-background: var(--background-secondary);
    --search-scope-badge-hover-background: var(--background-secondary-alt);
    --search-scope-badge-color: var(--text-primary-muted);
    --search-scope-badge-hover-color: var(--text-primary);
    --search-scope-badge-border-color: var(--background-modifier-accent);
    --search-input-text-color: var(--text-primary);
    --search-input-placeholder-color: var(--text-tertiary);
    --search-clear-button-color: var(--text-tertiary);
    --search-clear-button-hover-color: var(--text-primary);
    --search-clear-button-hover-background: var(--background-modifier-hover);
}
.ChannelHeader\.module__headerWrapper___XzU4Mj {
    .ChannelHeader\.module__headerContainer___XzU4Mj {
        .ChannelHeader\.module__messageSearchFocusWrapper___XzU4Mj {
            transition: all ease 0.3s!important;
            justify-content: flex-end!important;
            .MessageSearchBar\.module__anchor___Y2RiYT {
                transition: all ease 0.3s!important;
                justify-content: flex-start!important;
                border-radius: var(--radius-xl);
                border: 0.0625rem solid var(--search-input-border-color);
                background-color: var(--search-input-background);
                .MessageSearchBar\.module__scopeButton___Y2RiYT {
                    transition: all ease 0.3s!important;
                    .MessageSearchBar\.module__scopeBadge___Y2RiYT {
                        transition: all ease 0.3s!important;
                    }
                }
                .MessageSearchBar\.module__inputContainer___Y2RiYT {
                    transition: all ease 0.3s!important;
                    background: none;
                    border: transparent;
                    .MessageSearchBar\.module__input___Y2RiYT {
                        transition: all ease 0.3s!important;
                        width: 100%!important;
                        min-width: 100%!important;
                    }
                }
            }
            &:not(:has(.MessageSearchBar\.module__anchor___Y2RiYT:hover, .MessageSearchBar\.module__inputContainer___Y2RiYT:hover, .MessageSearchBar\.module__inputContainer___Y2RiYT:active, .MessageSearchBar\.module__inputContainer___Y2RiYT:focus-within, .MessageSearchBar\.module__inputContainer___Y2RiYT .MessageSearchBar\.module__clearButton___Y2RiYT)) {
                width: 30px!important;
                min-width: 25px!important;
                flex: 0 0 25px!important;
                .MessageSearchBar\.module__scopeButton___Y2RiYT {
                    scale: 1.3;
                    translate: -2px 0;
                    .MessageSearchBar\.module__scopeBadge___Y2RiYT {
                        opacity: 0;
                        pointer-events: none;
                    }
                }

                .MessageSearchBar\.module__input___Y2RiYT {
                    min-width: 0px!important;
                }
                .MessageSearchBar\.module__anchor___Y2RiYT {
                    width: 30px!important;
                    min-width: 30px!important;
                    flex: 0 0 30px!important;
                    background: transparent;
                    border: 1px solid transparent;
                }
                .MessageSearchBar\.module__inputContainer___Y2RiYT {
                    flex: 0 0 30px!important;
                    width: 30px!important;
                    min-width: 30px!important;
                }
            }
        }
    }
}
```
</details>

## Preview
![image](/Previews/IconifySearch/IconifySearch.gif)

### Credit
@GH0STP4WZ#0001

<details>
<summary>Changelog</summary>

## 1.0

- Initial release

</details>