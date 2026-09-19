# UI/UX Improvements

## Visual Design & Interaction
* ✅ **Better visual design**: More polished, modern look with a gradient accent and nicer typography.
* **Swap/swap direction button**: Actually bidirectional already, but needs a clear visual indicator.
* ✅ **Live counters**: Real-time character and word count tracking.
* **Clear button**: Easy clearing for both input and output fields.
* ✅ **Toast notifications**: Replace or complement button text swap for improved copy feedback.
* **Focus visible states**: Enhanced visual indicators for keyboard navigation.
* ✅ **Dark/light theme toggle**: Manual override in addition to `prefers-color-scheme`, cycled via a toggle button (System/Light/Dark) persisted in `localStorage`.
* ✅ **Title styling**: Nice gradient text on the main title.
* **Copy feedback**: Animated confirmation when text is copied.

## Accessibility (a11y) & Responsiveness
* **Accessibility improvements**: ARIA labels, roles, live regions for screen readers, and keyboard shortcuts.
* **Better mobile responsiveness**: Optimized layout for all screen sizes.

## State & Content Management
* ✅ **Persist state**: Save style selection and last text in `localStorage`.

---

# New Features

## More Text Styles (The Big One)
Currently only 2 styles. Can add many more Unicode styles:
* **Fullwidth**: `ＡＢＣ`
* **Circles/Framed**: `ⒶⒷⒸ` (negative circled `🅐` is emoji-ish)
* **Serif variants**: Bold serif, italic serif, and bold italic
* **Monospace**: `𝙰𝙱𝙲`
* **Small caps**: `ᴀʙᴄ`
* **Upside down**: `ɐqɔ`
* **Bubble/circled**: `ⓐⓑⓒ`
* **Squared negative**: `🄰🄱🄲`
* **Script**: `𝒜ℬ𝒞`
* **Gothic/Fraktur**: `𝔄𝔅ℭ`
* **Strikethrough**: Via combining chars (`A̶B̶C̶`)
* **Underline**: Via combining chars
* **Superscript**: `ᵃᵇᶜ`

## Advanced Functionality
* ✅ **Keyboard shortcuts**: Ctrl+Enter to copy styled text; Ctrl+⌘C copies the styled text (toast feedback).
* **History**: Recent translations log. *Maybe overkill but nice.*
* **Share URL**: Encode text in URL query parameters for easy sharing.

---

# Production Ready

## SEO & Metadata
* **Favicon**: Inline SVG data URI (no external dependencies).
* **Meta tags**: Add meta description, Open Graph tags, and `theme-color`.

## Code & Performance
* **Noscript fallback**: Add a message for users with disabled JavaScript.
* **Error handling**: Robust handling of edge cases.
* **Semantic HTML**: Proper tag usage throughout the markup.
* **Performance**: It’s tiny already.
* **File structure**: Maybe split files? For a single-file app, keeping it single-file is actually fine.
