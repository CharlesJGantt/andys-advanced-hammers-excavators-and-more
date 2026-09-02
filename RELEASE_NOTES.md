# Andy's Advanced Hammers, Excavators & More 0.1.28

Initial public release of five area-tool families for Minecraft Bedrock, across seven material tiers.

- Ships in seven tiers: Wooden, Stone, Copper, Golden, Iron, Diamond, and Netherite — 35 tools in total.
- Added **Hammers** and **Excavators** with a configurable break region — Cuboid or stair-step, up to 5 × 5 × 5, aimed at the face you hit or locked to a world plane. Both only take blocks in the same family as the block you actually hit.
- Added **Tillers** that prepare a whole 9 × 9 farm in one interaction, with three selectable plot layouts: a standard field, an optimal pumpkin and melon plot, and an optimal sugar cane plot with dug water channels.
- Added **Scythes** that sweep a 9 × 9 of vegetation, or harvest the mature crops in a 3 × 3 without resetting them and without damaging the farmland underneath.
- Added **Seeder Rakes** that plant a 4 × 4 plot from your inventory, checking real vanilla placement rules for all thirteen supported crops.
- Every tool draws a live wireframe preview of exactly what it will affect, in three colours: white for blocks that change, blue for water, green for rows a plot layout leaves open.
- Configure Hammers and Excavators by crouch-using them; Tillers and Seeder Rakes each have their own crouch-use menu. Operators get global tool toggles in the same menu, on the world settings screen, and through `scriptevent andys_excavators:set <tool> <on|off>` from a dedicated-server console.
- Fortune, Silk Touch, Unbreaking, Efficiency, and Mending all work through vanilla systems rather than reimplementations, so drops, wear, and item lifetime match a normal tool exactly.
- Containers, technical blocks, portals, and unbreakable blocks are never broken, in any pattern or area.
- Achievement compatible, verified in a cheats-off survival world with no experiments.
- Includes linked Behavior and Resource Packs with Standard graphics and Vibrant Visuals support.
