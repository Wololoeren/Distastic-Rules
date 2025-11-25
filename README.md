# Dicetastic Rules
The rules and glossary for **Dicetastic**.

---

## Initializing the Game
- **Players:** Two teams of 3 players sit around a table in alternating order (A–B–A–B–A–B).
- **Starting player:** All players roll. The highest roll chooses a starting player.
- **Drafting classes and ability cards:**
  1. Make **7 face-up piles**, each containing **1 class card + 1 ability card**.
  2. Starting player chooses one pile. Continue choosing clockwise until everyone has one.
  3. Discard all unchosen cards.
- **Deck setup:** Place the class deck and ability deck face down in the center. Place their discard piles face up beside them.
- **Starting health:** Each player starts with the health shown by their **first class** (white number in the top-right corner). Track health with counters.
- **Zeroth (0) round:** Play one full round where each player may **only play ability cards** on their turns.
  - **All classes are inactive during Round 0.**
  - This prevents everyone from firing class effects immediately and keeps the opening from turning into chaos.

---

## Start the Game
### Turn order
- **Round 1 begins** with the starting player.
- Turns proceed clockwise.
- After all players take a turn, a new round begins.
- You may configure variants as desired (see “Initializing the Game”).

---

## Attack Roll
On your turn you make an **attack roll**.

1. Roll **6d6**.
2. After each roll, you must **set aside at least 1 die**.
3. Set-aside dice are locked. All other dice are **free dice** and may be rerolled.
4. Continue until all dice are set aside.
5. Add all set-aside dice together. This total is your **attack-score**.

**Goal:** reach **above 30**.

**Extra dice:** After the first die you set aside in a roll, every additional die you set aside during that same roll counts as an **extra die** (some class effects care about this).

### Attack-score outcomes
- **Attack-score < 30:**  
  You take **self‑inflicted damage equal to (30 − attack-score)**.
  - Example: attack-score 25 → take 5 self‑inflicted damage.

- **Attack-score = 30:**  
  Draw **1 ability card**.

- **Attack-score > 30:**  
  You proceed to a **damage roll**.  
  Your **target number** = (attack-score − 30).  
  - Example: attack-score 33 → target number 3.

> **Overcharge cap:** If your attack-score is above 36 (target number > 6), you still roll for **6s** in the damage roll. Each 6 counts as your target number.

---

## Damage Roll
1. Roll **6d6**.
2. Set aside any dice matching your target number.
3. Reroll free dice until no more target numbers appear.
4. Add all set-aside dice together — that total is the damage you deal to your current target.

### Rollover
If you set aside **all 6 dice** as target numbers, you trigger **Rollover**:
- Roll a fresh 6d6 and continue the damage roll.
- Add new set-aside dice to the same damage total.
- Rollover can happen multiple times in a single damage roll.

### Targets during an attack
- You main target is then next alive enemy player unless an effect says otherwise.
- If your main target dies, Your new target becomes the next alive player clockwise from the dead target.
- If you main target is revived your target reverts back to your main target.
  You skip allies unless no enemies remain.

---

## Glossary

**Spillover:** If you deal more damage than a target has health remaining, excess damage transfers to the **next valid target** clockwise. If no enemy targets remain, spillover hits yourself or the next ally clockwise.

**Abilities:** Effects gained from classes and ability cards.

**Ability card:** You may play an ability card at any time unless stated otherwise.  
After resolving, discard it to the ability discard pile. Ongoing ability cards stay in front of you until they end or you die.

**Classes:** Each class has **Passive** and/or **Active** abilities. Keep your classes in front of you.

**Overcharge:** If an effect increases your target number above 6, you still roll for 6s. Each 6 counts as your target number.

**Health:** You cannot heal above your starting/max health.

**Passive:** Always resolves when triggered.

**Active:** Optional; you may choose whether to resolve it when triggered.

**Dead:** At 0 HP you become dead. Dead players cannot attack, be attacked, be targeted, play cards, or take damage. You can be revived by effects.

**Inactive:** Rotate a class upside down to show it is inactive. You may reactivate **one inactive class at the start of your turn** unless an effect says otherwise.

**Disable:** Flip a class face‑down. It does not function and cannot be reactivated until a condition is met.

**Empower:** Trigger one effect **ignoring its normal triggers**.

**Untargetable:** If other valid targets exist, you cannot be chosen. Forced targeting overrides this only if the forcing effect says it can.

**Heal / Revive:**  
Heal restores HP up to max. Dead players cannot be healed; they must be revived. Revive returns a dead player to life with **1 HP** and re‑enables their classes.

**Swap / Steal / Reroll / Flip:** Standard card terms (see card text for specifics).

**Permanent gains:** Effects that increase and stay increased until the class is discarded. Track the value on the card.

**Current target:** The player(s) you are attacking this turn.

---

## Resolving Priority

**Card‑draw priority:** When you draw a card, you must read it and decide whether to keep or play it **before the game continues**.

**Play precedence:** Effects resolve in the order they are played: **first played, first executed**. If still unclear, priority goes to the player with the most recent turn.

**Class precedence:** Resolve your class abilities **left to right**. You may reorder your classes at the end of your turn.

**Conflicting event execution:** If two events trigger simultaneously and the first event removes the second event’s trigger, the second event is cancelled.

**Shared class abilities:** If you share a class, you gain its effects as if you owned it. Shared classes cannot be discarded/removed/transferred via sharing.

---

## Damage Types

- **Damage:** From a damage roll or a newly created damage instance.
- **Extra‑damage:** Added on top of an existing damage instance.
- **Self‑inflicted damage:** Damage with no attacker.
- **Spillover‑damage:** A new damage instance created when leftover damage transfers after a target dies.

---

## Triggers

- **When:** Resolve simultaneously with the result (pause current execution, resolve the effect, then continue).
- **Before:** Resolve before the result (pause execution, fully resolve effect, then continue).
- **After:** Resolve after the current execution fully finishes.

---

## Recommendations

**Reducing complexity:** More classes in play increases complexity and play time. Consider a class limit for large groups or new players.

**3‑second rule:** After any event, wait ~3 seconds so players can call triggers.

**Anti‑recurrence:** An identical trigger cannot cause the same effect more than once in a single chain. If you hit an infinite loop, stop after the first repetition.
