# Accessibility Checklist

Use this when reviewing components or pages.

## Semantic structure
- [ ] Use one `h1` per page, with heading levels in order.
- [ ] Landmarks: `header`, `nav`, `main`, `footer`.
- [ ] Group form controls with `fieldset`/`legend` where relevant.

## Keyboard
- [ ] All interactive elements reachable via Tab.
- [ ] Visible focus indicator at all times.
- [ ] No keyboard traps; escape closes dialogs/menus.

## Forms
- [ ] Labels associated with inputs (`for`/`id` or `aria-labelledby`).
- [ ] Errors identified in text and linked to the field.
- [ ] Required fields indicated beyond color.

## Images and media
- [ ] Decorative images have empty `alt`.
- [ ] Informative images have descriptive `alt` text.
- [ ] Video has captions and audio has transcript.

## ARIA
- [ ] Use native elements before ARIA.
- [ ] `aria-expanded` and `aria-controls` on disclosure widgets.
- [ ] Dynamic regions announced with `aria-live` when necessary.

## Visual and contrast
- [ ] Text contrast meets WCAG AA (4.5:1 normal, 3:1 large).
- [ ] Don't rely on color alone for meaning.
- [ ] Touch targets at least 44x44 px.

## Testing
- [ ] Zoom to 200% with no loss of content.
- [ ] Test with keyboard only.
- [ ] Spot-check with a screen reader (VoiceOver/NVDA).
