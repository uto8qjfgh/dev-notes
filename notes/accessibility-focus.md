# Focus Management

Quick notes on focus for accessible components.

## Rules

- Focus should move into a dialog/overlay when opened.
- Return focus to the triggering element on close.
- Trap focus while modal is open.
- Ensure visible focus indicator for keyboard users.

## Common patterns

- Use `inert` on background content instead of manual tabindex management.
- Use `:focus-visible` for styling keyboard focus only.
- Avoid `tabindex="-1"` on interactive elements unless focusing programmatically.

## Resources

- MDN: Focus management
- WAI-ARIA Authoring Practices: Dialog
