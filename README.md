# G-Zero: Gasmania Recharged
## A GASLANDS: REFUELLED HACK

*G-Zero is an unofficial, non-commercial fan hack. Gaslands: Refuelled is copyright Mike Hutchinson / Osprey Games 2019. No challenge to copyright is intended.*
<br>

##### The world did not end; there was no money in it.

What happened instead is that the corps outlived the states, the states outlived the idea of states, and then nothing really changed except the letterhead. The Few run the enclaves. The enclaves run the infrastructure. The infrastructure runs on debt, and the debt runs on the rest.

For the few, it worked out. Arcologies with vertical gardens and clean water and a real sky over real earth with real plants. Post-scarcity pockets, well-managed, carefully photographed for the feeds. Proof that the system works.

For the rest: the sprawl, the hubs, the artificial dirt. High-tech, low-life. The sky above the blocks is the colour of a feed that has nothing to broadcast. Neural implants run on subscription models. Your air filter is a brand name. Your body is a liability you have not finished paying off.

Into this, somebody invented zero gravity.

The Boards saw what the Colosseum did for Rome and updated the formula. The G-Zero league is clean, beautiful, and carefully regulated — a pure sport where the best pilots from any hub push the limits of physics in machines that cost more than most districts do. Broadcast simultaneously to every screen in every timezone. The commentators are excellent. The crashes are spectacular. The drama is delightful.

Nobody is supposed to die in G-Zero. The insurance premiums alone guarantee the Boards pay attention. That said, blacking out at 1000 km/h with a wall in front of you is not a fun experience, and the waivers pilots sign before their first qualifying lap would take a corporate lawyer three days to read. But a cockpit painted red, perfectly lit — that is what really pulls the numbers.

The tracks are everywhere. Some float above the wastelands. Suspended circuits, kilometres of engineered tarmac hanging in the air above the places the Boards decided were not worth fixing. The rest watches from below. The feeds make it beautiful. Sometimes the race is in your backyard; someone could get hit. The feeds make it beautiful.

The pilots know what they are. They know what the crowds are for. Some of them mind.

Most of them fly anyway, because the alternative is the sprawl - and they are very, very good at this.

Speed is the one thing that does not care who owns it.


> ##### DESIGN INTENT
> G-Zero strips Gaslands: Refuelled down to its skeleton and rebuilds it as a 
> pure anti-gravity racing game in the spirit of F-Zero, Extreme G, WipeOut, 
> and Speed Racer. No weapons. No damage. No killing. Just speed, corners, 
> G-forces, and the occasional catastrophic blackout.
>
> Everything in this document replaces the equivalent Gaslands rule. Where no 
> replacement is stated, use Gaslands: Refuelled as written.
>
> ---
>
> ##### VIBE & SOUNDTRACK
> F-Zero GX. WipeOut HD. Extreme G3. Speed Racer (2008).
> Perturbator, Crystal Castles, Leftfield, Aphex Twin.
> If the walls feel closer and the track feels faster, you are in the right headspace.

---

### VELOCITY REFERENCE

The **Velocity Vector** (abbreviated V1 through V6) describes a car's current thrust band. This is not a gear ratio. It is the output state of the drive system, a number on the cockpit display that pilots use to communicate speed in terms the body can understand. The numbers below are approximate. 

| Vector | km/h | m/s | Vibe |
|:---|:---:|:---:|:---|
| V1 | ~200 | ~55 | "Pitlane tempo. System rebooting." |
| V2 | ~350 | ~97 | "Slow. Relatively speaking." |
| V3 | ~600 | ~167 | "Corners start to have opinions." |
| V4 | ~900 | ~250 | "Spectators genuinely nervous." |
| V5 | ~1.150 | ~319 | "Transonic turbulence. Rattling the cage." |
| V6 | ~1.900 | ~528 | "Mach 1.5+. Beyond the veil. Dampeners screaming." |

The fastest possible Speed is the **Red Mist** Manouver at V6, wich produces a brief burst in excess of 2400 km/h, approximately Mach 2. 

---

# THE HOVERCAR

**G-Zero uses a single vehicle type.** All cars are identical in stats. Variety comes from the Altitude system, your driving decisions, and (eventually) Sponsor perks.

> ##### DIFFERENCE FROM GASLANDS
> Gaslands uses many vehicle types with different Hull, Handling, Max Vector, Weight, and Crew values. G-Zero removes all of that. There is one car. Sponsors and Feats (coming in a future supplement) will add the differentiation back in a cleaner way.

| Stat | Value |
|:---|:---:|
| Max Vector | V6 |
| Handling | 4 |

**No Hull Points.** "Cars cannot be destroyed by ordinary play. The only ways to leave the race are voluntary retirement, being lapped beyond recovery, dying in an Emergency Dampener Check, or triggering Red Mist.

A dead pilot can't compete in any other races—which becomes relevant when there are feats, because a dead driver has no feats."

**Handling can drop during a race.** Each Tumble or Redout permanently reduces Handling by 1, to a minimum of 1. See Tumble and Handling Loss below.

---

# RESOURCES

G-Zero uses two trackable resources. Both are visible on your cockpit display at all times. Both will kill you if you ignore them.

### Energy ⚡

**Energy** is everything. It's what powers your engines and it's what's keeping you alive. And you should manage it carefully: pilots can route energy through the cockpit systems freely.

Energy is generated by rolling a **⚡** on Skid Dice. It is spent to activate the **Inertial Dampener**, to change your Velocity Vector, or to remove accumulated G-Force.
Unspent Energy is immediately lost.

Track Energy using tokens marked with a lightning bolt, or on a small dial.

### G-FORCE (G)

**G-Force tokens** are hazards. They accumulate from Vector changes, High-G templates, bad Skid Dice results, Altitude transitions, and collisions. A car with 6 or more G-Force tokens at the end of any activation immediately **Blacks Out**.

The **Inertial Dampener** is the system that clears G-Force. You activate it by spending Energy. Without Energy coming in, G-Force builds until the driver goes dark.

Track G-Force on your car using a dial, dice, or tokens marked **G**.

---

# CORE RULES

G-Zero uses the Gaslands: Refuelled movement and activation system. The core loop is unchanged: Vector Phases activate in order, each car picks a template and rolls Skid Dice, G-Force tokens accumulate, Blackouts happen.

The following is a summary of the core rules as they function in G-Zero. For full detail on anything not covered here, refer to Gaslands: Refuelled.

---

### ACTIVATION ORDER

At the start of each round, the player who holds the **Pole Position token** activates first. Play then proceeds in **initiative order**, which is the current race standing from leader to last place.

Within each Vector Phase, players take turns in initiative order. When it is their turn, a player must either:
- Activate one of their qualified vehicles (a vehicle whose Vector is equal to or higher than the current Phase number), or
- Declare a **Delayed Activation** (see below).

A player with multiple qualified vehicles may freely choose which to activate.

**A player may not skip their turn** if they have a qualified vehicle. The only way to influence when you act relative to others is through Vector choice between rounds, or through Delayed Activation within a Vector Phase.

**Pole Position passes to the player whose vehicle is currently leading the race** at the end of each round. Leadership is measured by gates passed, with distance to the next gate as the tiebreaker.

---

### DELAYED ACTIVATION

When it is your turn to activate, instead of moving immediately you may declare a **Delayed Activation**.

1. **Secretly choose your movement template now.** Note it down or set the physical template aside face-down. Your Altitude declaration also remains secret as normal.
2. **Name a target vehicle.** You may target any qualified vehicle whose controller has lower initiative than you (further from the lead in race standings).
3. The Vector Phase continues with other players activating in order. When your target vehicle completes its movement, your delayed activation resolves immediately afterwards, before any cleanup effects from the target's activation (such as a Blackout) are processed.
4. Reveal your template and Altitude and resolve your activation as normal.
5. Resolve the target vehicle's activation including possibly gained G-Force.

If your target vehicle declares its own Delayed Activation, your delay resolves after their actual movement, not after their initial declaration. If your target is removed from the race before activating, your delayed activation resolves at the end of the current Vector Phase using the template you secretly chose.

> ##### TACTICAL NOTE
> Delayed Activation is the leader's tool. The player in front sees the chasers commit, then resolves their own move with knowledge of where the threats actually are. The cost is that you forfeit any chance to set the pace, and you cannot react to anyone moving before you in initiative order.

---

### SECRET ALTITUDE DECLARATION

At the **start of each Vector Phase**, every player with a qualified vehicle secretly notes their chosen Altitude for this activation (Low, Mid, or High) on a slip of paper or token kept face-down.

**Altitude is revealed** when:
- It is that player's turn to activate (or their Delayed Activation resolves), or
- Their car is involved in a collision before their activation, in which case both drivers involved must immediately reveal their Altitude to resolve the collision.

Once revealed, Altitude is public for the remainder of that activation. A driver's Altitude persists until their next activation.

---

### VECTOR PHASES

Each round, Vector Phases 1 through 6 activate in order. A vehicle activates in the Vector Phase matching its current Velocity Vector. If a vehicle changes Vector during its activation, it activates in its new Vector Phase next round.

A vehicle may change Vector by +1 or -1 for free. Changing by more than 1 in a single step costs 1 G-Force token per additional step.

---

### TEMPLATES

When a vehicle activates, the active player selects a movement template appropriate to their current Velocity Vector. Higher Vectors give access to longer, faster templates but restrict turning. Lower Vectors allow tighter turns.

Some template/Vector combinations are **High-G** (formerly "Hazardous"): placing the template grants 1 G-Force token before Skid Dice are rolled.

Some combinations are marked **Trivial**: they grant 1 free Energy result without rolling any Skid Dice. You may still choose to roll Skid Dice if you prefer and add the free Energy.

---

### SKID DICE

After placing the template, the active player rolls Skid Dice equal to current Handling, up to a maximum of 4. Results are resolved in the following order:

| Result | Effect |
|:---|:---|
| **Energy** ⚡ | Spend to: activate the Inertial Dampener (cancel one G-Force, Drift, or Spin result); OR change Vector by +/-1 (costs 1 G-Force token); OR remove 1 G-Force token from your car |
| **G-Force** G | Gain 1 G-Force token. Cannot be cancelled. |
| **Drift** | Move to the Drift exit point on the template. Gain 1 G-Force token. |
| **Spin** | Pivot up to 90 degrees at Final Position. Gain 1 G-Force token. |

You do not have to roll all your dice. If you are sitting on 4 or 5 G-Force tokens, sometimes the correct move is to roll nothing.

> ##### NARRATIVE NOTE
> A Energy result is surplus energy the drive system routes back to the pilot. Spend it on the Inertial Dampener to bleed off G-Force, or push it into the thrust controls to change your Vector. Every point of Energy is a choice. Every G-Force token you cannot clear is a debt your body will eventually be asked to pay.

---

### SONIC BOOM

When a driver switches to V6, their vehicle breaks the sound barrier. The resulting shockwave is not optional and cannot be suppressed. Physics does not negotiate.

**On the first activation after switching to V6**, the active player must place a **Sonic Boom Shockwave** template. This is a Large Burst Template placed directly behind the vehicle, oriented along its direction of travel. The active player chooses whether to place it at the **start of movement** (before the normal template is placed) or at the **end of movement** (after the car has reached its final position). Either way, the template is removed at the end of this activation.

The Sonic Boom Shockwave has the following effects on other cars:

- **A car that activates while any part of its base overlaps the Shockwave** must roll additional Skid Dice equal to its current Handling before resolving its own movement. All results apply normally (Drift, Spin, G-Force).
- **A car that ends its activation with any part of its base overlapping the Shockwave** must immediately roll Skid Dice equal to its current Handling. All results apply normally.

The car that generated the Shockwave is not affected by its own template.

> ##### DESIGN NOTE
> This mechanic may need tuning. The intent is that V6 is genuinely violent, not just fast, and that a tight pack running at top speed produces real chaos rather than just a speed advantage for the leader. Whether the Handling-worth of extra dice is the right number, and whether start-of-move versus end-of-move placement produces interesting decisions or just a formality, needs table time to confirm. Adjust the template size and dice count freely based on how brutal your table wants V6 to feel.

---

### BLACKOUT

> ##### DIFFERENCE FROM GASLANDS
> In Gaslands, a Wipeout can result in a car being Destroyed. In G-Zero, cars are not removed by ordinary Blackouts. A Blackout is what happens when the human inside the cockpit briefly stops being able to fly. Cumulative Blackouts at Handling 1 can eventually kill the driver (see Emergency Dampener Check).

When a car would Black Out, resolve the following steps in order:

1. **If the driver is at Handling 1**, immediately perform an **Emergency Dampener Check** (see below). If they fail, they die and the car is removed. If they survive, continue.
2. **Roll 1D6** to determine the outcome:
   - **1 or 2**: the vehicle **Tumbles** (see below). Tumble automatically applies its own Handling loss and Recovery as described in the Tumble section.
   - **3 to 6**: the driver enters **Recovery** (see below). No Tumble, no Handling loss.
3. Vector resets to V1.
4. All G-Force tokens are cleared.
5. Altitude resets to **Mid**.

The car's facing after step 2 is the facing it keeps. If a Tumble was rolled, that is the Tumble direction. If only Recovery was rolled, the facing is unchanged.

---

### TUMBLE

A Tumble at V2 is embarrassing. A Tumble at V6 is a lesson in high-energy physics.

**Tumble can be triggered by:**
- A Blackout result of 1 or 2.
- A Burst Template result from striking a solid object (see Collisions).
- Any other game effect that specifies Tumble.

Whatever the trigger, the procedure is the same.

**Tumble Direction:** Roll 1D6 to determine which way the car flips. The result maps to one of six 60-degree wedges around the car (1 = directly forward, 2 = forward-right, 3 = back-right, 4 = directly back, 5 = back-left, 6 = forward-left). The car's nose now points in that direction.

**Tumble Distance:** Based on the Velocity Vector the car was in at the moment of the trigger:

| Vector at Trigger | Tumble Template |
|:---|:---:|
| V1 to V2 | Short Straight |
| V3 to V4 | Medium Straight |
| V5 to V6 | Long Straight |

Place the Tumble template from the car's current position in the rolled direction, then move the car to the end of it.

**Tumble Collisions:** Every other vehicle whose base is overlapped by the Tumble template, or whose base the tumbling car ends in contact with, is **caught in the wreckage**. Each affected car gains G-Force tokens equal to the Tumble length:

- Short Tumble: +1 G-Force
- Medium Tumble: +2 G-Force
- Long Tumble: +3 G-Force

Additionally, each affected car is pivoted up to 90 degrees in a direction chosen by the player whose car Tumbled. Affected cars may not declare an Evade or Brace reaction. Nobody is in the cockpit of an unconscious tumbling hovercar to negotiate with.

**Tumble Aftermath:** After any Tumble resolves:
- The tumbling driver **permanently loses 1 Handling** for the remainder of this race (minimum Handling 1).
- The tumbling driver **enters Recovery**.

> ##### NOTE
> A Tumble can chain into walls. If the tumble path lands the car against a wall, that is just a wall. The Tumble does not deflect or stop short. Walls do not gain G-Force tokens. They have ways of objecting.

---

### RECOVERY

A driver in **Recovery** skips their next qualifying activation. Mark the car with a Recovery token. The pilot is awake but the cockpit is rebooting, the harness is screaming, and the driver's vision has not yet returned to colour.

Recovery is triggered by:
- A Blackout result of 3 to 6.
- Any Tumble (as part of Tumble Aftermath).

A car cannot accumulate multiple Recovery tokens. If a car already in Recovery would enter Recovery again, treat the second trigger as having no additional effect beyond what its source already imposed (such as Handling loss from a second Tumble).

---

### HANDLING LOSS

Each Tumble or Redout permanently reduces a driver's Handling by 1 for the rest of the race, to a minimum of 1. Track the current Handling value on a dial or with markers.

- Handling determines how many Skid Dice you roll each activation (capped at 4).
- A driver at **Handling 1** may not declare Redout or Red Mist. Their nervous system and machine are too compromised to attempt anything that extreme.
- A driver at **Handling 1** who Blacks Out must roll an Emergency Dampener Check (below).

---

### EMERGENCY DAMPENER CHECK

When a driver at Handling 1 Blacks Out, before any other Blackout effects resolve, they must roll an **Emergency Dampener Check** on 1D6. Track the number of Emergency Dampener Checks this driver has been forced to make this race.

| Check Number | Required d6 result to survive |
|:---|:---:|
| 1st | 2+ |
| 2nd | 4+ |
| 3rd | 6+ |
| 4th | automatic death, no roll |

**On a success**, resolve the Blackout normally. A Tumble result from this Blackout does NOT cause further Handling loss, because the driver is already at the minimum.

**On a failure**, the driver dies and the car becopmes a *Dead Stick*

**Dead Stick**: When a driver dies, do not remove the car immediately. At the start of each subsequent Vector Phase equal to its last active Vector, the car activates automatically: it moves the Long Straight template directly forward, rolls no Skid Dice, and gains no G-Force. It has no pilot and no Inertial Dampener. It simply continues on its last thrust vector.
 
The Dead Stick car persists until it collides with a wall or Heavy Solid Object, at which point it is removed. Collisions with other cars are resolved normally for those cars; the Dead Stick car itself ignores all G-Force and reactions. There is nobody left to react.
 
If the Dead Stick car passes through a Gate, the passage does not count. The race is over for that cockpit. 

While a "Red Mist" maneuver is a glorious, terminal sacrifice - an ace racer burning out in a final, blinding surge of speed to clinch victory—dying a pilot dying to a simple system failure is a loser’s end. One is a legend written in fire; the other is just expensive debris drifting through the track, a hollow shell of waiting for the inevitable impact to turn it into an "Alloy Pizza".

> ##### DESIGN NOTE
> Consider a Perk that allows an AI to take over. Alternatively, as a baseline rule, "Dead Stick" cars could bounce upon impact until they either collapse into a "pizza of alloy" due to total dampener failure (on a D6 roll of 1) or explode in a shockwave (on a D6 roll of 6).

> ##### NOTE
> The Emergency Dampener Check is the only way ordinary play can permanently kill a driver. It is the cumulative bill the body has been keeping. The first time it triggers, the driver almost always lives. The fourth time, no roll, no chance, just a name added to the lap sheet's other side.

---

# DRIVER ACTIONS

The following two actions are core mechanics, not optional rules. They are how an experienced driver squeezes performance out of a system that has already started punishing them.

---

### REDOUT

A redout occurs when a pilot exceeds physiological limits during high negative G-maneuvers. This force drives blood into the head, causing the visual field to take on a distinct reddish hue.

> **Redout**: At the start of your activation, you may declare a Redout. If you do, reduce your Handling by 1 (min 1) for the remainder of the race. Until the end of the turn, you may perform any maneuver regardless of your current Velocity Vector, ignoring Vector restrictions. G-Force costs are paid as normal.
>
> You may declare Redout as many times as you like across the race. Each declaration costs another point of Handling.
>
> A driver at Handling 1 cannot declare a Redout.

> ##### SURVIVAL TIP
> Redout is what you reach for in the final lap when your only path to a podium is doing things your car was not designed for. Stacking Redouts is what you reach for when you have already decided you are going to win or detonate.

---

### RED MIST

The final and only true exit from G-Zero by your own hand. A pilot under sustained extreme G eventually stops being a pilot and becomes a fine red mist coating the inside of their cockpit. Some pilots reach this state by accident. The legendary ones reach it on purpose, on the final straight, with their nose pointed at the Finish Gate.

> **Red Mist**: Once per race, at the start of one of your activations, only if you are currently at V5 or V6. You must add two Long Straight templates in any order to your normal template for this activation. You roll no Skid Dice for this activation and gain no G-Force from the Red Mist movement itself. Collisions caused along the path are resolved normally for the other cars involved; you yourself ignore all G-Force from those collisions. Finishing the Race will count, even if you died for it.
>
> At the end of this activation, regardless of your position on the track, your driver dies. The car is removed from the game.
>
> **Exception**: if you crossed the Finish Gate on your final lap during this activation, you are recorded as a Finisher. The result book will list your placing. Whether the obituary calls you a winner depends on where the other cars are.
>
> A driver at Handling 1 cannot declare Red Mist.

---

# THE ALTITUDE SYSTEM

> ##### DESIGN INTENT
> This is the main mechanic that differentiates G-Zero further from standard Gaslands. All cars are hover vehicles. Altitude is the combat replacement: instead of shooting each other, drivers fight for position by flying high or diving low, and the physics of close-range altitude differentials do the damage.

Every hovercar has an **Altitude**: **Low**, **Mid**, or **High**. Track altitude with a separate token or dial alongside your Vector tracker.

Altitude is declared secretly at the start of each Vector Phase and revealed when you activate or when a collision forces it. See **Secret Altitude Declaration** under Core Rules.

Altitude persists between activations. You enter your next activation at whatever Altitude you finished your last one at, and then declare a new one.

---

### ALTITUDE TRANSITIONS

Moving between Altitude levels has costs and bonuses depending on where you are coming from and where you are going.

#### GOING LOW

When you declare Low, you gain a free **bonus movement** at the very start of your activation (before your normal template), but you also pay G-Force tokens.

| Previous Altitude | Free Bonus Move | G-Force Cost |
|:---|:---:|:---:|
| Low (staying Low) | Short Straight | +1 G |
| Mid (dropping to Low) | Medium Straight | +2 G |
| High (diving to Low) | Long Straight | +3 G |

The bonus movement is placed from your current position before your normal template.

> ##### SURVIVAL TIP
> Going Low from High is a massive speed burst, a free Long Straight, but 3 G-Force tokens is an enormous price. You will arrive fast, unstable, and very close to a Blackout. This is the move of a driver who is desperate or has absolutely committed to the corner entry.

#### GOING HIGH

When you declare High, you may use movement templates as if your Vector were 1+X lower than your actual Vector. X can be 0 and is paid in gained G-Force tokens. This makes tight manoeuvres available at speeds they normally are not.

| Previous Altitude | Vector Modifier |
|:---|:---|
| High (staying High) | -(1+X) for required Template Vector |
| Mid (rising to High) | +(1+X) for required Template Vector |
| Low (launching to High) | use any template Vector and drop 1+X Vectors |

> ##### EXAMPLE
> Your car is at V6, Altitude High. You declare High again (staying High). You choose to pay X=3 G-Force tokens. Your effective Vector drops to V3. You may now use V3 templates like the Hairpin. You still pay the 1 G-Force for using the Hairpin at V3.

#### GOING MID / STAYING MID

Mid is the recovery and stability zone. No bonus movement. No Vector Check. Just Energy.

| Transition | Bonus |
|:---|:---:|
| Mid to Mid | +1 Energy result |
| Low to Mid | +2 Energy results |
| High to Mid | +2 Energy results |

These bonus Energy results are added to your Skid Dice pool as free results. You may use them as normal Energy results: activate the Inertial Dampener, change Vector, or remove G-Force tokens.

> ##### SURVIVAL TIP
> Mid is where you go to clean up. After a chaotic dive or a high-speed High run, returning to Mid gives you Energy to spend on G-Force removal. Learn to use Mid as a planned reset rather than just a fallback.

---

# COLLISIONS

> ##### DIFFERENCE FROM GASLANDS
> In Gaslands, collisions involve a Smash Attack: attack dice are rolled, Hull Points are lost, and vehicles can be destroyed. In G-Zero, there are no Hull Points and no attack dice. Collisions produce G-Force tokens, Spin-Outs, and (for object collisions) Burst Templates. Altitude determines whether a car-vs-car collision is full contact or a graze.

### ALTITUDE AND COLLISION TYPE

Before resolving any collision between two cars, compare the Altitudes of the two cars involved. If either driver has not yet revealed their Altitude this phase, they must do so now.

**Same Altitude:** Full collision. Resolve as described under Full Collision below.

**Different Altitude:** Graze. The cars clip each other. Resolve using the graze table below, based on the Altitude differential.

Object collisions (car versus terrain or scenery) are always resolved as a Full Collision against the object, plus a Burst Template (see below).

---

### GRAZE TABLE

The moving car is the "aggressor" regardless of intent.

| Aggressor Altitude | Defender Altitude | Aggressor takes | Defender takes |
|:---|:---|:---:|:---:|
| High | Low | Light | Heavy |
| High | Mid | Light | Medium |
| Mid | Low | Light | Light |
| Low | High | Heavy | Light |
| Mid | High | Medium | Light |
| Low | Mid | Light | Light |

**Light:** +1 G-Force token.
**Medium:** +2 G-Force tokens.
**Heavy:** +3 G-Force tokens.

High Altitude is the dominant position. Flying High makes a driver dangerous as an aggressor and very resilient as a target. Low altitude makes a car fast and fragile.

> ##### SCALE NOTE
> These cars are travelling at 300 to over 2000 km/h. A graze is not a nudge. The reason a Heavy result is only 3 G-Force tokens is that at these speeds, the collision itself is measured in milliseconds. Debris from a destroyed object hangs in the air for only a few seconds, but at these velocities a few seconds is a full lap for the pack behind. This is why Burst Templates persist for the duration of the round (see Burst Templates below).

---

### FULL COLLISION

When two cars are at the same Altitude, OR a car collides with any object, a Full Collision occurs. First, determine orientation:

- **Car versus Car**: Head-On, T-Bone, or Tailgate as in Gaslands: Refuelled.
- **Car versus Soft Object** (bushes, persons, paper stands, light debris): resolves as a **Tailgate** collision. Place a **Small Burst Template** of debris.
- **Car versus Medium Solid Object** (billboards, barrels, small containers, crates): resolves as a **T-Bone** collision. Place a **Large Burst Template** of debris.
- **Car versus Heavy Solid Object** (walls, hard gates, pillars, large containers): resolves as a **Head-On** collision.

In a car versus car collision, each driver declares a Reaction. In an object collision, the colliding driver declares a Reaction normally; the object does not react and cannot Spin you out, although the Burst Template may affect nearby cars.

| Reaction | G-Force Cost | Special |
|:---|:---:|:---|
| **Evade** | +1 G | Cannot Spin the other car. |
| **Brace** | +2 G | May Spin the other car (see below). |

**Spin-Out:** If you chose Brace and you are the non-moving car, you may pivot the other car up to 90 degrees (T-Bone) or any direction (Head-On) after movement resolves. If both drivers chose Brace on a Head-On, both cars spin each other simultaneously. Decide direction by rock-paper-scissors or dice-off.

> ##### NOTE
> Smash Attacks from Gaslands do not exist in this game. No attack dice are rolled. No Hull Points are lost. The only consequences of a collision are G-Force tokens, possible Spin-Outs, and (for object collisions) Burst Template effects.

---

### BURST TEMPLATES

When a car strikes an object, the object shatters, deforms, or explodes. Place the appropriate Burst Template (Small, Large, or Extra-Large) centred on the point of collision. The Burst Template is oriented along the colliding vehicle's direction of travel.

**Any other vehicle whose base overlaps the Burst Template** suffers an effect determined by the object's **material**. The colliding vehicle itself is not affected by its own Burst Template; it has already paid the cost of impact through the Full Collision reaction.

**Template Duration:** Burst Templates from destroyed objects persist for the **remainder of the current round** (Vector Phases 1 through 6), then are removed at round end. At 900 km/h, splinters and shrapnel hang in the air for only a few seconds, but that is long enough for every car behind to run through them.

Some hazards are **permanent**: structural damage to the track surface, large debris that did not clear the lane, or objects that were only partially destroyed remain in place until the referee removes them. Whether a hazard is temporary or permanent depends on its material. Guidance on which material categories produce temporary versus permanent hazards will be in the forthcoming effects table.

The effect of the Burst Template depends on the material of the object struck. Possible outcomes include: G-Force gain or loss, Vector gain or loss, Tumble.

**A formal material/effect table is in development.** Until it is published, the players at the table decide what effect each piece of scenery produces when destroyed. Assign material categories at track setup: decide whether each object's debris is temporary (clears at round end) or permanent (stays on the track). People who play games like this know how to handle it.

> ##### DESIGNER NOTE
> Burst Templates exist to make object collisions matter beyond a single car's misfortune. If a leader takes out a stack of barrels on the apex of a corner, the chasers entering that apex deal with the consequences too. Place soft scenery where you want the track to forgive, place heavy scenery where you want it to bite.

---

# RACE RULES

### GATES AND LAPS

Set up the track using the Gaslands Death Race scenario as a base. Gates are placed at regular intervals around the circuit. Cars must pass through each Gate in order. Passing a Gate out of sequence does not count.

A standard race is **3 laps**. The first car to complete all laps and cross the Finish Gate wins.

---

### STARTING GRID

Roll off to determine starting positions. Place cars in a single-file line at the Start Gate, separated by one car length. All cars begin at V1, Altitude Mid, Handling 4, no Recovery, no Emergency Dampener Checks logged. The driver in first position receives the Pole Position token.

---

### BEING LAPPED

If a car falls more than one full lap behind the leader, it may use the **Restart Rule**: the car teleports to the last Gate it legally passed, resets to V1, clears all G-Force tokens, and resets Altitude to Mid. Handling, Recovery, and Emergency Dampener Check counts are NOT reset. This keeps hopeless positions from becoming unplayable without erasing the consequences of how the driver got there.

---

### GATES IN THE AIR

Some tracks may feature **Altitude Gates**, a Gate marked with a specific required Altitude (Low, Mid, or High). A driver must be at the marked Altitude when passing through the Gate for the passage to count. Passing at the wrong Altitude does not count and does not grant the Gate, but the driver is not penalised beyond having to come back around.

Mark Altitude Gates with a coloured token on the Gate.

---

# OPTIONAL RULES

### GHOST MODE

For a first game or when playing with new players: cars cannot collide with each other. Only wall and obstacle collisions apply. Removes the chaos element entirely so new players can learn the Vector system and template selection without worrying about opponents. Recommended for the first race only.

---

### SLIPSTREAM

A car directly behind another car at the same Altitude and same Velocity Vector (within one car length, not overlapping) may declare Slipstream at the start of its activation. A Slipstreaming car may move its template as if it were in the next Vector up. No G-Force cost. This represents drafting off the car ahead.

---

### HYPE

Use the Gaslands Audience Votes system (Gaslands: Refuelled page 88) as written, renamed **Hype**, with the following restrictions: any Hype effect that references weapons, attacks, Hull Points, or Crew is unavailable. The most useful effects are Burn Rubber, Thunderous Applause, and Slippery Track. Others are at the referee's discretion.

---

# COMING SOON

> ##### SPONSORS
> Sponsor cards will introduce asymmetric car bonuses tied to the Altitude system. A Low-specialist Sponsor might reduce the G-Force cost of Low transitions. A High-specialist might start each race with free Energy already banked. This section is in development.
<br>

> ##### FEATS
> Feats are persistent upgrades purchased between races. They will add build customisation without adding vehicle type complexity. This section is in development.
<br>

> ##### VEHICLE CLASSES
> Whether G-Zero ever expands beyond one car type is an open question. If vehicle classes are added, they will be differentiated through Altitude performance profiles rather than Hull/Weapon loadouts. This section is in development.
<br>

> ##### BURST TEMPLATE EFFECT TABLE
> A formal table mapping each material category to specific Burst Template effects, including whether debris is temporary or permanent, is in development. Until then, use player consensus during track setup or in the moment.
<br>

---

# QUICK REFERENCE

### THE HOVERCAR

| Max Vector | Handling (start) | Weight | Hull | Crew |
|:---:|:---:|:---:|:---:|:---:|
| V6 | 4 | Light | None | None |

Handling reduces by 1 with every Tumble or Redout (minimum 1).

---

### VELOCITY REFERENCE

| Vector | km/h | m/s |
|:---:|:---:|:---:|
| V1 | ~200 | ~55 |
| V2 | ~350 | ~97 |
| V3 | ~600 | ~167 |
| V4 | ~900 | ~250 |
| V5 | ~1300 | ~361 |
| V6 | ~1800 | ~500 |

---

### ACTIVATION ORDER

Pole Position activates first, then initiative order (race standings, leader to last). Qualified vehicles must activate or declare Delayed Activation. No passing turns.

Pole Position passes to the current race leader at end of each round.

**Delayed Activation**: secretly choose template, name a lower-initiative target vehicle, activate immediately after that vehicle moves (before its cleanup effects).

Altitude is declared secretly at the start of each Vector Phase. Reveal when activated or when a collision occurs.

---

### SKID DICE

Roll up to Handling dice (max 4). Resolve in order:

| Result | Effect |
|:---|:---|
| Energy ⚡ | Activate Inertial Dampener (cancel a result), change Vector +/-1 (costs 1 G), or remove 1 G |
| G-Force G | +1 G token (unavoidable) |
| Drift | Move to Drift exit. +1 G |
| Spin | Pivot up to 90 degrees. +1 G |

---

### ALTITUDE TRANSITIONS

| From -> To | Bonus | Cost |
|:---|:---|:---|
| Low -> Low | +Short Straight | +1 G |
| Mid -> Low | +Medium Straight | +2 G |
| High -> Low | +Long Straight | +3 G |
| High -> High | Templates as V-(1+X) | pay X G |
| Mid -> High | Templates as V-(1+X) | pay X G, +1 Vector Check |
| Low -> High | Templates as V-(1+X), drop 1 Vector | pay X G |
| Mid -> Mid | +1 Energy | none |
| Low -> Mid | +2 Energy | none |
| High -> Mid | +2 Energy | none |

---

### GRAZE TABLE (DIFFERENT ALTITUDE)

| Aggressor | Defender | Aggressor | Defender |
|:---:|:---:|:---:|:---:|
| High | Low | Light | Heavy |
| High | Mid | Light | Medium |
| Mid | Low | Light | Light |
| Low | High | Heavy | Light |
| Mid | High | Medium | Light |
| Low | Mid | Light | Light |

Light = +1 G. Medium = +2 G. Heavy = +3 G.

---

### FULL COLLISION

Car vs Car (same altitude): standard Head-On / T-Bone / Tailgate.
Car vs Soft Object (bushes, persons, paper stands): Tailgate + Small Burst.
Car vs Medium Solid (billboards, barrels, small containers): T-Bone + Large Burst.
Car vs Heavy Solid (walls, hard gates, pillars, large containers): Head-On + Extra-Large Burst.

| Reaction | G-Force | Can Spin Opponent? |
|:---|:---:|:---:|
| Evade | +1 | No |
| Brace | +2 | Yes (up to 90 degrees) |

---

### BURST TEMPLATE EFFECTS

Burst Templates persist until end of round, then are removed. Permanent hazards (large debris, structural damage) stay until the referee removes them. Effects depend on object material. Possible outcomes: G-Force gain/loss, Vector gain/loss, Tumble. Formal table in development.

---

### BLACKOUT

Triggered at 6+ G-Force tokens at end of activation.

1. If at Handling 1: roll Emergency Dampener Check first (2+ / 4+ / 6+ / dead).
2. Roll 1D6: on 1 or 2 = Tumble; on 3 to 6 = Recovery only.
3. Reset to V1, Altitude Mid, 0 G-Force.

---

### TUMBLE

Triggers: Blackout (1 or 2), Burst Template, other effects.

1. Direction: 1D6 -> six 60-degree wedges (1=fwd, 2=fwd-right, 3=back-right, 4=back, 5=back-left, 6=fwd-left).
2. Distance: Short (V1 to V2), Medium (V3 to V4), Long (V5 to V6).
3. Cars caught: gain G-Force = Tumble length, pivoted up to 90 degrees by active player, no reactions.
4. Tumble Aftermath: -1 Handling permanently (min 1) + Recovery token.

---

### RECOVERY

Skip next qualifying activation. Triggered by Blackout (3 to 6) or any Tumble. Does not stack.

---

### DRIVER ACTIONS

**Redout**: Declare at start of activation. -1 Handling permanently. Ignore Vector restrictions on templates for this activation. Stackable. Not available at Handling 1.

**Red Mist**: Once per race, start of activation, V5 or V6 only. Add two Long Straight templates in any order to your normal template. No Skid Dice, no self-inflicted G-Force. End of activation: driver dies, car removed. Finish-Gate exception: recorded as Finisher if final lap completed. Not available at Handling 1.

---

### EMERGENCY DAMPENER CHECK

When a driver at Handling 1 Blacks Out, roll before any other effects:

| Check Number | Survive on |
|:---|:---:|
| 1st | 2+ |
| 2nd | 4+ |
| 3rd | 6+ |
| 4th | death, no roll |

Success: resolve Blackout normally (Tumble does NOT take more Handling).
Failure: driver dies, car removed.

---

# CREDITS & LEGAL

### Author
**Stephan Schölzel** {{fa,fa-github}} [github.com/stschoelzel](https://github.com/stschoelzel/)  
{{fa,fa-link}} [G-Zero Project Repository](https://github.com/stschoelzel/g-zero-Gasmania-Recharged)

:::
:::

### Fonts
Under the **SIL Open Font License, Version 1.1**, this document uses the following typefaces:

* **Karrik** & **Resistance** by [Velvetyne Type Foundry](https://www.velvetyne.fr)
* **Illinois Mono** by [MadSimple](https://github.com/MadSimple)

:::

### Disclaimer
"Gaslands Refuelled" is a trademark of Osprey Publishing. This fan-made supplement is not affiliated with, endorsed, or sponsored by Osprey Publishing or Mike Hutchinson.

{{artist,bottom:40px,right:100px
##### Build. Race. Die.
G-ZERO 2026
}}
