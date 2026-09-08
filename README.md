# Thirteen Colonies Map

An interactive map for teaching the Thirteen Colonies. Click a colony and it lights up while every other colony stays grey.

**Live version:** https://tanman310.github.io/thirteen-colonies/

## Using it in class

- **Click a colony** on the map or pick one from the list to highlight it. Click again to clear it.
- **Show modern borders** lays today's state lines over the colonial map, with the land the states took in later shown pale. Off by default.
- **Hide names** strips every label off the map — useful for a blank-map quiz or a "name that colony" warm-up.
- **Color the regions** shows New England, the Middle Colonies, and the Southern Colonies in three colors at once.
- **Save image** downloads the current view as a PNG, sized for slides.
- Arrow keys move through the colonies one at a time. Esc clears the selection.

Everything runs in the browser from a single file. No account, no internet connection, nothing to install.

## A note on the geography

The colonies are drawn as they stood in about 1775, not as modern states with adjustments. **They stop at the Appalachian frontier.** The country west of the mountains was claimed on paper — several charters ran to the Mississippi — but it was not settled colony, and it is left out. That is why New York ends partway across the modern state, why Pennsylvania and Virginia are cut off short of the Ohio, and why the Carolinas and Georgia do not reach their modern western lines.

Inside the frontier:

- **Maine is part of Massachusetts.** It was governed as part of Massachusetts until 1820, so selecting Massachusetts highlights both landmasses.
- **Vermont is part of New York.** The New Hampshire Grants were claimed by both New York and New Hampshire until the Crown ruled for New York in 1764, putting the boundary at the Connecticut River. Selecting New York highlights the Grants with it. Vermont declared itself independent in 1777 and became a state in 1791; it was never one of the thirteen.
- **West Virginia is outside the colonies**, being trans-Appalachian, even though Virginia was legally undivided until 1863.

**Show modern borders** draws the state lines of today over the top and fills the land beyond the frontier pale, so you can see what each state later took in.

Founding dates are the ones textbooks generally use. Several colonies changed hands or charters more than once, so those dates are a starting point for discussion rather than the whole story.

## Editing it

The whole thing is one file, `index.html`. Colony names, dates, and the short descriptions live in the `DATA` block near the bottom of the file, inside the `<script>` tag. Edit the text there, commit, and the live site updates in about a minute.

Just below `DATA` are `MODERN` (the state outlines the toggle draws), `MODERN_LABELS`, and `NOTE`, the paragraph in the sidebar.

## Credits

Coastlines and the borders between colonies come from [Natural Earth](https://www.naturalearthdata.com/), which is in the public domain. The Appalachian frontier — how far west each colony runs — is traced from the Wikimedia map [Map of the Thirteen Colonies, 1775](https://commons.wikimedia.org/wiki/File:Map_Thirteen_Colonies_1775.svg), georeferenced against the five cities it marks (Boston, New York, Philadelphia, Baltimore, Charleston) and then clipped against the Natural Earth coastline, so the coast stays sharp while the frontier follows the period map.

The map is drawn in the [Equal Earth](https://equal-earth.com/) projection, which is equal-area: two colonies that look the same size on the map cover the same amount of ground.
