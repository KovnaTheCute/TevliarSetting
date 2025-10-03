#Statblock 
```statblock 
layout: Basic 5e 
name: Arcane Hydra
size: Huge
type: Monstrosity
alignment: Neutral
ac: 17 (Natural Armor)
hp: 280
hit_dice: 20d12 + 140
speed: 30 ft., swim 30 ft.
stats: [23, 12, 24, 2, 12, 20]
saves: 
- Strength: +10
- Constitution: +11
- Intelligence: 0
- Wisdom: +5
skillsaves: 
- Perception: +7
damage_resistances: Bludgeoning, Piercing, and Slashing from non-magical attacks
condition_immunities: Charmed, Frightened, Paralyzed, Poisoned
senses: Darkvision 60 ft., passive perception 15
languages: -
cr: 18
traits: 
- name: Mult-Headed.
  desc: "The Arcane Hydra has seven heads. It can make a number of bite attacks equal to the number of heads it has. If the hydra takes 40 damage in one turn then a head dies. The Hydra can regrow all lost heads at the start of its next turn unless it’s under the effect of an anti-magic field. When a head is regrown the Hydra releases a burst of magical energy dealing 44 (10d8) force damage to all creatures within 10 ft of it per head grown back."
- name: Magic Resistance.
  desc: "The Arcane Hydra has advantage on saving throws against spells and other magical effects."
- name: Legendary Resistance (3/day).
  desc: "If the Hydra fails a saving throw, it can choose to succeed instead."
actions: 
- name: Multiattack.
  desc: "The Hydra can make one attack for each head it has. Each head can either make a bite attack or cast the spell tied to it. The Hydra can use one of its heads to use elemental breath once per multi attack, that head cannot use the bite or spell associated with it."
- name: Bite.
  desc: "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 22 (4d8 + 6) piercing damage."
- name: Spell Attacks.
  desc: "Each head has a different spell associated to it as follows: <br> - Red Head (Evocation): Fireball. A bright streak flashes from the Arcane Hydras mouth to a point it chooses in range and blossoms with a low roar into an explosion of flame. Each Creature in a 20ft radius must make a DC 19 DEX saving throw. A target takes 35 (10d6) fire damage on a failed save, or half as much on a successful one. The fire spreads around corners. It ignites flammable objects in the area that aren't being worn or carried. <br><br> - Blue Head (Enchantment): Dissonant Whispers. The Arcane Hydra whispers a discordant melody that only one creature of its choice within range can hear, wracking it with terrible pain. The target must make a DC 19 WIS saving throw. On a failed save, it takes 24 (7d6) psychic damage and must immediately use its reaction, if available, to move as far as its speed allows away from the arcane hydra. The creature doesn’t move into obviously dangerous ground, such as a fire or a pit. On a successful save, the target takes half as much damage and doesn’t have to move away. A deafened creature automatically succeeds on the save. <br><br> - Green Head (Necromancy): Blight. Necromantic energy washes over a creature of the hydras choice that it can see within range, draining moisture and vitality from it. The target must make a DC 19 CON saving throw. The target takes 40 (9d8) necrotic damage on a failed save, or half as much damage on a successful one. This spell has no effect on undead or constructs. If the hydra targets a plant creature or a magical plant, it makes the saving throw with disadvantage, and the spell deals maximum damage to it. If the hydra targets a nonmagical plant that isn't a creature, such as a tree or shrub, it doesn't make a saving throw, it simply withers and dies. <br><br> - Purple Head (Transmutation): Magnify gravity. The gravity in a 10-foot-radius sphere centered on a point the Arcane Hydra can see within range increases for a moment. Each creature in the sphere on the turn when it casts the spell must make a DC 19 CON saving throw. On a failed save, a creature takes 27 (6d8) force damage, and its speed is halved until the end of its next turn. On a successful save, a creature takes half as much damage and suffers no reduction to its speed. <br><br> - Black Head (Illusion): Fear. The arcane Hydra projects a phantasmal image of a creature’s worst fears. Each creature in a 30-foot cone must succeed on a DC 17 Wisdom saving throw or use their reaction to use all their movement moving away from the arcane hydra by the safest available route. <br><br> - White Head (Abjuration): Dispel Magic. The Arcane Hydra chooses one creature, object, or magical effect within range. Any spell of 5th level or lower on the target ends. For each spell of 6th level or higher on the target, make an ability check using your spellcasting ability (+9). The DC equals 10 + the spell's level. On a successful check, the spell ends. <br><br> - Yellow Head (Conjuration): Misty Step. Briefly surrounded by silvery mist, The Arcane Hydra teleports up to 30 feet to an unoccupied space that it can see."
- name: Elemental Breath (Recharge 5-6).
  desc: "The Arcane Hydra exhales a breath of elemental magic in a 30-foot cone. Each creature in that area must make a DC 20 Dexterity saving throw, taking 63 (14d8) damage of a type depending on the head on a failed save, or half as much on a successful one. The damage type is determined as follows: <br> - Fire (Red Head) <br> - Cold (Blue Head) <br> - Necrotic (Green Head) <br> - Force (Purple Head) <br> - Poison (Black Head) <br> - Radiant (White Head) <br> - Thunder (Yellow Head)"
legendary_actions: 
- name: Arcane Blast.
  desc: "The Hydra uses one of its heads to create a blast of arcane energy, making a ranged spell attack against a creature within 60 feet. On a hit, the target takes 22 (4d10) force damage, and the Hydra can push the target up to 15 feet away from it."
- name: Elemental Surge.
  desc: "The Hydra unleashes a burst of elemental energy in a 15-foot radius around itself. Each creature in that area must make a DC 19 Dexterity saving throw, taking 22 (4d10) damage of a type based on the heads that are currently active. The Hydra can choose one of the elemental types available from its heads. <br> - Fire (Red Head) <br> - Cold (Blue Head) <br> - Necrotic (Green Head) <br> - Force (Purple Head) <br> - Poison (Black Head) <br> - Radiant (White Head) <br> - Thunder (Yellow Head)"
- name: Spell Echo (Costs 2 Actions).
  desc: "The Hydra can use one of its heads to cast a spell from any other head. This can include spells from heads that have died."
- name: Arcane Static (Costs 3 Actions).
  desc: "The Hydra unleashes a wave of arcane energy that interferes with spellcasting. Until the start of the hydras next turn a 30ft area around the hydra becomes an antimagic field."
```

### Description:
Legends speak of hydras as horrors of regeneration, ever-sprouting new heads when struck down. Yet in lands saturated with raw magical energy, a hydra’s curse mutates into something far stranger. These warped beasts, called arcane hydras, are born when the chaotic resonance of magic overwhelms a hydra’s natural regenerative power. Instead of endless heads, these monsters manifest spell-wrought maws—each capable of channeling destructive sorcery.

**Spawn of Arcane Excess.** An arcane hydra often lurks where the fabric of magic is frayed: near unstable portals, in the ruins of ancient wizard-empires, or across lands blighted by planar rifts. Over decades, a common hydra bathed in such energy undergoes a dreadful transformation. Its regenerative capacity twists into magical overgrowth—heads no longer sprout infinitely, but each remaining one develops its own arcane nature. These heads breathe fire, shadow, or radiance, and unleash spells with beastial instinct rather than calculated intent.

**Beast, Not Sorcerer.** Despite their spellcasting power, arcane hydras retain the animalistic cunning of their kin. They are not spellcasters in the true sense, but predators that lash out with whatever destructive force their heads embody. One head might belch fire, another exhale necrotic mist, while a third lashes out with the force of raw gravity. Their savagery makes them no less dangerous than the cleverest wizard, for they wield their power without restraint.

**Apex Hunters of Magic-Drowned Lands.** Few creatures can challenge an arcane hydra in its chosen territory. They are as comfortable hunting in deep swamps as they are in shattered ruins or flooded arcane sinkholes. Prey fleeing into rivers or lakes finds no reprieve—arcane hydras swim with ease, unleashing elemental breath and teleporting through silvery mist to close the distance. Even veteran adventurers who underestimate these beasts soon learn that brute force alone cannot triumph where sorcery itself fights back.

**DM’s Note:**
The arcane hydra is a unique twist on the classic hydra encounter, giving DMs a way to merge high-level magic with primal monstrosity. Place one in regions where raw arcane energy has warped the land: perhaps near a collapsed leyline, the ruins of a mythal, or a battlefield where archmages once clashed. This monster shines as a centerpiece encounter for high-level parties—it forces adventurers to adapt to unpredictable magical assaults while wrestling with its legendary durability. Unlike its mundane kin, this hydra can counter spellcasters just as easily as it shreds warriors, making it a threat to every member of the party.