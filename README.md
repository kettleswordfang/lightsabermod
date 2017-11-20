# lightsabermod
CDDA Lightsaber Construction

kyber crystals : basic + electric, flame, defensive?  
electric would protect you from electricity, flame ignites on hit, defensive has mad parry ability

`rivtech_beam_sword`  
┏━━━━━━━━━━━━━━━━┛  
┣━ Outer Casing^  rt_beam_outer_casing  
┣━ Power Assembly^  rt_beam_power_assembly !!!!
┣━ Focusing Assembly  rt_focusing_assembly !!!!
┣━ Lightsaber Emitter  rt_blade_emitter^
┗━  

Beam Sword Outer Casing^  
┏━━━━━━━━━━━━━━━━┛  
┗━ Beamsaber Controls^  

Beam Sword Power Assembly^  
┏━━━━━━━━━━━━━━━━┛  
┣━ Power Cell^  
┣━ Field Conductor^  
┣━ Vortex Ring^  
┣━ Power Insulator^  
┣━ Energy Gate^  
┗━ Recharge Socket^  

Beam Sword Focusing Assembly^  rt_focusing_assembly  
┏━━━━━━━━━━━━━━━━┛  
┗━ Focusing Crystal Chamber^  "rt_focusing_chamber"  
┗━ Kyber Crystal^  "rt_crystal_shard"

Beam Sword Lightsaber Emitter^  
┏━━━━━━━━━━━━━━━━┛  
┣━ Blade Energy Channel^  
┣━ Cycling Field Energisers^  
┣━ Energy Modulation Circuits^  
┣━ Focusing Lens  (diamond)^  
┣━ Emitter Matrix^  
┗━ High Energy Flux Aperture^  

assembly:
"type": "recipe",
	"result": "rt_focusing_assembly",
	"category": "CC_ELECTRONIC",
	"subcategory": "CSC_ELECTRONIC_COMPONENTS",
	"skill_used": "fabrication",
	"skills_required": [ "electronics", 10 ],
	"difficulty": 10,
	"time": 10000,
	"book_learn": [[ "textbook_beamsword", 4 ]],
	


Beam Sword, Possible Mods - not possible with guns, will have to edit the src for this  
┏━━━━━━━━━━━━━━━━┛  
┣━ Dual-Phase Mechanism  
┣━ Lock-On Activation Switch  
┣━ Pressure Grip/Deadman’s Switch  
┣━ Force-Manipulated Switch  
┣━ Cell Recogniser  
┣━ CommLink  
┗━ Dataport

*would be a **massive undertaking** to create one*

