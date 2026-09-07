# Thirteen Colonies Map

An interactive map for teaching the Thirteen Colonies. Click a colony and it lights up while every other colony stays grey.

**Live version:** https://tanman310.github.io/thirteen-colonies/

## Using it in class

- **Click a colony** on the map or pick one from the list to highlight it. Click again to clear it.
- **Hide names** strips every label off the map — useful for a blank-map quiz or a "name that colony" warm-up.
- **Color the regions** shows New England, the Middle Colonies, and the Southern Colonies in three colors at once.
- **Save image** downloads the current view as a PNG, sized for slides.
- Arrow keys move through the colonies one at a time. Esc clears the selection.

Everything runs in the browser from a single file. No account, no internet connection, nothing to install.

## A note on the geography

Boundaries are modern state outlines, the way most textbook maps draw them, with three adjustments for the colonial period:

- **Maine is part of Massachusetts.** It was governed as part of Massachusetts until 1820, so selecting Massachusetts highlights both landmasses.
- **West Virginia is inside Virginia.** Virginia was undivided until 1863.
- **Vermont is greyed out with a dashed border.** The New Hampshire Grants were claimed by both New York and New Hampshire and were never one of the thirteen colonies.

Founding dates are the ones textbooks generally use. Several colonies changed hands or charters more than once, so those dates are a starting point for discussion rather than the whole story.

## Editing it

The whole thing is one file, `index.html`. Colony names, dates, and the short descriptions live in the `DATA` block near the bottom of the file, inside the `<script>` tag. Edit the text there, commit, and the live site updates in about a minute.

## Credits

Boundary data from [Natural Earth](https://www.naturalearthdata.com/), which is in the public domain.
