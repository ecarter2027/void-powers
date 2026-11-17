# Void Powers: Epic Fight changelog

## 4.3.1
- Fix: Herobrine's Void Reaper trails didn't follow the blades. He holds one in each hand, the left one mirrored, but Epic Fight gives an item one trail for both hands, so whichever way it was set, one hand was wrong. In battle mode each reaper is now turned to point straight out of the fist (its own turn for each hand), so one trail runs along both blades.

## 4.3.0
- Herobrine's Void Reapers play EpicFight-Awaken's Darknight Pursuiters moveset: its own combos, dash and air attacks, guard, dual-wield style and skills.
- Requires EpicFight-Awaken 1.2.8 or later.

## 4.2.4
- Fix: Herobrine's Void Reaper trails swept round the wrong side of the player. Their sideways offset was mirrored; they now run along the blades.

## 4.2.3
- H4CK3R's Sword has its own moveset now, not Epic Fight's standard sword set: Dawn Day's reverse-grip backhand blade combo, its dash attack and its own stance (idle, walk, run), with the one-handed milady air slash. Its art, Impale, plays Dawn Day's Impaling Thrust.
- Fix: the Impale skill showed its raw name and tooltip keys, and had no icon. It has its name, a description, and its own icon (his sword, point down).
- Clones' blows follow the new moveset.

## 4.2.2
- Fix: Self-Clone made no clones with Epic Fight installed. Epic Fight failed to give them a body because their skeleton was never registered; they now use its biped skeleton.

## 4.2.1
- H4CK3R's clones fight in Epic Fight's body: its biped skeleton in your skin, its sword stance, and every cut is one of Epic Fight's sword blows (the Hacker's Sword's own moveset, worked through in order). They still fly and pick their own targets.
- Requires Void Powers 1.56.1.

## 4.2.0
- H4CK3R's Sword has an Epic Fight moveset: Epic Fight's own one-handed sword combo, dash and air slash, with its own innate skill, Impale (a giant copy of the sword drops through the creature you're looking at and pins it).
- Its swing trail runs along the blade, in his blue.
- Requires Void Powers 1.56.0.

## 4.1.2
- Fix: Epic Fight's swing trails now run along each weapon's real blade, at its exact size. They used to be a straight line out along the arm, which missed hooked and offset blades. The worst cases were Herobrine's Void Reaper, whose blade fans out to the side of the fist, and Nightmare's axes, where the trail now spans the axe head.
- Each trail runs from the guard to the tip on swords, from heel to point on the scythe and reaper, and across the head on the glaive, staff and axes. The positions were measured in game by drawing every weapon through Epic Fight's own held-item placement (the TrailProbe dev tool; it runs when a `vpef_trail_probe` file appears in the game folder).
- Requires Void Powers 1.55.10.

## 4.1.1
- Fix: Herobrine's one-handed Void Reaper skill crashed the game. It borrowed Weapons of Miracles' Moonless "Lunar Eclipse", which only works with the Moonless's own skill; it now uses the Dawn Day "Greater Harvest" scythe skill.

## 4.1.0
- Claire's pistol plays Weapons of Miracles' Ender Blaster gun moveset: its one-handed set with one pistol, and the two-handed set with a pistol in each hand. Its stance, walk and run come from the Ender Blaster too.
- A second pistol in the off hand is now drawn in battle mode (the pistol allows an off-hand weapon).
- Requires Void Powers 1.50.0.

## 4.0.2
- Chaos' and Entity 303's innate skills now use real attack animations.

## 4.0.1
- Fixed a crash while loading: an innate skill pointing at a non-attack animation no longer stops the game's data from loading.

## 4.0.0
- All of this mod's own Epic Fight animations are gone. Every weapon now plays real animations from Epic Fight, Weapons of Miracles, Epic Fight Extra and Dawn Day, with no attack set shared between weapons.
- Now requires Weapons of Miracles, Epic Fight Extra and Epic Fight: Dawn Day to be installed. Requires Void Powers 1.48.0.

## 3.10.0
- Stances narrowed and the feet stay under the body: no more splits on attacks, and no bending backward. Requires Void Powers 1.47.0.

## 3.9.2
- Vlad's innate skill reworked so the glaive's shaft stays clear of his body.

## 3.9.1
- Teufel's fourth attack and Teufel's and Vlad's innate skills no longer pass the shaft through the body for a frame.

## 3.9.0
- Every weapon's Epic Fight moveset and innate skill rebuilt pose to pose, each with its own stance, reach, tempo and string of blows. Requires Void Powers 1.46.0.

## 3.8.0
- Claire's pistols aim along the barrel instead of pointing at the sky.
- Herobrine's Void Reaper daggers now lead with the correct side in Epic Fight.
- Weapon arts no longer play cutscenes. Requires Void Powers 1.45.0.

## 3.7.0
- Herobrine's Void Reaper movesets (one reaper and twin reapers) rebuilt from scratch, pose to pose, and no longer identical to Teufel's scythe attacks. Requires Void Powers 1.44.0.

## 3.6.0
- Every weapon's attacks reworked: the blade lags the hand and then whips through, the lead knee drives up with each step, the body drops into the blow and rebounds, the free arm counterbalances, and hands slide along long grips.
- No weapon passes through the torso any more: the last clipping attacks (Teufel, Vlad, Chaos, Derek and the Reaper art) are fixed, with a collision pass in the animation generator.
- Blows landing on a guard shove the body back harder.
- H4CK3R's HUD follows the head in battle mode. Requires Void Powers 1.43.0.

## 3.5.1
- **Fix: Arcs and other worn arm pieces stuck at the player's side in battle mode** (Teufel's Arc, Orion's gauntlet, the burning fists, and the rest). Epic Fight sometimes put its own stand-in for those pieces in first: an un-animated copy pinned at the hip. They now always ride the animated arm. The same goes for Herobrine's and Entity 303's transformed bodies.

## 3.5.0
Needs Void Powers 1.42.2 or newer.
- **Every weapon has its own innate skill (weapon art)**, replacing Epic Fight's stock ones, with its own animation. Each blow throws out Void Powers effects in the weapon's colour as it lands: crescents, rings of blades, shockwaves and craters, sonic booms. Some examples: Nathan's Verdant Ascension, Leo's Lion's Gale, Vain's Thousand Cuts, Orion's Meteor Knuckle, Claire's Gun Kata. The dual-wielding sets have arts of their own too (Twin Gale, Shadow Flurry, Reaver's Frenzy, ...).
- **Cutscenes for the heaviest arts:** Chaos (Cataclysm), Kuro (Buster Hurricane), Teufel (Soul Harvest), Vlad (Blood Moon), Nightmare (Dread Guillotine), Entity 303 (Weeping Requiem) and Herobrine (Void Reaping, Twin Eclipse) get the ultimate-style cinematic, titled with the art. It's off with Void Powers' Move cinematics setting.
- **Every weapon guards its own way.** Each moveset has its own held guard, its own reaction to a blocked hit and two parries of its own (the blow beaten aside one way, then the other). Some examples: Daemon fences side-on with the point at the face, Kuro plants his buster sword like a shield, Entity 303 rests the greatsword on his shoulder, Teufel holds the scythe hooked over his shoulder, Fleur holds the staff level across her chest. With Epic Fight's Parrying skill, Void Powers spears, scythes, greatswords and axes can now parry too.
- **Livelier attacks.** Every attack winds up further, follows through further and steps in further. The stances sink deeper, and the hips, waist, chest and head all twist and roll into each blow, with an overshoot as the body settles. The free hand swings against the blow.
- **Fix: polearm shafts no longer pass through the body.** Vlad's glaive, Teufel's scythe, Fleur's staff and Herobrine's reaper are held to the right of the body, so the shaft runs past the side. Their straight-ahead thrusts are replaced with cuts.

## 3.4.2
- **Fix: crash when blocking a hit with the Parrying skill** (and possibly the other guard skills) while holding a Void Powers weapon. The guard animations carried a root-motion track. Epic Fight treats any animation with one as a move that carries the body, which a guard can't be, so it crashed loading them. The guards no longer have that track, as Epic Fight's own don't.

## 3.4.1
- **Attacks no longer swing so low.** Every cut lands higher, at chest, shoulder or head height. Follow-throughs stop around the hips instead of sweeping down toward the feet, and the body leans into a blow without folding over it.
- **More strike angles.** New angles: steep near-vertical diagonals, shallow almost-level diagonals, level cuts at head height, steep rising cuts and thrusts at the face. Every weapon's string now changes angle from one blow to the next, and low waist sweeps are mostly gone.

## 3.4.0
- **Every battle-mode attack redone in Epic Fight's own style.** They're modelled on base Epic Fight's attacks and on those of Dawn Day, Nightfall, Awakened, Weapons of Miracles, WoM Plus and Epic Fight Extra (their timing, reach, steps and follow-through were measured):
  - Each attack is one committed blow (a finisher sometimes two).
  - The weapon is drawn well back and up, snaps through a wide arc, and is held low in the follow-through before settling back. Each blow flows out of the last one's follow-through.
  - Every blow steps the body in: heavier weapons step further, and the torso winds up and unwinds harder.
  - Each kind of weapon is timed like Epic Fight's: daggers and fists quickest, swords about 0.7 s, axes about 1 s, spears and scythes just over 1 s, greatswords slowest.
  - No more flips. Spins only on a few finishers: Leo's, Kuro's, Teufel's and the Void Reapers'.
  - Dash attacks drive in about two blocks. Air attacks come down from overhead.
- Combo lengths: Void Reaper (single and dual) 7; Teufel 6; Daemon, Chaos, Kuro, Vira-Blade (single and dual) and Nightmare (single and dual) 5; the rest 4.

## 3.3.0
- **Fix: Herobrine's and Entity 303's transformations in battle mode.** Transforming used to just draw a bigger player. Now the giant body appears, riding Epic Fight's skeleton: every limb follows Epic Fight's animations, and the elbows and knees bend as Epic Fight bends them. Epic Fight's own body is hidden piece by piece as the transformation assembles. Armour, capes and held items are hidden under it, as outside battle mode.
- **Fix: weapon trails while transformed.** The trail now comes off the giant body's own blade, at its size and where it really is, through each Epic Fight cut. Epic Fight's own trail is left out for transformed players, because it was drawn at a normal player's size and position.

## 3.2.0
- **Every weapon guards its own way** (Epic Fight's guard, held on right-click in battle mode):
  - One-handed blades: angled up across the body, the free hand braced behind the flat.
  - Greatswords: two-handed, slanted across in front.
  - Scythes, the spear and the staff: the shaft braced across the chest.
  - Twin blades: crossed in an X.
  - Fists and pistols: forearms raised before the face.
  - A blow landing on the guard jolts it: the weapon is driven back toward the body, the body shoved back and the knees giving, then the guard is set again.
  - Only Void Powers weapons use these. Other mods' weapons keep Epic Fight's own.
- **Everything can guard:** Vain's dagger, Orion's gauntlet, the Fire Hand and Claire's pistols now count as swords to Epic Fight (its guard doesn't cover daggers or fists).
- **Longer combos (more attacks):**
  - The Void Reaper: seven attacks, adding a thrust-and-cut, a low sweep into a rising leap, and a spinning double cut.
  - The twin reapers: seven too.
  - Teufel's scythe: six.
  - Kuro's sword, Chaos' sword, Nightmare's axes (and the dual set) and the Vira-Blade: five each.
- **Fix:** the Void Reaper's own moveset was replaced by the twin reapers' set. They shared a style, so the dual set overwrote it. Each now has its own.

## 3.1.0
- **Weapon trails in battle mode:** every attack now lights its weapon's trail through each of its sweeps, in the weapon's own colour, on whichever hand swings it (both in the dual-wielding sets). The trails show for every blade, the gauntlet and the Fire Hand.
- **More diagonal cuts:** most of the plain cuts in every moveset are now diagonals (high to low and low to high, both ways). Spins stay level, and the leaping slams and flips still come straight down.
- **Fix:** the Arcs, Orion's gauntlet and Fleur's armour in battle mode could be mirrored across the arm. They're now placed exactly as Epic Fight places its own pieces (the bone's pose, an offset, and Minecraft's flipped model axes), with nothing flipped on top.

## 3.0.0
- **Right-click guards in battle mode:** with any Void Powers weapon, right-click is now Epic Fight's guard instead of the weapon's Void Powers skill. Out of battle mode the skills work as before. Needs Void Powers 1.41.3 or later.
- **Fancier movesets, in the style of Epic Fight: Dawn Day, Epic Fight: Awakened and Weapons of Miracles.** Every attack is now a string of beats, each landing its own blow:
  - **Multi-hit strings:** double and triple cuts in a single attack, combinations of punches, flurries of thrusts.
  - **Spinning cuts:** the whole body turns right round (once or twice) with the blade held out, the arms and the blade carried round with it.
  - **Diagonal cuts** (high right to low left, high left to low right, and both rising ones) and **thrusts** driven out from the hip.
  - **Leaping slams:** up into the air and crashing down onto the target.
  - **Air attacks with a flip:** a full front somersault into a chop.
  - **Dash attacks** that lunge in with a thrust, a spinning sweep or a chop.
- **Every weapon's own choreography:**
  - Nathan: quick cuts, a double, a spinning cut, a leaping slam.
  - Daemon: a fencer's thrusts and high cuts.
  - Leo: low spinning sweeps.
  - Derek: heavy diagonals and a spinning cleave.
  - Chaos: crushing blows and a big leaping slam.
  - Kuro: huge sweeping arcs and spins.
  - Vain: flurries of thrusts.
  - Teufel: low reaping spins, ending in a double spin.
  - Vlad: thrusts at full reach and a crashing leap.
  - Fleur: graceful spins with the staff.
  - The Vira-Blade: quick and flowing.
  - Nightmare's axes: savage chops.
  - The Weeping Greatsword: slow and crushing.
  - The Void Reaper: sweeping and spinning.
  - Orion and the Fire Hand: jab-cross combinations, a spinning backfist and a leaping hammer fist.
  - Claire: alternating shots and a spinning double shot.
  - The dual-wielding sets trade blows between the hands, then strike with both, spin, and leap.
- Spins turn about two-fifths of a second a turn, so even the double spins stay smooth.

## 2.2.1
- **Fix: every move faced backwards.** The player reached behind themselves and cut into their own back, because the moves were solved with forward pointing the wrong way. Epic Fight's skeleton faces the other way from what they assumed (its own attacks swing the blade and carry the body that way). Every move now faces forward: the cuts go out in front, the body bends forward into a chop, and punches drive straight ahead.
- **Fix:** Orion's gauntlet, the Arcs, the burning fists and Fleur's armour in battle mode were placed with the same mix-up (mirrored front to back). They now face the right way on the arm and chest.

## 2.2.0
- **Fix: the moves no longer twist and deform the body.** Each arm is now a proper hinge: the upper arm and forearm share the elbow's axis, so the arm only ever bends at the elbow and never twists against itself. In 2.1.0 the two were turned separately, which wrung the skin at the shoulder and elbow, and through some poses the arm could roll right over in a single frame.
  - Which way the elbow points now follows the reach the way a real arm does: down when reaching forward, forward when the hand is overhead, back when it hangs. It changes smoothly through every pose and never flips to the other side of the arm.
  - Wind-ups and recoveries carry the hand round the shoulder instead of straight through it, so the arm never folds flat.
  - A weapon's edge keeps facing the same way from moment to moment, so the weapon never spins in the hand.
  - Overhead chops are drawn back above and slightly in front, not behind the head.
  - The free hand rests in a natural spot by the hip.
  - The polearms' rear hand sits a little further up the shaft.
- The animations have three times as many keyframes, so the fastest cuts stay smooth.

## 2.1.0
- **Every moveset redone, from the weapon out:**
  - Each cut is now a real arc in space: the grip sweeps round a circle in front of the body (side to side, or up and down), with the blade pointing out along the arc and its edge leading. Every swing is one clean, flat sweep.
  - The arms follow the weapon. Each arm is solved to the grip, so shoulders, elbows and wrists bend naturally (no more stiff, straight-armed swings). Two-handed weapons are really held in both hands, on the same handle: a hand's width apart on the swords, wider apart on the scythes, the spear and the staff.
  - The body drives each blow in sequence: the hips turn first, then the waist, then the chest, and the arm whips through last. The weight rocks back onto the rear leg as the blade is drawn, then the front foot steps in with the knee bending into it.
  - The blade carries on past the target, then the body eases back to its guard.
  - A downward chop rears back and bends over into the blow, and a rising cut leans back as it comes up.
  - The free hand swings the other way for balance.
- **Punches** (Orion's gauntlet, the Fire Hand) are thrown the same way: the hips and shoulders drive the fist out of its guard by the chin, the elbow straightening as it lands. Hooks sweep round bent, and uppercuts drive up from low.
- The same weapons, cuts and dual-wielding sets as 2.0.0.

## 2.0.1
- **Fix:** every moveset laid the player flat on their back. The animations' root was turned from Blender's axes to Minecraft's twice, once by the root-motion track and again by the body itself. Now only the root-motion track turns it, as in Epic Fight's own attacks, so the player stands and fights upright.

## 2.0.0
- **Every weapon has its own Epic Fight moveset** (no more borrowed ones). Each set is four combo attacks, a dash attack and an air attack, made for that weapon (144 animations in all). Each weapon also has its own Epic Fight weapon type: hit box at its real length, swing and hit sounds, a special skill, and a stance for the bigger weapons.
  - They're built like Void Powers' own attacks: clean cuts, side to side or straight up and down, the whole body driving each one. Epic Fight's skeleton adds real elbows and knees (the arm draws back bent and straightens through the cut, the knees soften into the step), and a wrist that turns the blade flat for a sideways cut.
  - Swords: Nathan (quick and clean), Daemon (cuts from high), Leo (fast and loose, low sweeps), the Vira-Blade (quick and flowing).
  - Heavy two-handers: Derek's black blade, Chaos' great sword (crushing, the whole body behind each blow), Kuro's buster sword (huge sweeping arcs), Entity 303's Weeping Greatsword (slow and crushing).
  - Polearms, each two-handed: Teufel's scythe (wide, low reaping sweeps), Vlad's spear (sweeps at full reach, then a crashing chop), Fleur's staff, Herobrine's Void Reaper.
  - Vain's dagger: tight, fast arcs.
  - Nightmare's axes: savage chops.
  - Orion's gauntlet and the Fire Hand: real punches (jab, cross, hook, uppercut), the elbow bent back and snapping straight.
  - Claire's pistols: aimed shots with a kick of recoil.
- **Dual wielding:** with a second of the same weapon in the off hand, these get a dual-wielding set where the hands trade cuts, then both strike together: Nathan's, Daemon's and Leo's swords, Vain's dagger, the Vira-Blade, Nightmare's axes and the Void Reaper.
- **Special skills** are Epic Fight's own, picked per weapon: Sweeping Edge, Dancing Edge (dual), Rushing Tempo, Steel Whirlwind, Eviscerate, Blade Rush (dual daggers), The Guillotine, Grasping Spire, Heartpiercer and Relentless Combo.
- **Weapons of Miracles is no longer needed** (only Epic Fight).

## 1.2.1
- **Fix:** Orion's gauntlet, its flames and embers, the Arcs, the burning fists and Fleur's armour now sit exactly on the arm in battle mode, and bend and twist with the forearm. 1.2.0 placed them from the joint positions, but Epic Fight's hand joint starts at the elbow, so the forearm's direction came out empty and the pieces landed in the wrong place. Each piece now rides its bone directly: the forearm, or the chest for Fleur's armour.
- The flames and embers stream from the fist up the forearm in every Epic Fight animation, whatever way the arm is turned.

## 1.2.0
- **Void Powers' arm and body pieces show in battle mode:** Epic Fight draws you with its own animated body in battle mode and was leaving out Void Powers' own pieces. These are now placed on Epic Fight's body, following the forearm as it moves:
  - the Arcs on the forearm
  - Orion's 3D gauntlet with its flames and embers
  - the Chosen One's burning fists
  - Fleur's Aegis shield and Combat Form armour
- Needs Void Powers 1.41.1 or later.

## 1.1.0
- **Epic Fight swing trails for every weapon:** each Void Powers weapon leaves an Epic Fight swing trail in its own colour, running from the guard to the tip at the weapon's real length. Short trails follow the pistols, Orion's gauntlet and the Fire Hand.
- **Epic Fight animates your stances in battle mode:** Void Powers' own idle, walking, running, sneaking and flying animations stand aside, so only Epic Fight's play.
- Needs Void Powers 1.41.0 or later.

## 1.0.0
- **First release.** An addon for Void Powers (1.40.1 or later) that gives every Void Powers weapon an Epic Fight moveset. It needs **Epic Fight** (20.14 or later) and **Weapons of Miracles** (2.0 or later).
- Each weapon uses a full moveset (combos, dash and air attacks, guard and its special skill) from Epic Fight or Weapons of Miracles that fits it:

| Weapon | Moveset |
|---|---|
| Nathan's sword | Herrscher (WoM): quick, light sword work |
| Daemon's sword | Longsword (Epic Fight) |
| Leo's sword | Satsujin (WoM): draw-cut katana style |
| Derek's sword | Evil Odachi (WoM) |
| Chaos' great sword | Solar (WoM) |
| Kuro's buster sword | Ruine (WoM) |
| Vain's dagger | Dagger (Epic Fight), dual-wields too |
| Teufel's scythe | Antitheus (WoM): the reaper's scythe |
| Vlad's spear | Agony (WoM): the gravity-defying spear |
| Fleur's staff | Staff (WoM) |
| Claire's pistols | Ender Blaster (WoM): gun-kata |
| Orion's gauntlet | Clawed Gauntlet (WoM) |
| The Dark Lord's Vira-Blade | Moonless (WoM) |
| Nightmare's axe | Torment (WoM) |
| Entity 303's Weeping Greatsword | Greatsword (Epic Fight) |
| Herobrine's Void Reaper | Antitheus (WoM) |
| The Chosen One's Fire Hand | Fist (Epic Fight) |

- **No double swings:** while you're in Epic Fight's battle mode, Epic Fight does the fighting and Void Powers' own weapon and character combos stand aside. In Epic Fight's vanilla (mining) mode, Void Powers fights as usual. Your powers, dashes and the weapons' right-click skills work in both.
