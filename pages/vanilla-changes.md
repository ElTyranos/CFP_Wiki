---
layout: default
---

# Edited vanilla files

Community Flavor Pack edits several vanilla files.
Last loaded mod will overwrite the files of the other one.

Editing these files in your mod without [compatibility patch](/troubleshooting/in-compatibilities) will lead to...



# In common folder
## In common\genes
..AI won't be able to wear what `portrait_modifiers` asks it to wear and appear naked.
* common\genes\02_genes_accessories_misc.txt
* common\genes\03_genes_special_accessories_hairstyles.txt
* common\genes\04_genes_special_accessories_beards.txt
* common\genes\05_genes_special_accessories_clothes.txt
* common\genes\06_genes_special_accessories_headgear.txt
* common\genes\07_genes_special_accessories_misc.txt
* common\genes\08_genes_special_visual_traits.txt

## In common\ethnicities
..will remove skin color tweaks for africans
* common\ethnicities\01_ethnicities_african.txt
* common\ethnicities\01_ethnicities_east_african.txt



# In gfx folder
## Court scenes
..breaking royal courts
* gfx\court_scene\scene_settings\grandeur_levels\grandeur_levels.txt

## In units
..breaking the viking longship on strategical map.
* gfx\models\units\entity_links\00_fleet_entity_links.txt

## In portraits
### modifiers files
..AI won't be able to wear anything from CFP.
* gfx\portraits\portrait_modifiers\01_animation_props.txt
* gfx\portraits\portrait_modifiers\01_beards.txt
* gfx\portraits\portrait_modifiers\01_cloaks.txt
* gfx\portraits\portrait_modifiers\01_clothes.txt
* gfx\portraits\portrait_modifiers\01_hairstyles.txt
* gfx\portraits\portrait_modifiers\01_headgear.txt
* gfx\portraits\portrait_modifiers\01_legwear.txt

### accessory variations
..clothes won't feature CFP patterns.
* gfx\portraits\accessory_variations\catholic.txt
* gfx\portraits\accessory_variations\sub_saharan.txt

### CUSTOM files
..barbershop incompatibility.
* gfx\portraits\portrait_modifiers\01_custom_cloaks.txt
* gfx\portraits\portrait_modifiers\01_custom_clothes.txt
* gfx\portraits\portrait_modifiers\01_custom_hair.txt
* gfx\portraits\portrait_modifiers\01_custom_headgear.txt

# Overwritten classes
..major clothing assignement disfunctions
* portrait_steppe_clothing_contents_trigger
* portrait_mena_clothing_contents_trigger
* portrait_african_clothing_contents_trigger
* create_artifact_joyeuse_effect
* western in gfx/court_scene/scene_cultures
* spymaster in gfx/portraits/portrait_animations