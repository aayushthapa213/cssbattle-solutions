# #7 Leafy Trail

**Battle 1 · Challenge 7** · [Play on CSSBattle](https://cssbattle.dev/play/7)

| Score (this code) | High score |
|-------------------|------------|
| 601.24 | 602.04 |

## Target

![Target](target.png)

## Approach

- `*` resets margins and sets the dark teal background (`#0B2429`). `body` is a flex container that centers the middle leaf.
- Every leaf is a 150×150 `div` with `border-radius: 67% 0`. The top-left and bottom-right corners curve and the other two stay sharp, which gives the leaf shape.
- `.middle` (olive `#998235`) is centered by flexbox.
- `.bottom` (dark green `#1A4341`) is absolutely positioned at `left: 75px`, which puts it 50px to the left of the middle leaf.
- `.top` (orange `#F3AC3C`) is absolutely positioned at `right: 75px`, which puts it 50px to the right.
- The source order (bottom, middle, top) controls the stacking, so the orange leaf is drawn last and appears in front.
