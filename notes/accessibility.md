# Accessibility Notes

## Focus management
- Move focus to heading after route changes in SPAs.
- Use `:focus-visible` for keyboard-only outlines.

## Color contrast
- WCAG AA: 4.5:1 for normal text, 3:1 for large text.
- Don't rely on color alone to convey state.

## Testing
- Quick keyboard pass: Tab through page, check visible focus and order.
- Try a screen reader (VoiceOver/NVDA) on key flows.
