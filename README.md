# G-Zero: Gasmania Recharged
## A GASLANDS: REFUELLED HACK

*G-Zero is an unofficial, non-commercial fan hack. Gaslands: Refuelled is copyright Mike Hutchinson / Osprey Games 2019. No challenge to copyright is intended.*
# CREDITS & LEGAL

{{note
##### G-ZERO: GASMANIA RECHARGED
Dieses Projekt ist eine Erweiterung für das Gaslands-Universum. Alle Regeln wurden mit dem Fokus auf maximale Geschwindigkeit und Zerstörung optimiert.
}}

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
<br>

> ##### DESIGN INTENT
> G-Zero strips Gaslands: Refuelled down to its skeleton and rebuilds it as a pure anti-gravity racing game in the spirit of Trackmania, F-Zero, Extreme G and WipeOut. No weapons. No damage. No killing. Just speed, corners, G-forces, and the occasional catastrophic blackout.
>
> Everything that exists in this document replaces the equivalent Gaslands rule. Where no replacement is stated, use the Gaslands: Refuelled rules as written.

---

# THE WORLD

The circuits of G-Zero float above the wastelands. Hovercars, sleek, unstable, barely-street-legal anti-gravity sleds, scream around suspended tracks at speeds that make spectators genuinely nervous. There are no guns here. The track is the weapon. Physics is the executioner.

Unlike the Gaslands death races, nobody is supposed to die in G-Zero. That said, blacking out at 300km/h with a wall in front of you is not a fun experience, and the insurance premiums are absolutely devastating.

\page

---

# THE HOVERCAR

**G-Zero uses a single vehicle type.** All cars are identical in stats. Variety comes from the Altitude system, your driving decisions, and (eventually) Sponsor perks.

> ##### DIFFERENCE FROM GASLANDS
> Gaslands uses many vehicle types with different Hull, Handling, Max Gear, Weight, and Crew values. G-Zero removes all of that. There is one car. Sponsors and Feats (coming in a future supplement) will add the differentiation back in a cleaner way.

| Stat | Value |
|:---|:---:|
| Max Gear | 6 |
| Handling | 4 |
| Weight | Light |
| Hull Points | None |
| Crew | None |

**No Hull Points.** Cars cannot be destroyed by ordinary play. The only ways to leave the race are voluntary retirement, being lapped beyond recovery, dying in an Emergency Dampener Check, or triggering Red Mist.

**No Crew.** There are no crew actions, no shooters, no passengers. The driver is alone in that cockpit, and the cockpit is the only thing between them and several G of pure punishment.

**Handling can drop during a race.** Each Tumble permanently reduces Handling by 1, to a minimum of 1. See Tumble and Handling Loss below.

\page

---

# CORE RULES

G-Zero uses the Gaslands: Refuelled movement and activation system. The core loop is unchanged: Gear Phases activate in order, each car picks a template and rolls Skid Dice, G-Force tokens accumulate, Blackouts happen.

The following is a summary of the core rules as they function in G-Zero. For full detail on anything not covered here, refer to Gaslands: Refuelled.

---

### ACTIVATION ORDER

At the start of each round, the player who holds the **Pole Position token** activates first. Play then proceeds in **initiative order**, which is the current race standing from leader to last place.

Within each Gear Phase, players take turns in initiative order. When it is their turn, a player must either:
- Activate one of their qualified vehicles (a vehicle whose Gear is equal to or higher than the current Phase number), or
- Declare a **Delayed Activation** (see below).

A player with multiple qualified vehicles may freely choose which to activate.

**A player may not skip their turn** if they have a qualified vehicle. The only way to influence when you act relative to others is through Gear choice between rounds, or through Delayed Activation within a Gear Phase.

**Pole Position passes to the player whose vehicle is currently leading the race** at the end of each round. Leadership is measured by gates passed, with distance to the next gate as the tiebreaker.

---

### DELAYED ACTIVATION

When it is your turn to activate, instead of moving immediately you may declare a **Delayed Activation**.

1. **Secretly choose your movement template now.** Note it down or set the physical template aside face-down. Your Altitude declaration also remains secret as normal.
2. **Name a target vehicle.** You may target any qualified vehicle whose controller has lower initiative than you (further from the lead in race standings).
3. The Gear Phase continues with other players activating in order. When your target vehicle completes its movement, your delayed activation resolves immediately afterwards, before any cleanup effects from the target's activation (such as a Blackout) are processed.
4. Reveal your template and Altitude and resolve your activation as normal.

If your target vehicle declares its own Delayed Activation, your delay resolves after their actual movement, not after their initial declaration. If your target is removed from the race before activating, your delayed activation resolves at the end of the current Gear Phase using the template you secretly chose.

> ##### TACTICAL NOTE
> Delayed Activation is the leader's tool. The player in front sees the chasers commit, then resolves their own move with knowledge of where the threats actually are. The cost is that you forfeit any chance to set the pace, and you cannot react to anyone moving before you in initiative order.

---

### SECRET ALTITUDE DECLARATION

At the **start of each Gear Phase**, every player with a qualified vehicle secretly notes their chosen Altitude for this activation (Low, Mid, or High) on a slip of paper or token kept face-down.

**Altitude is revealed** when:
- It is that player's turn to activate (or their Delayed Activation resolves), or
- Their car is involved in a collision before their activation, in which case both drivers involved must immediately reveal their Altitude to resolve the collision.

Once revealed, Altitude is public for the remainder of that activation. A driver's Altitude persists until their next activation.

\page

---

### GEAR PHASES

Each round, Gear Phases 1 through 6 activate in order. A vehicle activates in the Gear Phase matching its current Gear. If a vehicle changes Gear during its activation, it activates in its new Gear Phase next round.

A vehicle may change Gear by +1 or -1 for free. Changing by more than 1 in a single step costs 1 G-Force token per additional step.

---

### TEMPLATES

When a vehicle activates, the active player selects a movement template appropriate to their current Gear. Higher Gears give access to longer, faster templates but restrict turning. Lower Gears allow tighter turns.

Some template/Gear combinations are **High-G** (formerly "Hazardous"): placing the template grants 1 G-Force token before Skid Dice are rolled.

Some combinations are marked **Trivial**: they grant 1 free Dampener result without rolling any Skid Dice. You may still choose to roll Skid Dice instead if you prefer.

---

### SKID DICE

After placing the template, the active player rolls Skid Dice equal to current Handling, up to a maximum of 4. Results are resolved in the following order:

| Result | Effect |
|:---|:---|
| **Dampener** | Spend to: cancel one G-Force, Slide, or Spin result; OR change Gear by +/-1 (costs 1 G-Force token); OR remove 1 G-Force token from your car |
| **G-Force** | Gain 1 G-Force token. Cannot be cancelled. |
| **Slide** | Move to the Slide exit point on the template. Gain 1 G-Force token. |
| **Spin** | Pivot up to 90 degrees at Final Position. Gain 1 G-Force token. |

You do not have to roll all your dice. If you are sitting on 4 or 5 G-Force tokens, sometimes the correct move is to roll nothing.

> ##### NARRATIVE NOTE
> A Dampener result represents the cockpit's active stabilisers and your pilot's own physiology bleeding off accumulated stress. Every Dampener you spend is energy that does not go into the engine. Every G-Force you accept is a debt your body will eventually be asked to pay. Speed and survival are the same currency.

---

### G-FORCE TOKENS

G-Force tokens accumulate from gear changes, High-G templates, bad Skid Dice results, Altitude transitions, and collisions. A car with 6 or more G-Force tokens at the end of any activation immediately **Blacks Out**.

Track G-Force on your car using a dial, dice, or stack of tokens marked **G**.

\page

---

### BLACKOUT

> ##### DIFFERENCE FROM GASLANDS
> In Gaslands, a Wipeout can result in a car being Destroyed. In G-Zero, cars are not removed by ordinary Blackouts. A Blackout is what happens when the human inside the cockpit briefly stops being able to fly. Cumulative Blackouts at Handling 1 can eventually kill the driver (see Emergency Dampener Check).

When a car would Black Out, resolve the following steps in order:

1. **If the driver is at Handling 1**, immediately perform an **Emergency Dampener Check** (see below). If they fail, they die and the car is removed. If they survive, continue.
2. **Roll 1D6** to determine the outcome:
   - **1 or 2**: the vehicle **Tumbles** (see below). Tumble automatically applies its own Handling loss and Recovery as described in the Tumble section.
   - **3 to 6**: the driver enters **Recovery** (see below). No Tumble, no Handling loss.
3. Gear resets to 1.
4. All G-Force tokens are cleared.
5. Altitude resets to **Mid**.

The car's facing after step 2 is the facing it keeps. If a Tumble was rolled, that is the Tumble direction. If only Recovery was rolled, the facing is unchanged.

---

### TUMBLE

A Tumble at Gear 2 is embarrassing. A Tumble at Gear 6 is a multi-car incident.

**Tumble can be triggered by:**
- A Blackout result of 1 or 2.
- A Burst Template result from striking a solid object (see Collisions).
- Any other game effect that specifies Tumble.

Whatever the trigger, the procedure is the same.

**Tumble Direction:** Roll 1D6 to determine which way the car flips. The result maps to one of six 60-degree wedges around the car (1 = directly forward, 2 = forward-right, 3 = back-right, 4 = directly back, 5 = back-left, 6 = forward-left). The car's nose now points in that direction.

**Tumble Distance:** Based on the Gear the car was in at the moment of the trigger:

| Gear at Trigger | Tumble Template |
|:---|:---:|
| 1 to 2 | Short Straight |
| 3 to 4 | Medium Straight |
| 5 to 6 | Long Straight |

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
> A Tumble can chain into walls. If the tumble path lands the car against a wall, that is just a wall. The Tumble does not deflect or stop short. Walls do not gain G-Force tokens. They have other ways of objecting.

\page

---

### RECOVERY

A driver in **Recovery** skips their next qualifying activation. Mark the car with a Recovery token. The pilot is awake but the cockpit is rebooting, the harness is screaming, and the driver's vision has not yet returned to colour.

Recovery is triggered by:
- A Blackout result of 3 to 6.
- Any Tumble (as part of Tumble Aftermath).

A car cannot accumulate multiple Recovery tokens. If a car already in Recovery would enter Recovery again, treat the second trigger as having no additional effect beyond what its source already imposed (such as Handling loss from a second Tumble).

---

### HANDLING LOSS

Each Tumble permanently reduces a driver's Handling by 1 for the rest of the race, to a minimum of 1. Track the current Handling value on a dial or with markers.

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

**On a failure**, the driver dies. Their car is removed from the race.

> ##### NOTE
> The Emergency Dampener Check is the only way ordinary play can permanently kill a driver. It is the cumulative bill the body has been keeping. The first time it triggers, the driver almost always lives. The fourth time, no roll, no chance, just a name added to the lap sheet's other side.

\page

---

# DRIVER ACTIONS

The following two actions are core mechanics, not optional rules. They are how an experienced driver squeezes performance out of a system that has already started punishing them.

---

### REDOUT

A Redout is what happens when a pilot pushes through G-Force tolerance and feeds the cockpit AI a body that is no longer reliable input. They get faster reflexes for the rest of the race. They get worse hands. Forever.

> **Redout**: At the start of any of your activations, you may declare a Redout. Permanently reduce your Handling by 1 (minimum 1) for the remainder of this race. For the rest of the race, you may use any movement template regardless of your current Gear. Gear-restriction rules on templates are ignored; G-Force costs on High-G templates still apply.
>
> You may declare Redout as many times as you like across the race. Each declaration costs another point of Handling.
>
> A driver at Handling 1 cannot declare a Redout.

> ##### SURVIVAL TIP
> Redout is what you reach for in the final lap when your only path to a podium is doing things your car was not designed for. Stacking Redouts is what you reach for when you have already decided you are going to win or detonate.

---

### RED MIST

The final and only true exit from G-Zero by your own hand. A pilot under sustained extreme G eventually stops being a pilot and becomes a fine red mist coating the inside of their cockpit. Some pilots reach this state by accident. The legendary ones reach it on purpose, on the final straight, with their nose pointed at the Finish Gate.

> **Red Mist**: Once per race, at the start of one of your activations, only if you are currently in Gear 5 or Gear 6. You must add two Long Straight templates in any order, to your normal template for this activation. You roll no Skid Dice for this activation and gain no G-Force from the Red Mist movement itself. Collisions caused along the path are resolved normally for the other cars involved; you yourself ignore all G-Force from those collisions.
>
> At the end of this activation, regardless of your position on the track, your driver dies. The car is removed from the game.
>
> **Exception**: if you crossed the Finish Gate on your final lap during this activation, you are recorded as a Finisher. The result book will list your placing. Whether the obituary calls you a winner depends on where the other cars are.
>
> A driver at Handling 1 cannot declare Red Mist.

\page

---

# THE ALTITUDE SYSTEM

> ##### DESIGN INTENT
> This is the main mechanic that makes G-Zero different from standard Gaslands. All cars are hover vehicles. Altitude is the combat replacement: instead of shooting each other, drivers fight for position by flying high or diving low, and the physics of close-range altitude differentials do the damage.

Every hovercar has an **Altitude**: **Low**, **Mid**, or **High**. Track altitude with a separate token or dial alongside your Gear tracker.

Altitude is declared secretly at the start of each Gear Phase and revealed when you activate or when a collision forces it. See **Secret Altitude Declaration** under Core Rules.

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

When you declare High, you may use movement templates as if your Gear were 1+X lower than your actual Gear. X can be 0 and is paid in gained G-Force tokens. This makes tight manoeuvres available at speeds they normally are not.

| Previous Altitude | Gear Check Modifier |
|:---|:---|
| High (staying High) | -1+X for required Template Gear |
| Mid (rising to High) | +1+X for required Template Gear |
| Low (launching to High) | use any template gear and drop 1+X gears |

> ##### EXAMPLE
> Your car is at Gear 6, Altitude High. You declare High again (staying High). You choose to pay X=3 G-Force tokens. Your Gear drops to 3 (only because of the template-as-lower-Gear rule). You may now use Gear 3 templates like the Hairpin. You still have to pay the 1 G-Force for using the Hairpin in Gear 3.

#### GOING MID / STAYING MID

Mid is the recovery and stability zone. No bonus movement. No Gear Check. Just Dampeners.

| Transition | Bonus |
|:---|:---:|
| Mid to Mid | +1 Dampener result |
| Low to Mid | +2 Dampener results |
| High to Mid | +2 Dampener results |

These bonus Dampener results are added to your Skid Dice pool as free results. You may use them as normal Dampener results: cancel bad dice, change Gear, or remove G-Force tokens.

> ##### SURVIVAL TIP
> Mid is where you go to clean up. After a chaotic dive or a high-speed High run, returning to Mid gives you Dampener results to spend on G-Force removal. Learn to use Mid as a planned reset rather than just a fallback.

\page

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

\page

---

### BURST TEMPLATES

When a car strikes an object, the object shatters, deforms, or explodes. Place the appropriate Burst Template (Small, Large, or Extra-Large) centred on the point of collision. The Burst Template is oriented along the colliding vehicle's direction of travel.

**Any other vehicle whose base overlaps the Burst Template** suffers an effect determined by the object's **material**. The colliding vehicle itself is not affected by its own Burst Template; it has already paid the cost of impact through the Full Collision reaction.

The effect of the Burst Template depends on the material of the object struck. Possible outcomes include:

- Lose or gain G-Force tokens
- Lose or gain Gear
- Tumble

**A formal material/effect table is in development.** Until it is published, the players at the table decide what effect each piece of scenery produces when destroyed. Assign material categories and effects during track setup, or resolve them by group consensus in the moment. People who play games like this know how to handle it.

> ##### DESIGNER NOTE
> Burst Templates exist to make object collisions matter beyond a single car's misfortune. They are the racing equivalent of a peripheral hazard. If a leader takes out a stack of barrels on the apex of a corner, the chasers entering that apex deal with the consequences too. Place soft scenery where you want the track to forgive, place heavy scenery where you want it to bite.

\page

---

# RACE RULES

### GATES AND LAPS

Set up the track using the Gaslands Death Race scenario as a base. Gates are placed at regular intervals around the circuit. Cars must pass through each Gate in order. Passing a Gate out of sequence does not count.

A standard race is **3 laps**. The first car to complete all laps and cross the Finish Gate wins.

---

### STARTING GRID

Roll off to determine starting positions. Place cars in a single-file line at the Start Gate, separated by one car length. All cars begin at Gear 1, Altitude Mid, Handling 4, no Recovery, no Emergency Dampener Checks logged. The driver in first position receives the Pole Position token.

---

### BEING LAPPED

If a car falls more than one full lap behind the leader, it may use the **Restart Rule**: the car teleports to the last Gate it legally passed, resets to Gear 1, clears all G-Force tokens, and resets Altitude to Mid. Handling, Recovery, and Emergency Dampener Check counts are NOT reset. This keeps hopeless positions from becoming unplayable without erasing the consequences of how the driver got there.

---

### GATES IN THE AIR

Some tracks may feature **Altitude Gates**, a Gate marked with a specific required Altitude (Low, Mid, or High). A driver must be at the marked Altitude when passing through the Gate for the passage to count. Passing at the wrong Altitude does not count and does not grant the Gate, but the driver is not penalised beyond having to come back around.

Mark Altitude Gates with a coloured token on the Gate.

\page

---

# OPTIONAL RULES

### GHOST MODE

For a first game or when playing with new players: cars cannot collide with each other. Only wall and obstacle collisions apply. Removes the chaos element entirely so new players can learn the gear system and template selection without worrying about opponents. Recommended for the first race only.

---

### SLIPSTREAM

A car directly behind another car at the same Altitude and same Gear (within one car length, not overlapping) may declare Slipstream at the start of its activation. A Slipstreaming car may move its template as if it were in the next Gear up. No G-Force cost. This represents drafting off the car ahead.

---

### AUDIENCE FAVOURITE

Use the Gaslands Audience Votes system (Gaslands: Refuelled page 88) as written, with the following restrictions: any Audience Vote effect that references weapons, attacks, Hull Points, or Crew is unavailable. The most useful effects are Burn Rubber, Thunderous Applause, and Slippery Track. Others are at the referee's discretion.

\page

---

# COMING SOON

> ##### SPONSORS
> Sponsor cards will introduce asymmetric car bonuses tied to the Altitude system. A Low-specialist Sponsor might reduce the G-Force cost of Low transitions. A High-specialist might start each race with free G-Force tokens already paid toward their first High declaration. This section is in development.
 <br>

> ##### FEATS
> Feats are persistent upgrades purchased between races. They will add build customisation without adding vehicle type complexity. This section is in development.
 <br>

> ##### VEHICLE CLASSES
> Whether G-Zero ever expands beyond one car type is an open question. If vehicle classes are added, they will be differentiated through Altitude performance profiles rather than Hull/Weapon loadouts. This section is in development.
 <br>

> ##### BURST TEMPLATE EFFECT TABLE
> A formal table mapping each material category to specific Burst Template effects is in development. Until then, use player consensus during track setup or in the moment.
 <br>

\page

---

# QUICK REFERENCE

### THE HOVERCAR

| Max Gear | Handling (start) | Weight | Hull | Crew |
|:---:|:---:|:---:|:---:|:---:|
| 6 | 4 | Light | None | None |

Handling reduces by 1 with every Tumble or Redout (minimum 1).

---

### ACTIVATION ORDER

Pole Position activates first, then initiative order (race standings, leader to last). Qualified vehicles must activate or declare Delayed Activation. No passing turns.

Pole Position passes to the current race leader at end of each round.

**Delayed Activation**: secretly choose template, name a lower-initiative target vehicle, activate immediately after that vehicle moves (before its cleanup effects).

Altitude is declared secretly at the start of each Gear Phase. Reveal when activated or when a collision occurs.

---

### SKID DICE

Roll up to Handling dice (max 4). Resolve in order:

| Result | Effect |
|:---|:---|
| Dampener | Cancel a result, change Gear +/-1 (costs 1 G), or remove 1 G |
| G-Force | +1 G token (unavoidable) |
| Slide | Move to Slide exit. +1 G |
| Spin | Pivot up to 90 degrees. +1 G |

---

### ALTITUDE TRANSITIONS

| From -> To | Bonus | Cost |
|:---|:---|:---|
| Low -> Low | +Short Straight | +1 G |
| Mid -> Low | +Medium Straight | +2 G |
| High -> Low | +Long Straight | +3 G |
| High -> High | Templates as Gear-(1+X) | pay X G |
| Mid -> High | Templates as Gear-(1+X) | pay X G, +1 Gear Check |
| Low -> High | Templates as Gear-(1+X), drop 1 Gear | pay X G |
| Mid -> Mid | +1 Dampener | none |
| Low -> Mid | +2 Dampeners | none |
| High -> Mid | +2 Dampeners | none |

\page

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

Burst Template effects depend on object material. Possible outcomes: G-Force gain/loss, Gear gain/loss, Tumble. Formal table in development. Use player consensus until then.

---

### BLACKOUT

Triggered at 6+ G-Force tokens at end of activation.

1. If at Handling 1: roll Emergency Dampener Check first (2+ / 4+ / 6+ / dead).
2. Roll 1D6: on 1 or 2 = Tumble; on 3 to 6 = Recovery only.
3. Reset to Gear 1, Altitude Mid, 0 G-Force.

---

### TUMBLE

Triggers: Blackout (1 or 2), Burst Template, other effects.

1. Direction: 1D6 -> six 60-degree wedges (1=fwd, 2=fwd-right, 3=back-right, 4=back, 5=back-left, 6=fwd-left).
2. Distance: Short (Gear 1 to 2), Medium (Gear 3 to 4), Long (Gear 5 to 6).
3. Cars caught: gain G-Force = Tumble length, pivoted up to 90 degrees by active player, no reactions.
4. Tumble Aftermath: -1 Handling permanently (min 1) + Recovery token.

---

### RECOVERY

Skip next qualifying activation. Triggered by Blackout (3 to 6) or any Tumble. Does not stack.

---

### DRIVER ACTIONS

**Redout**: Declare at start of activation. -1 Handling permanently. Ignore Gear-restrictions on templates for rest of race. Stackable. Not available at Handling 1.

**Red Mist**: Once per race, start of activation, Gear 5 or 6 only. Add two Long Straight templates in any order to your normal template. No Skid Dice, no self-inflicted G-Force. End of activation: driver dies, car removed. Finish-Gate exception: recorded as Finisher if final lap completed. Not available at Handling 1.

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
