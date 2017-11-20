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

part: **rt_beam_outer_casing**  
makes: rivtech_beam_sword  
tools: glare protection, welding, fine metal sawing, fine screw driving  
components: superalloy sheet x1 + scrap metal x5 + electronic scrap x5 + copper wiring x20 + beamsword controls

part: **rt_beam_controls**  
makes: rt_beam_outer_casing  
components: RAM x4, processor board x1, plastic chunk x2, small storage battery x1, small LCD screen x1, copper wire x2, superglue x1

part: **rt_power_assembly**  
makes: rivtech_beam_sword  
tools:  
components: Power Cell, Field Conductor, Vortex Ring, Power Insulator, Energy Gate, Recharge Socket  

part: **rt_power_cell**  
makes: rt_power_assembly  
components: plutonium cell x1, power converter x4, amplifier circuit x2, scrap metal x3, copper wire x10  

part: **rt_field_conductor  
makes: rt_power_assembly  
tools: plastic mold  
components: copper x100, power converter x1, signal receiver x2, plastic chunk x4  

part: **rt_vortex_ring**  
makes: rt_power_assembly  
components: silver x100, signal receiver x1, RAM x4, electronic scrap x2

part: **rt_power_insulator**  
makes: rt_power_assembly  
components: ceramic shard x6, power converter x1, copper wire x20, superalloy x1

part: **rt_energy_gate**  
makes: rt_power_assembly  
components: amplifier circuit x4, hydrogen canister x1, silver x100, superalloy x1
^^^chems instead of hydrogen

part: **rt_recharge_socket  
makes: rt_power_assembly    
components: processor board x2, amplifier circuit x2, UPS x1, scrap metal x2, pipe x1

---
####rt_blade_emitter

		[[ "rt_blade_channel", 1 ]],
			acid coated in something to handle the blade, metals
			welding, chemistry, tongs, metal sawing
			metal chunk 4, chem_acetic_acid 20, oxy_powder 20, chem_thermite 5
			
		[[ "rt_cycling_field", 1 ]],
			fine screw, soldering
			e_scraps 1, solder_wire 1, amplifier, solar cell
			
		[[ "rt_modulation_circuit", 1 ]],
			electronics to focus the blade
			fine screwing, soldering iron
			e_scraps 5, solder_wire 10, cable 4, amplifier 1, processor 1, silver 4
			
		[[ "rt_focusing_lens", 1 ]],
			lens to focus the blade
			fine screwing, SAW_M_FINE
			diamond, e_scraps 1, scrap copper 1, ceramic shard
			
		[[ "rt_emitter_matrix", 1 ]],
			silver, gold and plutonium slurry in a mold and extracted
			chemistry, glare 1, tongs, plastic mold
			e_scraps, silver, gold, slurry, plastic chunk
			
		[[ "rt_flux_aperture", 1 ]]		
			 small electric motor recipe?
			 hammering, screwing, soldering iron 5
			 scrap metal, scrap copper, cable, power_supply
			
			