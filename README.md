# Accessibility Enhancement: Roving Index Technique for Keyboard Navigation

## Objective
This lab improves keyboard accessibility for a menu by implementing the **roving index technique**, allowing keyboard-only users to navigate menu items using **up and down arrow keys**.

## Requirements

1. **Programmatic Focus Management**:
   - Apply focus to the newly selected menu item when navigating with the arrow keys.

2. **Tabindex Management**:
   - Set `tabindex="0"` for the currently focused menu item.
   - Update `tabindex="-1"` for the previously focused item to remove it from the tab order.

## Instructions

1. **Implementation Steps**:
   - Open the `focus.html`, `CSS.css`, and `JS.js` files.
   - In `JS.js`, add JavaScript to handle `keydown` events on the menu container:
     - Detect **Up Arrow** (`ArrowUp`) and **Down Arrow** (`ArrowDown`) keys.
     - Track the focused menu item and update focus based on keypress.
     - Set `tabindex="0"` on the newly focused item and `tabindex="-1"` on the previously focused item.

2. **Testing the Solution**:
   - **Keyboard Only**: Use only the keyboard to navigate through menu items.
   - **Chrome DevTools**: Open Chrome DevTools, use the **Elements** panel to inspect `tabindex` changes, and verify the focus behavior.

## Tools & Practice

- **Keyboard Navigation**: Test using the keyboard only to confirm accessibility.
- **Chrome DevTools Inspector**: Monitor `tabindex` changes and ensure correct focus management.




