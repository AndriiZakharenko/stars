# Stars block

Implemented the [Stars Block](https://www.figma.com/file/ojkArVazq7vsX0nbpn9CxZ/Moyo-%2F-Catalog-(ENG)?node-id=11325%3A2960&mode=dev) used in a card and catalog.

## Requirements:
- Reset browser's default `margin`
- Added 6 `stars` blocks with 5 `stars__star` elements each.
- Added `stars--0`, `stars--1`, `stars--2` ... `stars--5` modifiers to the blocks one per each
- Don't add any other classes to the elements.
- The block with `stars--N` modifier should have exactly `N` first stars active.
- use `background-image` for stars (see `images` folder). Don't use `<img>` or `<svg>` tags.
- The star size and the distance should be taken from Figma
- Use `display: flex` for the `stars` block to avoid an issue with extra spaces between individual stars
- Don't add vertical margins between blocks.
- DON'T use `gap` property for `flex` container because it does not work in tests

## Demo Links

- [DEMO LINK](https://AndriiZakharenko.github.io/layout_stars/)
