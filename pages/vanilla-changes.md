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
* gfx\portraits\portrait_modifiers\00_animation_props.txt

### accessory variations
..clothes won't feature CFP patterns.
* gfx\portraits\accessory_variations\catholic.txt
* gfx\portraits\accessory_variations\sub_saharan.txt

### CUSTOM files
..barbershop incompatibility.
* gfx\portraits\portrait_modifiers\00_custom_cloaks.txt
* gfx\portraits\portrait_modifiers\00_custom_clothes.txt
* gfx\portraits\portrait_modifiers\00_custom_hair.txt
* gfx\portraits\portrait_modifiers\00_custom_headgear.txt
* gfx\portraits\portrait_modifiers\00_custom_legwear.txt
* gfx\portraits\portrait_modifiers\00_custom_special.txt

# Overwritten classes
..major clothing assignement disfunctions
'portrait_mena_clothing_contents_trigger' for database 'common/scripted_triggers' in ' file: common/scripted_triggers/CFP_clothing_triggers.txt'
'portrait_african_clothing_contents_trigger' for database 'common/scripted_triggers' in ' file: common/scripted_triggers/CFP_clothing_triggers.txt'
'portrait_era2_armor_trigger' for database 'common/scripted_triggers' in ' file: common/scripted_triggers/CFP_clothing_triggers.txt'
'portrait_era3_armor_trigger' for database 'common/scripted_triggers' in ' file: common/scripted_triggers/CFP_clothing_triggers.txt'
'portrait_era4_armor_trigger' for database 'common/scripted_triggers' in ' file: common/scripted_triggers/CFP_clothing_triggers.txt'
'create_artifact_joyeuse_effect' for database 'common/scripted_effects' in ' file: common/scripted_effects/CFP_historical_artifacts_creation_effect.txt'
'western' for database 'gfx/court_scene/scene_cultures' in ' file: gfx/court_scene/scene_cultures/CFP_scenes_cultures.txt'
'mediterranean' for database 'gfx/court_scene/scene_cultures' in ' file: gfx/court_scene/scene_cultures/CFP_scenes_cultures.txt'
'mena' for database 'gfx/court_scene/scene_cultures' in ' file: gfx/court_scene/scene_cultures/CFP_scenes_cultures.txt'
'jester' for database 'gfx/court_scene/character_roles' in ' file: gfx/court_scene/character_roles/cfp_default_roles.txt'
'fp2_2p_chess_board' for database 'common/artifacts/visuals' in ' file: common/artifacts/visuals/CFP_redefined.txt'
'pedestal_crown_iron' for database 'common/artifacts/visuals' in ' file: common/artifacts/visuals/CFP_redefined.txt'
'wall_shield' for database 'common/artifacts/visuals' in ' file: common/artifacts/visuals/CFP_redefined.txt'
'skull_goblet' for database 'common/artifacts/visuals' in ' file: common/artifacts/visuals/CFP_redefined.txt'
'theocracy_government' for database 'common/governments' in ' file: common/governments/CFP_government_types.txt'
'spymaster' for database 'gfx/portraits/portrait_animations' in ' file: gfx/portraits/portrait_animations/animations.txt'