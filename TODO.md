# To do

Ideas and known gaps that are not in the current release.

## Next

- **Show the last selection.** An optional, greyed-out, non-selectable note
  of what was last chosen, so an accidental click can be identified at a
  glance. Position setting: top of the list, bottom of the list, or the
  centre of the wheel. Things to settle:
  - The centre (inside the hub, beside the cursor) is always visible. The top
    or bottom of the list scrolls out of view on long menus.
  - Show how long ago it was ("Copy, 5 s ago"), since the same note means
    something different a second later than an hour later.
  - The history already records the last choice, so this is display only.

## Later

- Menu icons.
- Draw owner-drawn items properly, instead of "Item N" in submenus and the
  standard menu at the top level.
- Saved orders: reuse an order when only a file name in a label differs
  ("Extract to ...", "Add to ..."), and clear out orders that are never used
  again.
- Custom items: pass the right-clicked file or folder to the command.
- Stacked submenus: keep deep rings on screen.
- Programs that are not per-monitor DPI aware: convert the hook's
  coordinates so clicks land correctly on scaled displays.
