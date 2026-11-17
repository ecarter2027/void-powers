# Void Powers changelog (since 1.7.2)

## 1.56.10
- Entity 303's Weeping Greatsword attacks faster: attack speed up from 1.0 to 2.4 swings a second (still a little slower than Herobrine's reapers, for its weight). With Epic Fight, its greatsword moveset plays faster to match.

## 1.56.9
- Herobrine's Void Reapers attack much faster: attack speed up by 2 (from 1.4 to 3.4 swings a second). With Epic Fight, their Darknight Pursuiters combos play faster to match.

## 1.56.8
- Explosion impact frames scatter anime sparkles instead of jagged starbursts: four thin arms tapering to a point (the horizontal pair longer), white with a black outline, and one with a long thin streak through it.

## 1.56.7
- Weapon swing trails are just the ribbon of light: no more sparks or embers thrown off them.
- Fix: giants' beams slid past each other at an angle instead of clashing head-on. A giant's beam starts from a hand far out from its middle, so the distance at which two beams count as touching now grows with the caster's size.

## 1.56.6
- Fix: H4CK3R's Impale showed only particles, with no sword, and Weapon Formation's fan of swords vanished before firing. A flying weapon that wasn't moved through its own placement deleted itself after six ticks; both now place their swords properly.
- Weapon Formation's swords no longer burst into particles when they hit: they're just his swords, outlined in blue.
- No weapon has a cooldown any more: every weapon's right-click (the Eternal warriors' skills, Claire's pistols, the Hacker's Sword, Nightmare's axe, the Vira-Blade, the Fire Hands, the Weeping Greatsword and the Void Reaper) can be used back to back.

## 1.56.5
- Thrown and fired weapons no longer trail particles; each is just the weapon itself with a glowing outline in its move's colour. That's every move that throws or fires its own weapon: H4CK3R's Weapon Formation and Impale swords, Nightmare's thrown axe, the Vira-Blade throws and Blade Split, Vain's dagger, and Daemon's silver swords.

## 1.56.4
- H4CK3R's Sword is solid black with just a blue outline round its outer edge (no more blue lines where the blade, crossguard and grip meet); its thin edges are blue, so the outline shows from any angle.
- Far fewer particles from H4CK3R: the clones no longer glitch constantly and cut with a small burst, Telekinesis redraws its box and tether far less often, the barrier sparks less, and Weapon Formation's swords form and land without extra glitches and with thinner trails.

## 1.56.3
- H4CK3R's clones find their way: they steer round walls and over obstacles instead of flying straight into them, keep clear of the ground, never aim for a spot inside a block, and glitch-teleport to their goal if they get stuck.

## 1.56.2
- Fix: H4CK3R's Sword was invisible (in hand, in the inventory, and as the Weapon Formation and Impale swords). Its 3D model had a parent that made Minecraft build a flat item from a texture layer it didn't have.

## 1.56.1
- For addons: `HackerClone.onCut` is called each time one of H4CK3R's clones cuts (the Epic Fight addon plays its sword blows on it).

## 1.56.0
H4CK3R revamp:
- New: H4CK3R's Sword. A plain black blade outlined in his blue, with a crossguard and a short grip. He's handed it like the other characters' weapons. Swinging it plays his own five-cut sword combo; right-click is Impale: a giant copy of the sword drops point first through the creature you're looking at, into the ground, and pins it there for two seconds.
- Telekinesis (replaces Free Transform): the creature you aim at is held in the air where you look, at the distance it was, and follows your gaze until you use the ability again to let go.
- Weapon Formation: eight of his swords form in a fan behind him, hang a moment, then fire at the nearest creatures (shared out among them) and home in.
- Self-Clone: three real copies of you, in your own skin and armed with his sword, fly at whatever you're fighting (or the nearest hostile mob) for 20 seconds. Your own powers pass through them.
- Barrier: hold it and a glowing blue wall stands in front of you. Projectiles that reach it are deleted, and creatures that walk into it are pushed back.
- Terminal: DELETE: beams of his blue light lance through the creature you target from every side, and it's deleted on the spot.
- For addons: `WeaponTrails.probe` reports where a held 3D weapon's model sits.

## 1.55.11
- Fix: with a shader pack, a black hole far away (Accretion Storm's) was hidden by the sky and distant clouds, which the pack gives a depth too. Only things well in front of a hole hide it now.
- Fix: with a shader pack, a black hole more than a few dozen blocks away wasn't drawn at all, only its particles. It's now traced over the whole screen, so it shows at any distance.
- Fix: Accretion Storm's black hole could fail to appear at all, because the storm's many shockwave ripples took every lens slot first. A black hole now always gets one.
- Fix: seen from inside its reach, a black hole could be cut off by a hard diagonal edge when a camera mod steered the view. The full-screen pass now follows the view actually drawn.

## 1.55.10
- Fix: from far away, Accretion Storm's black hole showed only its particles. Effects were only sent to players within 128 blocks, so a hole that big could be out of range while still plainly in view. Effects now reach players within 256 blocks.
- For addons: `WeaponTrails.probe` reports where a held 3D weapon's model sits, so the Epic Fight addon can fit its swing trails to each blade.

## 1.55.9
- Fix: with some shader packs (Eclipse), 1.55.8's depth check made black holes lose their lensing and dark shadow. It now reads the pack's finished depth and ignores leftovers.
- Fix: Accretion Storm drew a second, smaller lens on top of its black hole, which doubled and blew out the hole's look.

## 1.55.8
- Fix: with a shader pack on, a black hole's light bending also warped players, mobs and your hand standing in front of it. Anything nearer than the hole now keeps its own light (read from the shader pack's depth).

## 1.55.7
- Herobrine's black holes are clearly audible: Event Horizon's opening, hum and collapse and Accretion Storm's roar and strikes were pitched so low they were a sub-bass rumble most speakers and headphones can't play. They're pitched up and carry further, and the Accretion Storm hole now drones while it lasts.

## 1.55.6
- Fix: with a shader pack on, the scorch marks fire moves leave on the ground showed up as big red-brown clouds. They're left out under shaders, like smoke.

## 1.55.5
- Fix: with a shader pack on, black holes couldn't be seen at all. They're now drawn over the pack's finished frame.
- Fix: with a shader pack on, explosion smoke came out as flat, opaque cream blobs. Smoke is left to the shader pack's own atmosphere; fire, sparks, debris and light are unchanged.

## 1.55.4
- With "Dash after-images" on, the after-images are the whole dash trail: the bar of light and the shock rings are left out.

## 1.55.3
- Impact frames are shorter again: the full ones about 0.7 s, the short ones about 0.26 s.

## 1.55.2
- Impact frames are a third shorter: the full ones about 1.05 s, the short ones about 0.4 s.

## 1.55.1
- Impact frames last longer, so you can take them in: the full ones about 1.6 s with more flashes and a long final hold, the short ones about 0.6 s (at most two a second).
- Every living thing near an impact frame gets a white outline while it plays, so entities always stand out of the flash (bright in the monochrome frames, black in the negatives).

## 1.55.0
- **Starbursts in explosion impact frames.** Explosive moves draw hand-drawn starbursts into their impact frames, the way animators draw them: jagged spikes of uneven length, a black outline shape round a smaller white core. One big burst sits at the blast and smaller ones scatter round it, with square debris flung out, all re-drawn on every flash.

## 1.54.1
- Impact frames: the brick-like dashed pattern in the mid-tones is gone; they shade in smooth grey.

## 1.54.0
- **Impact frames, reworked to look like your reference:** the real frame flickers through several flashes. Each is a hard monochrome grade of the scene (blacks crushed, highlights blown out and blooming, mid-tones broken into a dashed print pattern, outlines cut in), alternating with its negative and a blink of the real frame, then fading back. No more lines round the edges of the screen.
- **Fix: impact frames were black.** They were drawn under the HUD, and the HUD's vignette darkened them to black. They're now drawn over everything.
- **Many more impact frames:** big blasts, craters, lightning strikes, novas, sonic booms, implosions and large shockwaves flash a short impact frame (up to four a second). The moves that already had one keep the full version.

## 1.53.0
- **Fix: impact frames came out black.** The new explosion smoke was enormous for big blasts like the Awakening, so a near-black cloud several blocks wide sat right on the camera and covered the impact frame. Explosion smoke now billows as more, smaller puffs spread wider, and the ink and red frames show properly.
- **Black holes: a purple edge.** Light skimming the photon sphere glows in the hole's own colour round the rim of its shadow, and the cooler outer disk burns the same colour.
- **No more flashing purple round black holes.** The implosion flashes and the second, pulsing lens are gone. Matter streaming in and debris in orbit are now dust and grit.

## 1.52.0
- **Impact frames in the style of KJ's Final Ride.** The real frame is redrawn through a post shader. First comes a couple of frames of red duotone: the scene as black silhouettes on a red field, swept by speed streaks. Then about half a second of manga ink: white paper, hard black outlines, solid blacks in the shadows, hatched dry-brush strokes in the mid-tones, and dark-red hatching radiating from the hit. The strokes re-draw every few frames so they boil. A second red snap and a fade back finish it.
- **A realistic black hole, ray traced.** Every pixel's light is traced through curved spacetime around the hole, so the lensing, the black shadow, the photon ring and the disk's wrapped-over images all come from the physics. The accretion disk is a thin disk starting at the innermost stable orbit, glowing as a blackbody (white-hot inside, cooling to orange-red), with the approaching side Doppler-brightened and everything gravitationally redshifted near the hole. The sparkle particles round black holes are gone.
- **The streak lines on the ground (1.51) and the flat shockwave rings painted on the ground are gone.** Shockwaves are now the air itself: a pressure front bending light, with dust thrown out and settling.
- **Every ability's effects redone, realistic and cinematic:**
  - Blasts are real explosions: a white flash cooling into colour, a ballooning fireball (or ball of plasma for energy powers), smoke billowing up and lingering for seconds, debris thrown on arcs, and embers falling.
  - Fire burns under rising soot. Frost is ice splinters with a freezing mist that sinks. Lightning strikes flash, crack the air and leave smoke. Sonic booms form vapour cones. Slashes and crescents tear the air and shed sparks that fall. Gravity wells and implosions drag dust and debris in.
  - The cartoon star and lens-flare sprites are gone everywhere.

## 1.51.0
- **Impact frames, redone as in anime:**
  - **On the ground:** big hits score the terrain around them with streak lines. Dozens of tapered strokes shoot out from the point of impact, hugging every bump and step, with thick main streaks among hairlines, and jagged forking cracks split the ground at the centre. They flash white-hot (through the inverted frame they read as black ink lines), cool through the attacker's colour, then linger as scorch marks for a few seconds. New setting: **Impact streaks**.
  - **On screen:** dense focus lines converge on the hit, from hairlines to thick wedges, leaving a ragged clear oval round it. A jagged starburst with a broken shock ring marks the blow.
- **Black holes, reworked:** a real accretion disk, tilted as it sits in the world. It swirls round the hole with its inner edge fastest, shearing into spiral streaks, glows white-hot at the inner edge and cools outward through the hole's colour, with dark dust lanes. The side orbiting toward you burns brighter. The far half of the disk is lensed up over the top of the horizon, as in film black holes. Jets fire along the disk's axis, and long filaments of matter spiral in from far out.
- **Effect polish:** bursts now have a white-hot core, a racing shock ring, fast light streaks, tumbling sparks, falling embers and lingering smoke. Rings have a bright leading edge and rising wisps, shockwaves throw streaks along the ground (and the biggest score it), pillars have spiralling bands and a crowning flare, and shockwave ripples have a faint colour fringe.

## 1.50.0
- Dash after-images are back: the dash trail leaves translucent copies of the player's body again. The "Dash after-images" setting turns them on or off.
- The Chosen One's fire hands and Orion's gauntlet no longer use particles. Their fire is now real 3D flames: tongues of fire round the fist and forearm that rise skyward, sway, flicker and stream back as you move, white-hot at the root and red at the tips. Also in first person.
- The Vira-Blade's red lightning is now 3D bolts instead of particles.
- Claire's pistol is held the same way in Epic Fight battle mode as everywhere else, barrel out from the fist.
- Switching to the Chosen One no longer leaves you stuck in the Energy Beam pose: an entrance animation that holds its last pose is now released.
- The Chosen One's tornado touches down where you're looking (up to 48 blocks away) and stays on the ground. It used to drift up into the sky after a couple of seconds over water or a drop.
- The tornado's funnel, pull and wind all last 11 seconds. The wind is quieter and ends exactly when the tornado does. The tornado has more effects: a dust funnel inside the wind, dust rings at its foot, and debris at every height up to a cloud at the top.
- Every laser and beam boils away water and burns out lava along its path (a waterlogged block just loses its water). It follows the block-breaking setting and mob griefing.

## 1.49.1
- Herobrine's solid plates keep their full texture and jagged outlines on every face, instead of a single colour per block.

## 1.49.0
- Lasers and beams no longer instakill: every beam deals 10 damage per tick to whatever it touches.
- The Chosen One's tornado now lasts 11 seconds, effects and pull alike, and its wind sound stops the moment it ends.
- Herobrine's Void Reaper is held the right way round in third person and in Epic Fight battle mode, with its shards fanning forward from the fist the way the transformed body holds it.
- PlayerAnimator animations rolled back to how they were before the 1.44 to 1.47 rebuild. The Epic Fight animations are unchanged.
- Herobrine's transformed body is solid: every flat cut-out plate now has real thickness, and a dark core fills the gaps between them.
- Herobrine's and Entity 303's limbs join up: ball joints at the shoulders, elbows, hips and knees, and a neck, so a bent limb never opens a gap.
- Entity 303's wings have bone struts, knuckle spurs and burning veins.

## 1.48.0
- In Epic Fight battle mode, Claire's pistols and the Void Reaper are held the way real Epic Fight animations expect.

## 1.47.0
- Every animation's legs fixed: no more splits on attacks, and the lead foot no longer swaps between the wind-up and the blow.
- Characters no longer bend over backward. Every laser and beam re-posed, planted and leaning into the shot.

## 1.46.0
- Every character's PlayerAnimator set rebuilt pose to pose: stances, walks, runs, flight, dashes, attacks, weapon attacks and every move. Each character now has their own body language and tempo.
- No animation is shared between characters any more: air attacks, the chase, the form change and the transformation are each character's own, and H4CK3R has a complete set of his own instead of borrowing.

## 1.45.0
- Removed every cutscene: character entrances, ultimates and weapon arts no longer take over the camera.
- Black holes no longer distort players or mobs. They bend the land and sky only; with a shader pack on, they don't bend light at all, because entities can't be separated from the finished frame.

## 1.44.0
- Herobrine's PlayerAnimator set rebuilt from scratch, pose to pose: stances, walks, flight, dashes, every move, bare-hand and air attacks, and both Void Reaper styles. Held poses, instant strikes, full spins. His air attacks and transformation are now his own.

## 1.43.0
- New character: H4CK3R (Animator vs. Animation), unlocked after Herobrine. Energy Barrage, Free Transform, Weapon Formation, Self-Clone, Barrier and Terminal: DELETE, with flight and a teleport dash. Blue HUD over the left eye, light-blue glow and blue lightning.
- Herobrine's Void Reaper daggers are now solid: every shard has real thickness, tapering to a sharp edge.
- The Herobrine and Entity 303 transformation is now staged: the power gathers on the kneeling body, then breaks out in a flash and shockwaves, and the body surges past full size before settling.
- Herobrine and Entity 303 have their own synthesized sound effects for every move, transformation and weapon swing.

## 1.42.2
- For addons: a move cutscene hook (`Cutscene.move`), the ultimate-move cinematic with an addon's own title, subtitle and colour. Void Powers: Epic Fight 3.5.0 uses it for its weapon arts. It's off with the Move cinematics setting, like ultimates.

## 1.42.1
- **Fix: Vlad's Crimson Gate and Teufel's Abyss Dive now really sink into the ground.** The whole player model glides down through the gate and is hidden by the terrain, then shoots back up out of the other gate. It works in Epic Fight's battle mode too. Before, the animation could only lower the body a few pixels, and in battle mode not at all.

## 1.42.0
- **Teufel: Abyss Dive replaces Dark Form.** A round pool of the dark opens under her and she glides down into it. A violet line runs through the ground to her mark, a second pool opens there and drags down whoever stands over it, and she erupts out of it in a rising reap that throws everything high. The cuts it leaves burst a moment later.
- **Teufel: Eclipse Reaping replaces Hundred Portals** (her ultimate). She rises and a black eclipse opens in the sky. Every foe in the field is hoisted up into its pull and held in a ring around her. A colossal scythe falls out of it and she turns it once all the way round, reaping each foe as the blade passes. Then the eclipse collapses and slams them all into the ground.
- **Vlad's Crimson Gate: a smoother sink.** He now glides down into the gate in one unbroken motion, his arms rising overhead as he goes, and vanishes only once he's fully under. He used to drop in jerks and disappear halfway down.
- Gates can now be round as well as square (Teufel's are round).

## 1.41.5
- **New setting: Move cinematics.** It turns the cinematic camera for ultimate moves on or off: the camera swinging round, the letterbox bars and the move's title card. It's in the Settings screen and as `moveCinematics` in the client config. It used to be tied to the entrance cutscene setting, which now covers only a character's entrance.

## 1.41.4
- Herobrine's and Entity 303's transformed bodies can now be drawn on another mod's skeleton. This makes them work in the Epic Fight addon's battle mode (addon 3.3.0).

## 1.41.3
- **For addons:** `CombatHooks.handleUsesWhen` lets an addon take over a Void Powers weapon's right-click (Epic Fight's guard). While it does, the weapon's own right-click skill stands aside. This applies to every weapon: the Eternal Conflict weapons, the greatsword and reapers, the Vira-Blade, Nightmare's axes and the Fire Hand.

## 1.41.2
- **No aura particles on any character, ever:**
  - The character aura is gone everywhere: no longer drawn at all, not even during timed forms (Dark Form, Demon Form and the like) or Kuro's mode switch.
  - The constant crackle of energy round the body during timed forms and the Chosen One's ascension is gone too.
  - Forms and the ascension still burst out with their activation effects as they begin.

## 1.41.1
- **Fix (shaders):** beams, sky pillars and Vlad's gates no longer vanish against the sky or water with a shader pack on. They're drawn once the pack has finished the frame, like the swing trails and dash trails (so, like those, they show through blocks in front of them).
- **For addons:** `client.ArmSpace` lets an addon that draws the player with its own body (Epic Fight's battle mode) place Void Powers' arm and body pieces (Arcs, Orion's gauntlet and flames, Fleur's armour, the burning fists) on that body.

## 1.41.0
- **No idle particles on any character:** nobody gives off particles while just standing about any more. Gone:
  - Every character's surrounding aura (the Eternal Conflict warriors' too).
  - Nightmare's Enraged lightning.
  - The Chosen One's resting hand embers.
  - Particles still come from moves, timed forms, flight and the Chosen One's ascension.
- **The Dark Lord and Nightmare no longer ascend:** only the Chosen One has an ascended form now (the transform key does nothing for the other two), and an ascended Dark Lord or Nightmare drops out of it. Nightmare no longer flies.
- **For addons:** `CombatHooks.animateStancesWhen` lets an addon that animates players itself (Epic Fight's battle mode) take over their idle, walking, running, sneaking and flying animations.

## 1.40.1
- **For addons: a combat hook** (`com.voidpowers.api.CombatHooks`). An addon with its own combat system can claim a player's swing, and Void Powers then skips its own weapon or character combo for that swing. Used by the new Void Powers: Epic Fight addon.
- **Epic Fight weapon data moved out:** the leftover Epic Fight weapon files for the Vira-Blade, Nightmare's axe and the Fire Hand are gone from Void Powers. The Epic Fight addon now gives every weapon its moveset.

## 1.40.0
- **No more particle auras on the legends:** Herobrine, Entity 303, The Chosen One, The Dark Lord and Nightmare no longer give off a constant particle aura, including while ascended. Nightmare's Enraged lightning, the ascended crackle and the Eternal Conflict warriors' auras stay.
- **The Dark Lord's Vira-Blade is its original animated 2D sprite again** (the 3D model is gone). Its swing trail follows the sprite's blade.
- **Teufel, remade (stronger, flashier):**
  - **Abyssal Reap** (1.5s): three great crescents fanned out left, centre and right, each flying on as a wave. Everything in front is cut (12) and hooked in toward her, and the rift left in each foe bursts a moment later (7).
  - **Rift Reap** (2.5s): through a portal to behind up to five foes in turn, cutting each in an X of crescents (11). An after-image of her is left at every stop, then she portals back to where she began.
  - **Dark Form** (20s, Speed III, Strength II, Resistance): the dark bursts out of her as a ring of rifts that cuts (10) and throws back everything near, and portals open on up to six foes. In the form her blows keep opening portals.
  - **Portal Prison** (replaces Portal Strikes): a ring of portals closes round a foe. The scythe sweeps out of each in turn, faster and faster, through everything inside, then the ring collapses in on them (14) and flings them up.
  - **Demon Form** (25s, Strength IV, Resistance II, Speed II, Regeneration II, Fire Resistance): erupts as a pillar of violet fire and wings of light, with a blast that hits (12) and throws everything near into the air.
  - **Hundred Portals:** she rises as portals flood a 22-block field. Every foe is cut over and over for five seconds, then every portal collapses at once: a pillar of light and three rings of crescents tearing outward (22).
  - Demon Form now multiplies her moves by 1.5 (Dark Form by 1.2).
- **Livelier weapon attacks for the Dark Lord and Nightmare** (in the style of Better Combat):
  - The hips and shoulders wind further and the whole body turns with the cut.
  - The body leans and drops deeper, and every blow steps forward.
  - Downward chops are loaded up on the toes, and the follow-through runs longer along the cut.
  - Vira-Blade: right-to-left, left-to-right, a rising cut, a chop, and a lunging low sweep.
  - Twin Vira-Blades: the hands trade cuts, then both chop together, a rising cut, and a lunging double sweep.
  - Nightmare's axes: a chop with each axe, both swept wide, a rising rip, then a leaping double chop.

## 1.39.1
- **Weapon attacks move the whole body:**
  - Each cut starts with the weight settling, then the body rocks back as the blade is drawn: hips and shoulders wind toward it and the free arm reaches the other way for balance.
  - Then the hips lead, the shoulders follow, and the arm comes through last as the front foot lands.
  - The blade carries on a little past the target (along the same flat arc) before the body unwinds back to guard.
- **Fix:** during an attack the arms no longer follow where you're looking. That tilted them off the cut, so the arm and weapon didn't move together. The head still follows your look.
- **Fix:** Nightmare's axe attacks keep their footwork while you walk, like every other weapon attack.
- **Arms at the sides when empty-handed:** every Eternal Conflict warrior's idle, walk, run, sneak and flight stances now have their arms loose at their sides. The weapon-holding stances (Teufel's scythe across her, Vlad's spear held in front, Claire's raised pistols and the rest) play only while their weapon is in hand.

## 1.39.0
- **Every weapon attack is a clean cut:**
  - Every weapon's attacks are now built from six plain cuts only: side to side (right to left, left to right), at chest or waist height, and straight down or straight up. No twirls and no flipping the blade over mid-swing.
  - Through a cut only one angle of the arm changes, so the blade sweeps one flat arc.
  - Each attack winds up (the weight back and the hips turned about 25 degrees toward the start of the cut), cuts through with a short step, holds the follow-through, then returns to guard. The last attack of each set lunges.
- **The blade turns flat for sideways cuts:** for a side-to-side cut the weapon turns a quarter turn in the hand during the wind-up, so it sweeps level instead of standing upright. It holds still through the cut and turns back afterwards. This replaces the old wrist motion that whipped the blade around mid-swing.
- **Cleaner trails:** a weapon's trail now records only through the cut itself, not while the blade is drawn back or turning in the hand, so each trail is a single clean, flat arc.
- **Every weapon has its own attacks** (each its own five cuts in its own order, speed, weight and grip):
  - Nathan, Daemon, Leo, Derek and Chaos: one-handed swords.
  - Vain: a fast dagger with tight arcs.
  - Kuro's sword, Teufel's scythe, Vlad's spear and Fleur's staff: two-handed, both hands moving together on the grip.
  - The Vira-Blade, and the twin Vira-Blades cutting in turn and together.
  - Nightmare's twin axes: heavy chops, one axe then the other, then both.
  - The greatsword: two-handed and slow.
  - The reaper (two-handed), and the twin reapers (one in each hand).
  - Orion's gauntlet: heavy straight punches.
  - Claire's pistols: aimed shots with a kick of recoil, right, left and both.

## 1.38.1
- **Vlad's spear, as in the series:** a long black shaft outlined and banded in glowing red, a red loop at the butt, a crown of short red spikes where the head meets the shaft, and a long leaf-shaped black blade rimmed all round in red. (It replaces 1.38.0's trident head.)

## 1.38.0
- **Every animation redone, simpler and more realistic:**
  - The exaggeration pass is gone. Moves play as posed, with no extra-large swings, no whole-body travel and no oversized drops of the hips.
  - Every pose stays within a real body's range: no arm, leg, torso or head bent past where its joint can go.
  - Whole-body spins and flips are now a turn of the hips (at most about 35 degrees), keeping their direction and timing.
  - Strikes ease like real muscle: a quick cubic acceleration into the hit instead of an exponential snap, a small wind-up instead of a big one, and only a slight follow-through past the target.
  - Trembles and charging shakes are half as violent and no faster than ten times a second.
  - Sword combos: the blade is drawn back with the weight on the back foot, cut through with a short step and a natural (about 25 degree) turn of the hips, then the guard comes back. No spinning cuts.
  - Hand-to-hand combos: no spinning kicks or backfists. Every blow loads, strikes and recovers, and the rush is a step in with a driving cross.
- **Nathan's sword, as in the series:** a plain, straight silver longsword (polished steel that catches the light) with a short clipped point, on a chunky stepped black hilt banded in green, with green energy rising up the base of the blade.
- **Vlad's glaive, as in the series:** a long grey polearm wrapped in red, with a trident-like head of glowing red: a long double-edged centre blade with a hooked prong curving up on each side of it, and a red spike at the butt.

## 1.37.4
- **Each dash trail closes on its own:** in a run of dashes, every dash's trail now thins and disappears on its own timer, counted from the end of that dash, instead of all of them waiting for the last dash and vanishing together. The Trail hold and Trail close settings set that timer.

## 1.37.3
- **One bar per dash:** each dash now leaves its own trail bar. Dashing again while a trail is still up adds a new bar.
- **Configurable closing:** two new settings (Void Powers Settings, right column, or `voidpowers-client.toml`):
  - **Trail hold:** how long a finished trail stays at full size (default 0.22 s).
  - **Trail close:** how long it takes to thin down to a line and vanish (default 0.33 s).

## 1.37.2
- **The dash bar is a bit smaller:** a square about 1.4 blocks across, down from 1.9.
- **Fix (shaders):** particles no longer vanish against the sky or water. Shader packs paint the sky and water in their own later passes wherever nothing has written depth, which painted over the particles. With a pack on, particles now write depth for their visible part.

## 1.37.1
- **Accretion Storm devours the land:** for its whole length the black hole tears up blocks from anywhere within 40 blocks of where it struck, several every tick, and they spiral up into it. Every creature and player in that radius is dragged in fast and is hurt once it reaches the hole (Herobrine stays safe in the eye).
- **The dash bar is a square:** it's as wide as it is tall (head to feet), seen end-on.
- **The dash bar closes as one:** the whole trail stays fully open while you dash, then squeezes down into a single thin line all at once, and the line vanishes.
- **Fix (shaders):** with the HUD hidden (F1), dash trails, swing trails, afterimages and black-hole distortion no longer disappear.

## 1.37.0
- **Nightmare's axes:** back to their original 2D look, and now they leave swing trails like every other weapon.
- **Each swing is one trail:**
  - A swing now leaves a single smooth, unbroken trail. It grows with the blade for the whole move, so it stays in sync with the animation, then fades away as a whole when the move ends.
  - The trail is wider, running from the hilt to past the tip.
  - It's faint where the swing began and brightest at the blade.
- **Ultimate cutscenes:** using a character's ultimate gives you a short cutscene.
  - The camera punches in low and close, then swings out to show the move.
  - Black bars close in, and the move's name is cut across the screen in their colour.
  - An ultimate is the move with the longest cooldown, plus any that takes 30 seconds or more to come back.
  - Held beam moves are left out, so you keep your aim.
  - The `cutscenes` config option turns these off too.

## 1.36.1
- **The dash bar is body-sized:** it's as wide as the shoulders and runs head to feet, with each colour layer a third of the body.
- **It closes instead of fading:** each stretch stays at full size, then squeezes down into a single thin line, and the line vanishes.

## 1.36.0
- **New dash look:** a dash now leaves a 3D bar of light along its path instead of afterimages and a ribbon. The bar is three stacked layers in the character's own colours, for example:
  - Herobrine: purple, pink and white.
  - Orion: orange, amber and gold.
  - Kuro: peach, green and fire.

  Older stretches of the bar shrink and fade, and a pulse of light runs along it.
- **Character cutscenes:** becoming a character plays their entrance.
  - The camera swings round in front of you and circles as you strike the pose of their biggest move.
  - Their signature light breaks out around you, which other players see too. For example: Herobrine's void galaxy, Vlad's square gate, Derek's lightning, Leo's doubles, Chaos' sky pillar.
  - Black bars close in, and their name is cut across the screen in their colour with their origin and passives.
  - The HUD steps aside while it plays. It can be turned off in the config (`cutscenes`).
- **New character menu:**
  - A scrolling list with one row per character showing everything at once: portrait, name, origin, passives, and all six moves, each with what it does and its cooldown.
  - Hover a move for its full description.
  - Scroll with the mouse wheel or drag the scrollbar, so any number of characters fits.

## 1.35.3
- **Kuro's and Derek's swords** are turned the right way: the edge now leads the cut, facing forward and down, with the spine on top.
- **Every sword is held just under its guard**, not low on the handle. This covers Nathan, Daemon, Leo, Derek, Vain, Chaos and Kuro.
- **Trails really no longer go black:** they're drawn as plain additive light with true transparency. Each one fades from clear at the hilt to strongest along the blade, with a bright band at the edge, and can only fade out as it dies, never darken.

## 1.35.2
- **Weapons move in the hand:** every swing works the wrist. The blade cocks back as the blow loads, whips through past the arm's line as it lands, then settles; each swing turns it its own way. This covers all the 3D weapons and the transformation greatsword and reaper.
- **Trails no longer go black:** other effects were leaving the blending in the wrong state, so the fading end of a trail drew dark. That's fixed, and the faded tail now simply ends.
- **Trails and afterimages work with shaders:** swing trails, axe trails, dash ghosts and trails, and illusion doubles are now drawn after the shader pack finishes the frame. Before, the pack swallowed them. With shaders they show through whatever is in front of them.

## 1.35.1
- **Kuro's buster sword** is shaped like Cloud's Buster Sword: a huge, broad, single-edged slab with a slanted tip, two round sockets by the guard, a squared guard and a long wrapped grip. It's black, with its one edge glowing peach.
- **Derek's sword** is rebuilt as a long black single-edged blade:
  - Its spine is notched in jagged teeth.
  - Its edge glows deep purple at the guard, through magenta, to red at the tip.
  - It has a long black hilt, a spiked horned guard and a white orb of light set where the blade meets the guard.

## 1.35.0
- **Weapons fight differently from fists:** every weapon now has its own attacks, kept apart from its warrior's hand-to-hand combo.
  - With their own weapon in hand, a warrior's five-hit combo and rush are the weapon's moves: the blades' sweeping slashes, Orion's gauntlet boxing, Claire's gun-kata and Fleur's staff work.
  - Every weapon move in the mod is played bigger than a fist: further twists, wider arcs, deeper drops and longer lunges. This includes the transformation greatsword and reaper and the Vira-Blades.
- **New hand-to-hand combos:** without their weapon, each warrior fights with their own five-blow string of jabs, crosses, hooks, uppercuts, palm strikes, knees, front kicks, roundhouses, spinning back kicks and spinning backfists. The sprint attack becomes a flying knee.
- **Fix:** sword trails now show with shaders on. The shader pack's shadow pass was crowding out the real blade positions.

## 1.34.0
- **Every sword combo is slashes:** all five combo hits and the rush of every blade-wielder are now cuts. Each blade is wound back on one side and swept through a full arc to the other, with the body twisting and stepping into it.
  - **Characters:** Nathan, Teufel, Daemon, Leo, Vlad, Derek, Vain, Chaos and Kuro.
  - **Cuts:** forehand, backhand, both downward diagonals, a rising cut, an overhead chop and a low sweep.
  - **Variety:** each warrior has their own order, speed and weight, and some cuts carry right round into spinning slashes.
- **Every blade leaves a trail:** each 3D weapon swung in the hand leaves a ribbon of light in its own colour along the edge's path, throwing sparks on fast swings. This covers all the Eternal Conflict blades, Fleur's staff, the Vira-Blade and Nightmare's axe; the transformation weapons already had trails.

## 1.33.3
- **Burning fists are a 3D model now:** the Fire Hand and Orion's gauntlet share a sleeve of fire round the fist and forearm.
  - It has three layers: a white-hot core, an orange skin of flame and thin streaks of fire swept back up the arm.
  - The layers turn against each other and flicker, so the fire roils.
- **Thinner fire:** the wide candle-like flames are gone. Small square embers peel off the fire instead, red as they leave it and yellow as they burn out (still at most two-thirds of the way up Orion's arm).

## 1.33.2
- Orion's gauntlet fire is lighter: fewer flames. Each one reaches at most two-thirds of the way up his arm before it burns out yellow.

## 1.33.1
- **Orion's gauntlet has its own fire:** big licking tongues of flame, a new flame shape that rolls and sways. They're lit around his fist and wrist and stream all the way up his arm to the shoulder.
- **The Fire Hand's flames reworked:** thin, crisp flames that also stream all the way up the arm.
- **Both fires change colour as they burn:** each flame is born deep red at the fist and turns orange, then yellow, before fading out near the shoulder.

## 1.33.0
- **Orion's gauntlet blazes:** his whole fist and forearm are wrapped in dense flame particles, every face of the gauntlet every tick, with embers thrown off the knuckles. They show in first person too.
- **Every animation is bigger and moves:**
  - Attacks, abilities and dashes twist and bend further, swing wider, sink deeper and carry the whole body forward on lunges.
  - Wind-ups pull back harder and follow-throughs carry further.
  - The off hand no longer moves in lockstep with the lead hand: it trails a beat behind, or has its own job.
- **Every weapon moves like itself:**
  - **Nathan:** an iaido swordsman. Draw-cuts from the hip, a lunging thrust, a rising cut, a spinning backhand and a dash straight through.
  - **Daemon:** his sword hand and his telekinetic palm take turns.
  - **Orion:** a boxer. Jab, cross, hook, jumping uppercut and overhand.
  - **Vlad:** his hands slide on the glaive. A thrust, the butt-blade swung round, an overhead twirl, a low sweep and a vault slam.
  - **Derek:** greatsword cuts traded with lightning jabs and uppercuts from his free fist.
  - **Vain:** reverse-grip rakes, a spinning kick, a stab up from a crouch, a low spinning cut and a diving stab.
  - **Fleur:** staff twirls, a thrust, an overhead arc and a pirouette, while her free hand casts.
  - **Chaos:** slow one-handed great-sword swings with the whole body behind them, ending in the sword driven into the ground.

## 1.32.0
- **New character: Kuro** (*Tears of Cataclysm*), the warriors' successor. Unlock him by crafting **Kuro's Golden Device** (gold ingots, compasses and a fire charge).
  - He carries a black buster sword and wears his golden compass device on his left forearm.
  - **Compass Shift** switches his power between **Bright Green** (Nathan's speed and energy) and **Blaze** (Orion's explosions and fire). Every move and his passives change with the mode.
  - His moves: *Buster Swipe*, *Energy Vault*, *Blast Arm*, *Blaze Rush* and *Bright Green Onslaught*.
  - He has his own animations: stances, combo, dashes and every move.
- **Every weapon has its own right-click skill:**
  - **Nathan:** Blink Cut.
  - **Teufel:** Reaper's Whirl.
  - **Daemon:** Sword Recall (thrown, then called back).
  - **Orion:** Gauntlet Burst.
  - **Leo:** Feint Riposte (hit his double and he's behind you).
  - **Vlad:** Glaive Vault.
  - **Derek:** Thunder Cleave.
  - **Vain:** Venom Flurry.
  - **Fleur:** Gilded Lance.
  - **Chaos:** Ruinous Slam.
  - **Kuro:** Buster Spin.
  - Each skill has its own animation.
- **Every beam looks like its owner's power:**
  - **Daemon:** a holy lance with spiralling blue ribbons and halos; his swords ride it in.
  - **Vlad:** a turning square beam in square frames, with cubes blooming where it hits.
  - **Derek:** a bundle of crackling lightning bolts that leap to nearby foes.
  - **Chaos:** a black core with crimson shock rings that tears up the land.
  - **Nightmare:** the Heart Beam throbs like a heartbeat.
  - **Entity 303:** a ragged column of fire with spiralling embers.
  - **The Chosen One:** the Energy Beam is golden, with racing rings.
- **No more shared moves:**
  - Vlad no longer copies Explosion Boost.
  - Leo's Explosion Boost became *Phantom Step*.
  - Nathan's Tribal Seal became *Superspeed*.
  - Teufel's plain Teleport became *Rift Reap*.
- **Iconic moves from the series:**
  - **Vlad's Crimson Gate:** glowing red square portals open flat in the ground. He sinks into one, a line of red light traces to where he's looking, and he rises out of a new square.
  - **Vlad's Gate Trap:** opens those squares under his foes.
  - **Nathan's Portal Combo:** green portals open around his foes and he flashes between them with trails, cutting each time.
  - **Nathan's Superspeed:** leaves doubles behind him, and his blows land from a blink away.
  - **Teufel:** spins her scythe in a new combo and whirls through Rift Reap.
- **Real afterimages:** Leo's illusion clones, Vain's mirror images, Nathan's and Kuro's speed doubles and Leo's Phantom Step leave actual copies of the player's model, not particles.
- **Models:**
  - **Orion** wears a flaming gauntlet with living, flickering fire.
  - **Derek's** sword is now a broad, long periwinkle greatsword.
  - **Leo, Nathan, Daemon, Chaos and Vain** have bulkier blades. Leo's is redesigned, with a varied combo: a draw-cut, a backhand, a pommel strike, a spinning heel cut and a leaping thrust.
  - **Claire's** pistols point along her arms, and she idles and walks with both of them raised and aimed.
  - **Teufel's** scythe and **Fleur's** staff are held nearer the middle of the pole.

## 1.31.0
- **Arcs are worn, not held:** each Eternal Conflict warrior wears their Arc round the right forearm for as long as they're that warrior. Holding the Arc item no longer shows a striped tube in the hand.
- **3D weapons fit the hand:** they're held at full size, and the right way round. Claire's pistol grip and Teufel's scythe blade now hang below the hand.
- **Natural stances for every Eternal Conflict warrior:**
  - Idles settle the weight on one leg, breathe, and glance around, with the arms hanging loose.
  - Walks and runs swing the free arm against the legs, and a carried weapon stays steady.
  - Each warrior keeps their own bearing: Vlad hunches over his glaive, Vain stays low, Claire rests on one hip, Chaos looms.
- **Moves made faithful to the series (per the wiki):**
  - **Teufel:**
    - *Energy Swipe* flings her scythe's energy on as a wave.
    - *Dark Form* replaces Scythe Throw: her sclera blacken, and portals open one after another so her scythe strikes again out of them, for 15s.
  - **Vlad:** *Explosion Boost* (learned from Leo) replaces Glaive Throw: a red blast flings him on glaive-first and bursts again where he stops.
  - **Fleur:**
    - *Aegis* is now her small gold-and-white shield, worn on the left forearm. Blows from the front glance off it.
    - *Combat Form* replaces Divine Judgment: gold-and-white armour with thin, glassy, beating wings, plus strength, speed, resistance and regeneration for 30s.
  - New animations for each of these.

## 1.30.0
- **Full 3D models:** every Eternal Conflict weapon is a full 3D model, modelled on how it appears in the series, and so are the Dark Lord's Vira-Blade and Nightmare's battle axe.
  - **Nathan:** a long blade of pale cyan light rising green from a black, green-banded hilt.
  - **Teufel:** a dark, organic scythe with glowing purple spots.
  - **Leo:** a black sword with a glowing green edge.
  - **Vlad:** a red-and-grey glaive.
  - **Claire:** a black-and-white pistol.
  - **Fleur:** a golden staff crowned with a red gem.
  - **Chaos:** a black-and-red great sword.
  - **The Arcs** are now what they are in the series: glowing bands of light worn round the forearm, shaded from the warrior's darkest colour to their brightest.
- **Thrown weapons are the weapon itself:**
  - The Dark Lord's Blade Split and the Vira-Blade's right-click now throw real spinning Vira-Blades.
  - Nightmare's battle axe tumbles through the air when thrown.
  - Vain's dagger, Daemon's swords, Teufel's scythe, Vlad's glaive and Chaos' great sword fly, orbit, rain down or fall as themselves.
- **Each Eternal Conflict warrior has their own animations,** no longer borrowed from other characters: stances, five-blow combo, rush, dashes and all six abilities.
  - **Teufel** wields her scythe two-handed.
  - **Daemon** conducts his swords with a gesture.
  - **Orion** bounces like a boxer.
  - **Leo** fights one-handed, his other hand behind his back.
  - **Vlad** hunches over his glaive.
  - **Fleur** moves with grace.
  - **Chaos** looms.
- **Moves reworked to be more faithful:**
  - **Nathan:** his Energy Jump Pad stays and launches anyone who lands on it. His Tribal Seal and Sealing Chains seal a player's powers.
  - **Teufel:** throws her scythe and it cuts its way back (Scythe Throw), and her scythe sweeps out of each portal.
  - **Daemon:** his swords orbit him, rain from a black portal rimmed in blue, burst out of portals, and ring a foe before impaling them.
  - **Vlad:** his Energy Cube is a real cube of red energy that expands where it lands, and Cube Prison closes a vast one over the area. He also throws his glaive (Glaive Throw).
  - **Claire:** Time Stop drains the world to grey for anyone caught inside.
  - **Fleur:** Aegis circles her with shields, and golden swords fall with Divine Judgment.
  - **Chaos:** his great sword, vast, falls from the sky and impales the land (Sword of Ruin).

- **Eleven new characters from ZNathan Animations' Eternal Conflict:** Nathan, Teufel, Daemon and Orion (Fleur's chosen), Leo, Vlad, Derek, Claire and Vain (Chaos' chosen), and the gods themselves, Fleur and Chaos. Each has six moves built from their powers on the series wiki, their own combo, rush, dash, stances, aura and passives, and their signature weapon (Claire carries a pistol in each hand).
- **Unlocked only by crafting their Arc,** apart from the XP progression: each warrior has an Arc item with its own recipe, and crafting it unlocks them for good (kept through death). Right-click a crafted Arc to become that warrior. Creative players and `voidpowers.bypass.progression` need no Arc. The Arcs are in the creative Ingredients tab.
- **Character screen:** two tabs, the original legends and the Eternal Conflict (in two rows).

- **LuckPerms support:** every feature now has a permission node, registered through Forge's permission API, so LuckPerms (or any Forge permissions mod) can grant or deny it per player or group. Without a permissions mod nothing changes.
  - `voidpowers.character.<herobrine|entity_303|chosen_one|dark_lord|nightmare>`: playing as that character (default: everyone). A player who loses it goes back to being a Mortal within a few seconds.
  - `voidpowers.abilities`: using moves. `voidpowers.dash`: dashing. Both default to everyone.
  - `voidpowers.transform` and `voidpowers.ascend`: transforming and ascending. Turning them off is always allowed. Both default to everyone.
  - `voidpowers.grief`: powers breaking blocks (on top of the game rule and config). Default: everyone.
  - `voidpowers.pvp`: powers hurting other players. Default: everyone.
  - `voidpowers.bypass.progression`: any character with no XP cost or unlock order. Default: nobody.
  - `voidpowers.command.progression`: the `/progression` command. Default: operators.

## 1.27.0
- **Every attack animation rebuilt for realism.** Each blow now has the phases of a real strike, timed so contact lands on the tick the hit is dealt:
  - **Guard, then load:** weight drawn back, hips cocked, the striking limb chambered.
  - **The strike:** accelerating into contact instead of snapping there.
  - **Follow-through:** carried a little past the target.
  - **Recovery:** back to the guard.
  - **Body mechanics:** the hips and legs lead every strike, the shoulder and arm arrive a beat later, and the head stays on the target. Weight sinks into the heavy blows and rises with the launchers, and the off hand guards or balances.
  - **Rebuilt:** every character's unarmed combo, launcher, rush and air attack; the Mortal's boxing; the Fire Hands; the Vira-Blades (single and twin); Nightmare's axes; the Greatsword; and the Void Reaper (single and twin).
- **Everything else made more realistic too:**
  - **Feet stay planted:** they no longer float off the ground in lunges.
  - **Leans:** they come from the waist instead of tipping the whole body over at the feet.
  - **Toned down:** the cartoon exaggeration and the extra-deep stances.
  - **Gone:** the forced whole-body spins that opened abilities and finishers. Spins remain only where the move itself is a spin.

- **Fixed the transformed bodies' forearms disappearing:** some animations (Singularity Bolts among them) had two keyframes on the same game tick. That broke the arm's pose for a single frame, and the giant's elbow smoothing kept the broken value for good, so the forearms and the swords in them stopped drawing. Every animation now has at most one keyframe per tick, and the smoothing recovers from a bad frame instead of keeping it.

## 1.26.2
- **Void Reaper sits lower in the hand:** held untransformed, the blade now rests a little lower through the grip.

## 1.26.1
- **Weapons held by the handle:** untransformed, the Void Reaper's model sat below the hand. It's now held by its dark shaft between the pommel spike and the guard. The Greatsword is held by its grip instead of its skull pommel.

## 1.26.0
- **Twin Vira-Blades:** the Dark Lord now dual-wields. Becoming the Dark Lord hands out two Vira-Blades (one goes straight onto an empty off hand); wear one on each arm to fight with both.
  - **New twin combo:** Cross Cut (right then left, an X), Scissor Rend (crossed high, torn outward), Twin Thrust (right and left pistons), Blade Cyclone (both arms out, a turn and a half, with a second wider ring) and Rising Execution (both blades torn up from low, harder and wider). In the air, both blades are driven down together.
  - Every twin blow adds the second blade's cut and damage. Right-click throws a blade from each hand, fanned apart.
  - **Twin stances:** with both blades on, the Dark Lord idles, walks, runs, sneaks and flies with both blades held out low, and both arms crackle with the blades' dark energy.
  - With a single blade, the original combo plays as before.
- **3D orbs:** every orb thrown by a character other than Herobrine is now a real 3D model instead of a cloud of particles, with only a light wisp trailing behind it:
  - **Fireballs** (the Chosen One's Fireball and Fire Hand throw, Entity 303's fireballs): a white-hot core inside rolling flame shells with a glowing halo.
  - **The Dark Lord's Explosive Fireball:** a black core in red flame.
  - **The Dark Lord's Dark Orbs and Nightmare's Knockout Orb:** a black core in a writhing red haze, circled by two crossing rings.
  - **Nightmare's Energy Particles:** small energy orbs, a white-hot core in a crimson shell ringed by a spinning band.
  - Herobrine's orbs stay as they were.

## 1.25.0
- **Black-hole distortion with shaders:** with a shader pack on, black holes bend the light around them again. The distortion is now drawn over the shader pack's finished frame. (With shaders it can also warp things in front of the hole, since the shader pack's depth isn't available.)
- **Ascension, for the Chosen One, the Dark Lord and Nightmare:** the transform key (G) now ascends them, so they can fight on par with transformed Herobrine and Entity 303.
  - Every power they use is **four times as big**: areas, pulls, blasts, beams, dashes, combo reach and effects. Terrain damage grows like the giants' does.
  - They gain the awakened giants' toughness: **Resistance V and Regeneration VII** (paused while wounded, as for the giants).
  - Crackling energy in their colour plays around them while ascended; a pillar, shockwave and impact frame mark the moment they ascend.
  - The Chosen One and the Dark Lord can ascend at any time; Nightmare once enraged ("Nightmare Unbound"), and **unbound he can fly**.
  - Death or switching character ends it; pressing G again calms back down.

## 1.24.0
- **Twin Void Reaper animations redone:** the blades no longer move as one mirrored pair. One leads and the other answers a beat later, with the body whipping between them, and the arms sweep around the body instead of crossing through it.
  - **Twin Rend:** the right blade cuts in from the right, then the left answers from the left.
  - **Rising Cross:** crouched low, both blades are torn upward one after the other, lifting what they hit.
  - **Twin Hooks:** right hook, left hook thrown past it, then both wrenched back.
  - **Death Whirl:** both blades straight out from the shoulders, one tipped high and one low, for two full turns.
  - **Void Rend:** both blades raised on the toes; the right chops down, then the left crosses it a beat later, dropping to a knee.
  - **Plunge:** both blades reversed overhead and driven down.
- **Twin-blade stances:** holding a reaper in each hand, Herobrine idles, walks, runs and sneaks with both blades held ready (right forward, left trailing low), transformed or not.

## 1.23.1
- **Fixed impact frames turning the screen white with shaders (Oculus / Iris):** the flash's blending was being switched off under shader packs, so the inversion drew as a solid white screen. Blending is now set directly and restored afterwards, and with a shader pack on, impact frames use a shader-friendly look (a dark snap with speed lines, a wash of the attacker's colour, then the fading glow) instead of inverting colours. Without shaders they look the same as before.
- **Photon particles and other effects with shaders:**
  - With a shader pack on, Photon's own bloom is switched off for the mod's particles and beams. It was composited into the pack's buffers and blew out to white or flickered; the shader pack's own glow takes over.
  - The light-bending lens effect (black holes and shockwave ripples) is skipped with shaders. It copied a frame that shader packs don't draw into, which showed up as a stale or white disc and could misdirect the rest of the world's drawing.

## 1.23.0
- **Twin Void Reapers:** Herobrine now dual-wields. Becoming Herobrine hands out two Void Reapers (one goes straight into an empty off hand); hold one in each hand to fight with both.
  - **New twin combo:** Twin Reap (an X-cut), Scissor Reap (both blades torn outward at the legs), Twin Hooks (catches and drags the two nearest foes), Death Whirl with both blades out, and Void Rend brought down in a crossing X. In the air, a two-bladed plunge.
  - Twin blows reach a little wider and hit a little harder. Right-click (Reaper's Arc) throws a crescent from each blade.
  - The transformed giant holds the second reaper in its left hand, and both blades leave trails while attacking.
  - With a single reaper, the original one-handed combo plays as before.

## 1.22.1
- **Far less lag from Event Horizon and Accretion Storm:**
  - **Particles:** every particle effect now has a ceiling (about 90 particles per emitter). The biggest effects (20-block black holes, a giant's storm) used to spawn thousands every frame; they now look sparser instead of heavier.
  - **Craters:** capped at 24 blocks across. As a giant, the collapse craters reached 48–60 blocks and removed hundreds of thousands of blocks at once.
  - **Torn-up blocks:** Event Horizon tears blocks loose more slowly, with at most 40 in the air at once (was 140).
  - **Pull streams:** drawn for the 8 nearest victims rather than every mob in range.
  - **Accretion Storm:** its bolts fall a little less often and its spiral-galaxy effect refreshes less often.

## 1.22.0
- **Flashier Herobrine and Entity 303:**
  - Every move, attack and dash is pushed further: bigger wind-ups, wider swings, deeper lunges.
  - Every ability, the fifth blow of each combo and the weapon finishers open with a whole-body spin that whips into the move.
  - Their idle, walk, run, sneak and flight stances are unchanged. The transformed (giant) versions get all of this too.
- **Lower arms on the transformations:** the giants' arms hang down closer to the body instead of held out like a T-pose.
- **Weapon trails only while attacking:** the Greatsword and Reaper leave their trails only during a swing, not when you just move around holding them.

## 1.21.1
- **Fixed: holding a weapon froze your stance.** Holding your character's weapon (the greatsword, reaper, axes or Vira-Blade) stopped the idle, walk, run, sneak and flight animations from playing; only the weapon swings did. Every stance plays normally again with a weapon in hand.
- **Weapons are held by the handle:** the Greatsword and Reaper items now sit in your hand by the end of their grip.
- **Herobrine's aura** spreads over the whole transformed body instead of piling up around his feet, with lighter, sparser wisps so he isn't hidden behind it.
- **No more red on Herobrine's weapon:** his void slashes, trails and sparks are purple and black only. Near-black void effects now spark purple instead of red.
- **The Wither King's wings:** the feathers that hung down to his hands are trimmed, so the wings end above his arms, and both wings, his body and his head are now exactly symmetrical.

## 1.21.0
- **New weapons, as items:**
  - **Weeping King's Greatsword** (Entity 303) and **Void Reaper** (Herobrine), modelled from their transformation rigs and shown as full 3D models in the hand, in the inventory and on the ground.
  - They're handed out like the other character weapons, and only their character can wield them.
  - While transformed, the giant holds the weapon only while you have the item in hand.
- **Weeping King's Greatsword:** a two-handed, five-blow combo with its own animations:
  - Molten Cleave, an overhead blow.
  - Burning Sweep, which flings enemies aside.
  - Rising Brand, which launches.
  - Inferno Wheel, a full spin.
  - Earthsplitter, a leaping slam that splits the ground in a line of fire.
  - Swung in mid-air, it becomes a falling cleave. Right-click: **Searing Wave**, a wall of flame rolling along the ground.
- **Void Reaper:** a five-blow reaping combo with its own animations:
  - Reap.
  - Return Reap, which slows.
  - Soul Hook, which drags the target in.
  - Death Whirl, two cutting turns.
  - Void Rend, a rift torn straight ahead.
  - Swung in mid-air, it becomes a plunging reap. Right-click: **Reaper's Arc**, a thrown void crescent that drags what it cuts.
- **Swing trails:** both weapons leave glowing ribbons along the blade's real path through every swing, molten orange for the greatsword and void purple for the reaper, with sparks off the tip. They work at normal size and as a giant.
- The giant animation set covers the new weapon moves too.
- Unarmed attacks while transformed are back to normal; the weapon power is in the items now.

## 1.20.0
- **Transformation weapons:** the Wither King wields his molten greatsword and the Void Monarch his void blade, both from their rigs and held in the right hand. While transformed, the attack combo is swung with them: blows hit 75% harder, carve crescent slashes through what they hit, and reach as far as the giant does. Held items aren't drawn in a giant's hands (they still work).
- **Giant animations with real joints:**
  - Both transformations now have elbows and knees, split where their rigs bend.
  - Arms straighten as they strike or cast and fold as they draw back. Knees lift through each stride, push off behind, sink into a crouch and tuck in the air. The giant stands with its knees bent, and the body lowers so its planted foot stays on the ground.
  - Every Herobrine and Entity 303 animation (idle, walk, run, sneak, flight, every ability, the attack combo and the dashes) has a giant's version, played while transformed. These have a wide, low, hunched stance, bigger movements and heavier timing.
- **Smoother transformed dashes:** a giant's dash leaves fewer, lighter afterimages (at most four, drawn once each), so it no longer tanks the frame rate.

## 1.19.0
- **Everything scales with a transformed body.** While transformed, all of your powers are sized to the giant you are:
  - **Effects:** particles and effects are drawn five times as big (rings, shockwaves, black holes, novas, auras and the rest).
  - **Hit areas:** every ability's area, reach and hit width grow to match, including blasts, beams, projectiles, pulls and melee sweeps.
  - **Dodge:** the dash covers five times the distance.
  - **Terrain:** destruction grows too, but at most twice as big, so the server doesn't stall.
- **Herobrine's transformation:** heavier calves, with layers of the armour's own jagged plates building out the back of both lower legs.

## 1.18.2
- **Transformations face forward:** both bodies were turned backwards; they now face the way you do.
- **Symmetrical bodies:** the Wither King and the Void Monarch are now symmetrical side to side. The fuller arm and leg are mirrored onto the other side, which also restores the Void Monarch's missing lower right leg.
- **Removed:** the grey shield plate floating behind the Wither King's arm.

## 1.18.1
- **Fixed:** the Wither King and Void Monarch no longer wash out to white. Their glowing parts are now self-lit in their true colours instead of being added over themselves.

## 1.18.0
- **New transformation bodies, converted from Mine-imator rigs:**
  - **Entity 303** is now the *Wither King*: a horned skull-faced titan in blackened, ember-veined bone armour, with flanking skulls on the shoulders and huge black-and-orange bat wings. His greatsword is left out.
  - **Herobrine** is now the *Void Monarch*: a jagged void-armoured giant streaked with glowing purple, with a crowned skull face and taloned feet. His sword, scythe and blade-fan wings are left out.
  - Both are rebuilt part for part from the rigs: every textured piece, extruded sprite, cube and body part, with their colours and glows. They're mapped onto the player's skeleton, so they still play every animation, and their shoulders and hips bend where the rigs put them.

## 1.17.0
- **Accretion Storm** is cast where you look, as far as your render distance: the black hole forms over that spot, the void bolts rain around it, and the final pillar of void falls there.
- **Event Horizon** is now a 20-block maw. It drags mobs in fast (up to a couple of blocks a tick) and tears up the ground around it, sucking the blocks in, before it collapses. Its effects are drawn at its new size.
- **Giant-sized effects:** while transformed, beams are as big as the body firing them (thicker, wider-hitting, boring bigger tunnels). Dash trails, shock rings and afterimages scale with the body too, and a transformed body leaves afterimages of itself rather than of your skin. The dash's hit area grows to match.
- **Entity 303 is on par with Herobrine:**
  - Blast Wave: reaches 32 blocks, hits harder and craters the ground under him.
  - Hellfire Chains: grabs up to 8 foes within 32 blocks, drags them in hard, and each one explodes at the end.
  - Phoenix Dive: an 11-block impact that hits far harder and craters the ground.
  - Magma Eruption: stronger geysers and a bigger 28-block field.
  - Supernova: drags everything within 24 blocks in while it charges, then detonates across 40 blocks for up to 40 damage.
- **Armour reshaped:** both transformations are lean and angular rather than bulky. They have a hexagonal, V-tapered cuirass with stepped belly plates and tassets, flaring layered pauldrons, stepped bracers and cuisses, spiked knee plates, keeled greaves and pointed sabatons.

## 1.16.5
- **Herobrine's transformation, upper body:**
  - His mask now has a demon's face: glowing slanted eyes, a glowing third eye on the forehead and a grin of jagged glowing teeth.
  - A crown of jagged spikes fans out behind his head.
  - A ribbed chest plate with a glowing ring over the sternum.
  - Pixel-stepped zigzag streaks of purple energy run over his armour and wing blades, replacing the cracked seams.
  - Longer claws.
- **Black holes are clean:** Herobrine's black holes, singularities and void blasts no longer throw up brown dust or debris when they explode or break the ground. Orbiting debris is void-black instead.

## 1.16.4
- **Armoured transformations:** both now wear full faceted plate armour instead of showing bare muscle: a keeled cuirass, belt, gorget, three-layered pauldrons, bracers, gauntlets, cuisses, knee cops, keeled greaves and sabatons. Spikes and shards now grow out of the armour.
  - **Entity 303:** blackened plate with ember light leaking from the seams and glowing shards set into it, under his horned head.
  - **Herobrine:** recoloured to purple and black only: near-black plate over a deep-purple undersuit, violet spikes and claws, purple glowing seams and a chest core, and a helmet behind his mask with violet-white eye slits. His blade wings are dark violet with blazing edges.

## 1.16.3
- **Leaner, more jagged transformations:** both bodies are slimmer, with the muscle bulges cut way down (no more puffed-up chest, glutes or thighs). They're built from fewer, sharper facets with rougher edges, and have more spikes: Entity 303 now has rock spikes down his back, along his forearms and at his knees, and Herobrine has more spikes all over.

## 1.16.2
- **Herobrine's transformation redesigned:** no longer a literal dragon, just dragon-themed. He's now a super jagged, armour-plated humanoid:
  - A sharp, faceted mask with a pointed chin, cheek blades, slanted glowing eye slits and swept crest blades.
  - Angular spikes jutting from his shoulders, forearms, hips, knees, flanks and back, and a magenta core burning through the chest plate.
  - Wings made of a fan of long crystal blades, pale with magenta-lit edges (they still spread and flap in the air). The tail and talons are gone.

## 1.16.1
- **Transformation bodies restyled:** chunky, faceted, flat-shaded giants in a cinematic low-poly style instead of smooth sculpting:
  - **Entity 303:** a hulking obsidian brute with great curved horns, rock spikes on the shoulders, burning eyes and glowing red-orange crystal shards embedded all over.
  - **Herobrine:** a pale, armour-plated dragon knight with glowing magenta seams between the plates, bladed pauldrons, and huge pale wings with magenta-lit veins.
- They're also much lighter to draw (about a quarter of the geometry), so frame rates should hold up better.

## 1.16.0
- **Transformations are giants:** five times player size, about 9 blocks tall (they were 1.75 times). Reach, step height and speed grow to match, and the third-person camera pulls back to fit. You need room to stand up in to transform.
- **New transformation bodies:** smooth, sculpted, realistic humanoids instead of box models, with real muscle shapes and human faces (brow, eye sockets, nose, cheekbones, lips, chin and ears):
  - **Entity 303:** an ash-grey giant whose skin is cracked with glowing ember veins (brightest over the heart), with burning orange eyes and torn dark trousers.
  - **Herobrine:** a pale-faced dragon-humanoid with white glowing eyes, swept-back horns, purple scales with a banded belly, spines down the back, bladed forearms and taloned feet. His bat wings flap while he's in the air, and his barbed tail sways as he moves.
- **Superb Warfare vehicles:** every power can now damage them: beams, blasts, projectiles and melee. A held beam destroys a vehicle in about two seconds, and no other single hit takes more than about a third of its health. Your powers never hit the vehicle you're riding.

## 1.15.1
- **Fixed:** the death message from another player's powers now names who did it ("X was overpowered by Y").

## 1.15.0
- **Characters can fight each other:**
  - Powers used on another player pierce Resistance, even Resistance V, so awakened Herobrine and Entity 303 are no longer immune to each other.
  - No power can take more than 30% of a player's max health in one hit (beams included), so players are worn down instead of one-shot.
  - A hit from another player's power pauses the awakened Regeneration VII for 3 seconds.
  - Flying or falling no longer protects you from another player's powers; a dash still dodges them.
- **Death message:** players killed by another player's powers are "overpowered".

## 1.14.3
- **Fixed with shader packs (Oculus):** the Fire Hand's flames, the dash afterimages and the axe trails now show up. They were being placed from the shader's shadow pass, which draws from the sun's point of view.

## 1.14.2
- **Fixed:** the white core of every beam is now visible, including Entity 303's and Nightmare's. The outer layers were hiding it.
- **Fire Hand flames:** crisp, hard-edged flame shapes in a mix of yellow, gold, orange and red, kept tighter to the arm.
- **Chosen One:** the Fire Hand's arm flames hide while flying in survival, so the flight jets take over.

## 1.14.1
- **Beam texture:** the outer layers now carry long, straight streaks flowing out along the beam, instead of spirals.
- **Beam core:** the coloured beams have a pure white core with a white-hot line through the middle, and it shows through the outer glow.
- **Transformation hands:** curved, jointed claws that hook toward the palm. The fingers now spread front to back along the hand, with a thumb claw at the front.

## 1.14.0
- **New beam shape:** every beam now starts from the hand as a rounded, bullet-shaped nose that swells out to full width, then runs at a constant thickness. Each glowing layer nests inside the next.
- **Transformation bodies:** bigger (1.75 times player size) and rounded off instead of boxy, with much more detail:
  - **Entity 303:** cheekbones, temple ridges, neck tendons, collarbones, ribs, bicep veins, forearm tendons, knuckles and kneecaps.
  - **Herobrine:** a snout horn, spiked brows, forearm spines, wrist spurs, a shin spike, a spined tail and glowing veins down his limbs.

## 1.13.1
- **Transformations reworked:** the transformations are now lithe, muscular creature bodies, half again as big as a player, instead of robots.
  - **Entity 303:** a skull-headed brute with charcoal skin over defined muscle, molten orange veins, a cracked skull with burning eye sockets, and bone claws.
  - **Herobrine:** a lithe dragon-humanoid in black scales, with violet belly scutes, glowing purple veins, a horned dragon head, membrane wings, a tail and talons.
- **Size:** while transformed, your hitbox, eye height, model and held items are all 1.55 times their normal size, and your moves come from where the bigger body's hands are.

## 1.13.0
- **Transformations:** once awakened (or any time in creative), Entity 303 and Herobrine can press **G** to transform into a detailed 3D mech suit, and press it again to change back.
  - **Entity 303's skull mech:** black and dark grey with orange glow. A skull helmet with white-hot eyes and a toothed jaw, a chest reactor, glowing exhausts, hazard-striped pauldrons and clawed gauntlets.
  - **Herobrine's dragon mech:** lithe, in obsidian and violet. A horned dragon helm, mechanical wings, a tail with a glowing barb, and talons.
- **How the suits work:** the suit replaces the player's model but follows every animation exactly. It assembles over the body piece by piece, and dissolves away when you change back. Armour still protects you underneath. Dying ends the transformation.
- **Fire Hand:** bigger flames that wrap all the way around the arm and hand instead of hiding behind it.

## 1.12.1
- **Nightmare's lightning is now 2D:** a custom particle made of tiny red-white zaps that flicker in and out.
- **Lightning aura:** it crackles all around Nightmare while he's Enraged in survival, and all the time in creative.
- **His moves:** the same zaps replace the 3D lightning arcs and bolts.

## 1.12.0
- **Nightmare, red lightning:**
  - Lightning crawls over his body, faster while he's Enraged.
  - Red lightning snaps along his Heart Beam.
  - His axes throw red arcs with every swing and hit.
  - Rage Step trails lightning.
  - Knockout Orb calls bolts down from the sky, and Pillar of Light is lashed by lightning strikes.
- **No hold limits:** every beam now lasts as long as you hold the key.
- **Dash:** holding the dash key chains dashes for as long as you hold it, steered by your movement keys.
- **Dash sounds:** each character now has their own dash sound, replacing the phantom sound.
- **Fixed:** one of the Chosen One's laser-vision beams sometimes drew dark or black.

## 1.11.0
- **Beam clashes:** when players' beams cross, sparks in both beams' colours fly from where they pass through each other.
- **Head-on clashes:** two beams aimed at each other stop where they meet in the middle and grind against each other in a storm of sparks, with a shockwave and impact frame when they first collide. Whoever holds their beam longer wins, and their beam carries on as normal. Any beam can block another, including the same character's same beam. This covers all six beams: Void Beam, Inferno Laser, Laser Vision, Energy Beam, Unstable Laser and Heart Beam.

## 1.10.0
- **Character progression (survival):** everyone starts as a Mortal. The legends unlock in order, each costing XP levels: Nightmare (5), The Chosen One (10), Entity 303 (15), The Dark Lord (20), Herobrine (30). Unlocks are kept through death. Creative mode skips it, and the costs can be changed in `voidpowers-common.toml`.
- **New command:** `/progression true|false` (operators only) turns progression on or off for the world.
- **Mortal:** now has the Alt dash, a quick level **Sidestep** with grey afterimages. You can't be hit mid-dodge.
- **Settings screen:** the move bar no longer shows while you're in the mod's config screen.
- **Character screen:** locked characters are dimmed and show what they cost to unlock.

## 1.9.0
- **Mortal skills:** the Mortal now has six moves: Power Strike, Sweep Kick, Combat Roll, Second Wind, Battle Cry and Rock Throw (a tumbling 3D rock).
- **Mortal combo:** a bare-handed four-hit combo (jab, cross, hook, roundhouse kick), with its own animation for every move.

## 1.8.3
- **Fixed:** item and character attacks stopped working for a while after dying (for example, falling into the End's void).
- **Fixed:** the dash's dodge window could be skipped after a respawn.

## 1.8.2
- Removed a development-only skin hook from the mod.

## 1.8.1
- Development build only.

## 1.8.0
- **Nightmare's Battle Axes:** shorter, and much bigger in your hand.
- **New axe moveset:** Reaper's Hook, Backhand Rend, Scissor, Cyclone, Executioner's Drop, plus a new plunging air attack.
- **Axe effects:** glowing red afterimage trails follow every swing, and fast swings throw off crimson sparks, shards and embers.
- **Reaper's Reel** replaces Puppet Spear. Nightmare hurls an axe up to 30 blocks on a crimson chain and drags whatever it hits back to him.
- **Pillar of Light** can be cast anywhere you can see.
- **Real projectiles:** Energy Particles, Dark Orbs, Fireball, Explosive Fireball and Singularity Bolts are now real projectiles with 3D models, and they break blocks where they land.
- **Singularity Bolts:** they collapse into a mini black hole for a split second on impact, bending the light and pulling nearby mobs in.
