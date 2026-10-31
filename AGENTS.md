# AGENTS.md – Frozen Stick (D&D Campaign)

This repo holds the DM's notes for the D&D campaign **"Frozen Stick"**: an Obsidian vault in `DND-FozenStick/`, plus session flowcharts (`*.drawio`), Improved Initiative combat files (`improved-initiative*.json`) and maps. Most of the notes are in German. The DM is Rafael (git: rrott).

---

## 1. Working rules (mandatory)

1. **No changes to text the DM wrote without explicit approval.** This covers notes, summaries (Zusammenfassungen), backstories, lore and NPC write-ups. Fixing typos or spelling also needs approval.
2. **Batch changes only on an explicit request.** Never edit several files, or make sweeping replacements, unless the DM asks for exactly that. Default: one file, one change.
3. **Every changed file needs approval before it is saved or pushed to git.** Show the proposed change (diff or full new text) first and wait for a clear "yes". Never commit or push without being asked.
4. **Keep the original when the DM's text is changed or overwritten.** Append the original text, unchanged, at the end of the same file in a clearly separated section:

   ```markdown
   ---
   ## Originaltext (vor Änderung am YYYY-MM-DD)
   <the original text, unchanged>
   ```

Also:
- Reading, searching and summarising are always allowed.
- New content (ideas, drafts, NPCs, encounters) goes in the chat first. It only becomes a file after approval.
- Do not touch `.obsidian/` config, `.$*.drawio.bkp` or `.~lock.*` files. They belong to Obsidian, draw.io and LibreOffice.
- Keep player-facing text and DM-only secrets separate. Many topics have both a `DM Notes` and a `Player Notes` file.
- **Log every approved change** in section 13 ("Agent changelog") at the end of this file: date, file, what changed and why, newest first. Read the changelog at the start of each session to pick up recent context.
- **Log ideas discussed in chat** that have not become files in section 12 ("Planning log"), so later agents have the context.

---

## 2. Repo layout

| Path | Contents |
|---|---|
| `session1.drawio` … `Session8.drawio` | Session flowcharts with read-aloud text, rooms, encounters and loot. Each session tends to copy the previous one and extend it. |
| `improved-initiative*.json` | Combat setups per session (for Improved Initiative) |
| `Infos Torben(Gimbal).md` | Handout for Gimbal's player: arrival in Syrinlya, current situation |
| `Clovis Concord Infos.md` | Short descriptions of the Menagerie Coast cities |
| `Auftrag (Frozen Stick).pdf` | Sisman's mission letter as a PDF |
| `DND-FozenStick/Player/` | Player characters, backstories, player info |
| `DND-FozenStick/Npcs/` | NPCs (Syrinlya, Palebank, Cobalt Soul, antagonists) |
| `DND-FozenStick/Artefacte/` | Homebrew artifacts and lore texts |
| `DND-FozenStick/Texte/` | Handouts (e.g. the Aeor logbooks from the Splitterkuppeln lab) |
| `DND-FozenStick/Plot Idee.md` | Plot ideas (Mila rescue, Tamer, broken ring) |
| `DND-FozenStick/ZSessiones/` | Session 0 (house rules, world framework), Session 1, links |
| `DND-FozenStick/Worlds/Exandria/` | World lore: history, pantheon, Wildemount realms, factions, regions |
| `DND-FozenStick/Maps/` | Battle maps (Dungeondraft and images) |

---

## 3. Setting & tone

- **World:** Exandria / Wildemount (Critical Role), year **834 PD**, one year before the war between the Dwendalian Empire and the Kryn Dynasty.
- **Region:** Greying Wildlands → Palebank Village → Eiselcross (the frozen ruins of **Aeor**).
- **Tone:** High immersion, dark fantasy, harsh survival in the ice.
- **Medical realism:** Healing and medicine are described realistically and in detail (herbalism, anatomy, surgery). Magic supplements this but does not replace the dirty reality of a field hospital.
- **Aeor technology:** Cold, clinical, extremely dangerous. The focus is cybernetics, bioweapons and dunamancy (gravity and time magic).
- **House rules (Session 0):** Rolled stats (point array as fallback). Rolled HP, rerolling 1s. Milestone leveling. All hit dice return on a long rest. Core rules + 2024. No Chaotic Evil. Crits and inspiration follow the base rules.

---

## 4. Story so far

- **Setup:** The dwarf explorer **Urgon Wenth** brought Aeorian relics back from Eiselcross. He caught **Frigid Woe (Frostleid)**, an engineered Aeorian plague that turns the body to ice, and died in Palebank.
- **Session 1 (02 Horisal 834 PD):** Urgon's funeral in Palebank. The party looks into Urgon's cabin, Tulgi's cabin, Crokar Cave and the Jolly Dwarf.
- **Session 2:** Travel to Eiselcross. Arrival at the research outpost **Syrinlya**. They meet The Buyer and Orvo Mustav.
- **Sessions 3–4:** They explore **Salsvault** (Aeorian lab, the wight **Ferol Sal**) to find the Frigid Woe cure. **Bumm is infected.**
- **Sessions 5–7:** They return to a nearly empty Syrinlya. A rescue team (Bari, Orvo, Mila) has gone missing. Morgo gives the party snow wargs so they reach the lab faster. They find Mila. Gnoll attack. The **Splitterkuppeln**, a ruined Aeorian dome complex.
- **Session 8 (in planning):** The Splitterkuppeln lab with about 20 rooms (blade gallery, stasis tubes, mind-control lab, prosthetics chamber, eyeball breeding room, dissection hall, …). An arena, a prison room, the Tamer fight (loot includes Umbra's letter). Then the trip back, the funeral, and a 50 g reward per person.

---

## 5. Player characters

- **Bumm (Niklas):** Goliath barbarian, formerly the "toy" of the orc warlord Bummen under the **Iron Authority**. A flower at a shrine changed him. Urgon rescued him, which is why he's fighting the plague. Artifact: **Crystalline Peacebloom**.
- **Ekmek (Wyron) & Patates (Lucas):** Foundling "brothers" from the destroyed village of **Nebelfurt** (raided, possibly by the Shadycreek Run tribes). Raised by **Expositor Sisman Kurtarici** (Cobalt Soul, Rexxentrum). Their mission: secure Urgon's relics before the Cerberus Assembly does. Patates is a wild-magic sorcerer bound to the **Shard of Schattengrad**.
- **Gimbal (Torben):** One-armed dwarf tinkerer, born Torens Silbertuch in the Empire. Thrown out of the academy and his family, then worked in Port Zoon with the fire genasi Kindra. He is looking for Aeorian tech to build a prosthetic arm.

---

## 6. NPCs

**Syrinlya**
- **Morgo Delwur:** Dwarf, secretly a werebear, neutral good. Loud, warm, a moral compass, hates tyrants. Hates it when "Frischlinge" (inexperienced adventurers) die for nothing. Looks after the camp's snow wargs and gave the party wargs for the rescue mission.
- **The Buyer (Elloway Tenvidas):** High-elf mage, lawful neutral, **he/him**. Hides his real name. Faerie dragon Dew. Buys Aeorian relics for Uthodurn. Has a teleportation chest linked to Uthodurn's archives. Dignified and mysterious. *The lotus (illusion/fire magic) still has to be planned, not now.*
- **Vethar (druid):** *(no file yet; the DM will add one later)* Runs a field hospital in Syrinlya. From the jungle of Far Hhrome (Kryn Dynasty), raised among beastfolk. A calm, focused pragmatist. Remedies:
  - Iceland moss, arnica flowers, volcanic ash → warming paste against frostbite
  - Willow bark, valerian root → shock brew against pain and panic
  - Sphagnum moss, ribwort plantain → wound compresses that stop bleeding
  - Sea buckthorn berries → carrier for "Goodberry" magic
- **Orvo Mustav:** Dwarf guide, part of the rescue team (Bari, Orvo, Mila). He wears the twin of the vital / mana-stone ring. The cracked ring in the command tent was the distress signal ("the dwarf" in `Plot Idee.md` = Orvo). Killed by the Tamer's beasts.
- **Professor Gulrim Shalebrow:** Founded Syrinlya for Queen Fruunast (Uthodurn). Almost always away.

**Palebank Village**
- **Elro Aldataur** (village leader), **Arl Bortock** (innkeeper of the Jolly Dwarf).
- **Bari "Frost":** Grumpy career guard from the Flotket Alps, with a good heart.
- **Mila Tenno:** Young guard (Glassblades). Wears the **Frostphönix-Träne** amulet.

**Cobalt Soul**
- **Sisman Kurtarici:** "The Disenchanter". A former gifted mage who walked away from the Cerberus Assembly and became a monk-expositor.

---

## 7. Antagonists

- **The Paradox Weaver:** A time Primordial. The gods shattered its core into soul shards and hid them. The hidden main villain.
- **Vaelis Nyx ("Umbra"):** Xhorhasian chronurgy wizard, level 9+, whose mind has merged with a Weaver fragment. Pretext: steal Aeorian bioweapons and start a war between the Empire and the Kryn Dynasty. Real goal: Aeorian data crystals, star charts and time records to find the other shards. The war is cover. His sealed letters trap whoever opens them in a time loop.
- **The Tamer:** Ranger-mercenary from the Underdark who breaks beasts through fear. Sadistic, feeds prisoners to his beasts. Mid-level boss. Your notes add: if captured and questioned, a seal or hex kills him.
- *Handover:* Umbra's mercenaries are highly professional. They looted and wrecked the Splitterkuppeln lab and murdered the novice adventurers (including the NPC **Varek**; probably no file needed).
- *Idea:* The **Shard of Schattengrad** may also be a Primordial fragment (Night or Order).

---

## 8. Handover from the previous agent (status quo)

- The party is dealing with the aftermath of exploring the **Splitterkuppeln lab**, an Aeorian bioweapons lab that Umbra's mercenaries had already looted. (The handover wrongly called it Salsvault. Salsvault is the Frigid Woe lab from sessions 3–4.)
- **The syringe incident:** A player injected raw mutation tissue in the **eyeball breeding room** ("Augen-Zucht-Raum").
  - Immediate: veins turn black, poison damage, *poisoned* + *exhaustion*.
  - Long term: hallucinations (sees infrared and magic, but disadvantage on sight-based Perception). Small eyes form under the skin. Needs medical treatment from Vethar.
- **Next scene: sea burial**
  - Syrinlya coast at dusk. A symbolic funeral (the bodies stayed in the ice) for Varek and the other fallen mercenaries, in a small wooden boat.
  - Players can place mementos or flowers in the boat.
  - Morgo gives an honest, rough speech mourning the inexperienced adventurers. She deliberately hides the truth about Umbra's murders to avoid panic in the camp.
  - The Buyer stands on a cliff and sets the boat alight with a glowing blue-violet lotus.

---

## 9. Items & loot

**Existing artifacts (files in `Artefacte/`)**
- **Shard of Schattengrad** (Patates): Common → Legendary. Chaos valve with 3 charges for Wild Magic Surges. Later +1/+2/+3 and "Arcane Tap".
- **Crystalline Peacebloom** (Bumm): when he heals himself, +1d4 and spores that heal or cure poison for up to 2 allies. Downside: no STR modifier on damage until the end of his next turn. Upgrades are planned.
- **Frostphönix-Träne** (Mila): at 0 HP it freezes the wounds shut. Cracks after being used.
- **Annalen der Transzendenz:** Lore fragment (Aeor's hubris: "gods as batteries").

**From the handover**
- **Aeorian resonance core** (for one specific player, likely Gimbal and his prosthetic): Inactive, beats like a heart, weightless. Once built into a prosthetic or armor, it negates the item's weight (armor loses its drawbacks / weapon gains Finesse), and once per day allows a gravity discharge (force damage + push). Dangerous on bare skin contact.
- **Umbra mercenary loot:**
  - *Chronometer of Echoes:* pocket watch, +2 initiative once per day
  - *Umbra gravity chalk:* draws floating, glowing notes in the air
  - *Ring of the Light Swallower:* bonus action, extinguishes non-magical light within 30 ft, once per long rest
  - *Vial of temporal dust:* rewinds time on a broken object and repairs it (1 use)
  - *Spell scroll:* Magnify Gravity

**Lore handouts (`Texte/Spliterkupeln Labor.md`):** three damaged Aeor logbooks
1. Chief arcanist's log: de-massification via resonance cores. Too much power → the feedback shatters bone.
2. Subject 14-Sigma report: the shoulder tore off because the mind couldn't control the weightless acceleration of the prosthetic.
3. Error log: inactive cores dissolve biomass unless coupled to a mechanical circuit (or kept in lead). Skin contact → flesh collapses in on itself (implosion).

---

## 10. Canon decisions by the DM (2026-10-24)

These are settled. Treat them as canon:
- **Lab:** The handover's lab (eyeball breeding room, syringe incident, Umbra's looting) is the **Splitterkuppeln lab**, not Salsvault.
- **Morgo:** werebear, and she looks after the snow wargs. She gave the party wargs for the rescue.
- **Urgon's surname is Wenth.** "Widor" in the mission letter and the Ekmek/Patates player info was a mistake. It's marked there with a hidden Obsidian comment (`%% … %%`) and the text stays unchanged. The session 1 funeral speech and the PDF stay as they are.
- **Year:** 834 PD is correct. The DM will fix Bumm's timeline after the campaign start.
- **Ring:** "the dwarf" with the twin ring = **Orvo**. The rescue team = **Bari, Orvo, Mila**.
- **Timeline:** the ring has been pulsing for about an hour (not 18 hours). The expedition left ten days ago (`Plot Idee.md`).
- **Spellings:** **Orvo Mustav**, **Mila** (file renamed to `Mila Tenno.md`).
- **Shadycreek Run:** four families: Mardoon, Uttolot, Trebain, Jagentoth.
- **Clovis Concord:** eight cities: Port Damali, Port Zoon, Gwardan, Tussoa, Othe, Feolinn, Nicodranas, Brokenbank. Brokenbank still has no description (TODO in `Clovis Concord Infos.md` and `Clovis Concod SubItems.md`).
- **The Buyer:** he/him.
- **To be added later:** Vethar's file, the Buyer's lotus scene. Varek probably needs no file.

## 11. Remaining inconsistencies (unchanged, for reference only)

- Bumm's rescue is dated **835 PD** (campaign: 834 PD). The DM will fix this.
- `Infos Torben(Gimbal).md` line 50: left 10 days ago + 5 days of travel = 5 days on site, but the text says 6.
- `Elloway Tenvidas (The Buyer).md` line 30 still says "ihn/sie" (not part of the approved change).

---

## 12. Planning log (discussed, not yet in files)

Ideas and drafts the DM discussed with agents in chat that have not become files yet. Read this at the start of each session together with the changelog. Newest first. When an idea becomes a file, add "→ file: …" to its entry. Format:
`YYYY-MM-DD – topic – status – what was discussed / decided / still open`

- 2026-10-27 – **Aeorischer Resonanz-Kern** (Gimbal) – Common stage written → file: `DND-FozenStick/Artefacte/Aeorischer Resonanz-Kern.md` – Final Common: +2 STR or DEX (mode switch at a long rest, max 20) + one **core slot** per long rest: either a known core elixir or a normal Experimental Elixir roll. Start recipes: **Gravity Vial** (#3) and **Orbit Elixir** (#14). Parked: #6 stasis serum, #8 resonance tincture. Evolution path drafted (Uncommon → Very Rare; Legendary reserved). **Still open:** lore of the gravity Primordial (name ideas: Vharun, Orrhaxis); the DM wants to think about it. Earlier discussion below. – Confirmed for Gimbal (alchemist artificer). It currently powers his prosthetic arm. It's an evolving item, like the Peacebloom and the Shard (base state + evolution path). **It has no burden or drawback (DM decision).** Base state: +2 STR or DEX (agent idea: switchable mode at a long rest, max 20). Agent's ideas for the alchemist bonus: A) roll elixirs twice and pick, B) throw an elixir to an ally 30 ft away as a bonus action, C) stasis vial (an elixir survives the long rest; time link), D) gravity push on alchemical damage, E) blood analysis (Medicine/Investigation advantage, Lesser Restoration), F) maximise an elixir 1×/long rest. Agent recommended A or B for Common and C for later. **DM has not chosen yet.** Lore: indirectly tied to the Primordials (not relevant yet). The handover concept in section 9 (weight negation, gravity discharge) may become a later stage.

---

## 13. Agent changelog

Newest entries first. One entry per approved change. Format:
`YYYY-MM-DD – file – what changed – why / decided by the DM`

- 2026-10-27 – `DND-FozenStick/Artefacte/Aeorischer Resonanz-Kern (Handout).md` – created: player handout for Gimbal, Common stage only (no evolution path, no DM notes) – approved by the DM
- 2026-10-27 – `DND-FozenStick/Artefacte/Aeorischer Resonanz-Kern.md` – created: Gimbal's evolving artifact (mass calibration, core slot, Gravity Vial, Orbit Elixir, evolution path); planning log entry updated – approved by the DM
- 2026-10-27 – `AGENTS.md` – added section 12 "Planning log" for chat discussions (first entry: Resonanz-Kern); the changelog is now section 13; new rule in section 1 – requested by the DM

- 2026-10-24 – `AGENTS.md` – recorded the DM's decisions on inconsistencies 1–15 (section 10), updated the NPC and story sections – approved by the DM (P1)
- 2026-10-24 – `Elloway Tenvidas (The Buyer).md` – Buyer is he/him: removed "nicht-binär", "sie/ihn" → "ihn", "Er/Sie" → "Er" (lines 3, 9, 26, 28); originals at the end of the file – approved (P8)
- 2026-10-24 – `Clovis Concord Infos.md`, `Clovis Concod SubItems.md` – "sieben" → "acht stolzen Stadtstaaten"; added a Brokenbank section with a TODO; originals at the end – approved (P7)
- 2026-10-24 – `Greying Wildlands.md` – Shadycreek Run: "sieben kriminellen Clans" → "vier kriminellen Familien (Mardoon, Uttolot, Trebain und Jagentoth)"; original at the end – approved (P6)
- 2026-10-24 – `Npcs/Palbank Village/Milla Tenno.md` → `Mila Tenno.md` – renamed – approved (P5)
- 2026-10-24 – `Plot Idee.md` – "seit 18 Stunden" → "seit knapp einer Stunde"; Briefing: the 18-hour distress flare → "Ten days ago, almost everyone went out … Their report never came." ("your Dwarf" kept); originals at the end – approved (P4)
- 2026-10-24 – `Auftrag (Frozen Stick).md`, `Ekmek (Wyron).md`, `Patates (Lucas).md` – hidden Obsidian comment `%% Fehler beim Erstellen – richtiger Name: Urgon Wenth %%` after "Urgon Widor"; text unchanged – approved (P3)
- 2026-10-24 – `Morgo Delwur.md` – new bullet "Warg-Halterin"; "Orvo Mustave" → "Orvo Mustav"; original at the end – approved (P2)
- 2026-10-24 – `AGENTS.md` – added this changelog section and the rule to log changes here – requested by the DM
- 2026-10-24 – `AGENTS.md` – created: working rules, campaign context, the previous agent's handover, open questions, inconsistencies – requested by the DM
