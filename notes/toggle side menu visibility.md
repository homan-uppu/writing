when isActive=false:
- the entire side menu is replaced by a single sticky icon 24px from the left and the top (basically the same position as the side menu).
- when the user hovers over the area of the side menu, it animates back to life - but "on top" of the content, not shoving the content to the right as is usual.
- when the cursors moves out of the side menu area, it animates back into the single icon.
- when the icon is clicked, isActive=true, and the original side menu is back.

---

prompts:

the side menu's visibility can be toggled via the toggle component.
create an isVisible state that Toggle's onclick toggles.

when the isVisible=false:
- the entire side menu is replaced by just the toggle icon. (but continue to make the side menu to take the entire height of the screen to enable the following behavior):
- when the user hovers over the area of the side menu, it animates back to life - but "on top" (i.e. give it a shadow).
- when the cursors moves out of the side menu area, it animates back into the single icon.
- when the icon is clicked, isVisible=true, and the original side menu is back.
