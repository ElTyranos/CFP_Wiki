---
layout: default
---

# Edited vanilla files

Community Flavor Pack edits several vanilla files.
Last loaded mod will overwrite the files of the other one.

Editing these files in your mod without [compatibility patch](/troubleshooting/in-compatibilities) will lead to...

# In common\genes folder
..AI won't be able to wear what `portrait_modifiers` asks it to wear and appear naked.
* common\genes\03_genes_special_accessories_hairstyles.txt
* common\genes\04_genes_special_accessories_beards.txt
* common\genes\05_genes_special_accessories_clothes.txt
* common\genes\06_genes_special_accessories_headgear.txt
* common\genes\07_genes_special_accessories_misc.txt
* common\genes\08_genes_special_visual_traits.txt

# In gfx folder
## In units
..breaking the viking longship on strategical map.
* gfx\models\units\entity_links\00_fleet_entity_links.txt

## In portraits
### modifiers files
..AI won't be able to wear anything from CFP.
* gfx\portraits\portrait_modifiers\01_beards.txt
* gfx\portraits\portrait_modifiers\01_cloaks.txt
* gfx\portraits\portrait_modifiers\01_clothes.txt
* gfx\portraits\portrait_modifiers\01_hairstyles.txt
* gfx\portraits\portrait_modifiers\01_headgear.txt
* gfx\portraits\portrait_modifiers\01_legwear.txt

### CUSTOM files
..barbershop incompatibility.
* gfx\portraits\portrait_modifiers\01_custom_cloaks.txt
* gfx\portraits\portrait_modifiers\01_custom_clothes.txt
* gfx\portraits\portrait_modifiers\01_custom_hair.txt
* gfx\portraits\portrait_modifiers\01_custom_headgear.txt
