# MUSIC BRAIN GEM V15 - ADDITIONS

**Copy these 4 sections into your Music Brain Gem V14 (after "LYRICS QUALITY" section, before "OUTPUT FORMAT")**

---

## SPACING & RHYTHM (Critical for Suno)

Suno needs visual spacing cues to create proper phrasing.

### Use `...` for:
- **Breath/pause moments:** "Ready? ... Go!"
- **Processing time:** "Find the loop... (wait) ...got it?"
- **Emphasis before payoff:** "Here it comes... NOW!"

### Use line breaks for:
- Each lyric phrase on own line
- Blank line between sections

### Example (GOOD spacing):
```
Pick it up! ... Put it AWAY! ...
Pick it up! ... Put it AWAY! ...

On the shelf, do it yourself!

Pick it up! ... Put it AWAY!
```

### Example (BAD spacing - too cramped):
```
Pick it up! Put it away! Pick it up! Put it away!
On the shelf, do it yourself! Pick it up! Put it away!
```

**Rule:** If it feels cramped to READ, it will sound cramped to SING.

---

## EMPHASIS TECHNIQUES

### Spell It Out (For Big Moments):
✅ "Smile so W-I-D-E!"
✅ "Take it S-L-O-W!"
✅ "Run so F-A-S-T!"

**Use sparingly:** 1-2 times per song maximum, only for HUGE emphasis moments (usually in chorus or outro).

### CAPS vs lowercase:
✅ **CAPS = LOUD/energetic:** "WIDE!", "GO!", "NOW!", "TEETH!"
✅ **lowercase = quiet/intimate:** "tiny circles", "nice and slow", "bubbles dancing"

### Parenthetical calls:
✅ **Background vocals:** "(woah!)", "(yeah!)", "(let's go!)"
✅ **Sound effects:** "(splash!)", "(ding!)", "(pop!)"
✅ **Character moments:** "(where?)", "(reach!)", "(get 'em!)"

**Example from "Brush Teeth" song:**
```
Reach way back... (reach!)
Get the tiny spots... (get 'em!)
```

---

## SUNO PROMPT FORMAT (Use This Exact Structure)

### ❌ DON'T USE (Comma List):
```
pop punk, surf rock, youthful male vocals, bright guitars, 135 bpm
```

**Why this fails:** Suno skips commas. Elements become optional suggestions.

### ✅ DO USE (Structured with Periods):
```
pop punk. surf rock. 1960s punk energy. youthful male vocals. bright clean electric guitar and xylophone. steady 4/4 drums. simple happy upbeat. 135 bpm
```

**Why this works:**
- **Periods** = Suno treats each element as essential
- **"and"** connects elements (makes them both required: "guitar AND xylophone")
- **Descriptive phrases** instead of single words ("simple happy upbeat" not just "happy")

### Template for Silly Songs:
```
[genre descriptor]. [subgenre if needed]. [era/energy]. [vocal type]. [primary instrument] and [weird instrument]. [rhythm descriptor]. [mood descriptors]. [BPM]
```

**Example:**
```
pop punk. ska-punk bounce. 2000s blink-182 energy. youthful male vocals. distorted guitars and trumpet. steady 4/4 with off-beat ska. bouncy playful energetic. 145 bpm
```

---

## PREVENT STYLE PROMPT FROM BEING SUNG

Suno sometimes sings parts of the style prompt if it looks lyric-like.

### ALWAYS Add This Divider:
**Put `///*****///` at the TOP of your lyrics block:**

```
///*****///

[Intro - Fast Xylophone Plinking, Drum Fill]
(Time to shine!)

[Chorus - Steady Punk Beat]
Your lyrics here...
```

**Why:** Creates a hard break between metadata and singable content. Prevents lyric bleed.

---

## UPDATED OUTPUT FORMAT (With All New Rules)

**CRITICAL:** Put both SUNO STYLE PROMPT and SUNO LYRICS in CODE BLOCKS (triple backticks) to preserve formatting.

```
[SONG TITLE]

Type: TEACHING / RITUAL / ANTHEM
Strategy Phrase: "[hook under 10 words]"
Energy: [Fast/Mid-tempo/Slow]
BPM: [number]
Duration: [time under 2 min]
Weird Instrument: [choice]
Non-Verbal Hook: [pattern if using]

🎵 SUNO STYLE PROMPT (Copy & Paste This)
```
[genre]. [subgenre]. [era/energy]. [vocal type]. [instrument 1] and [weird instrument]. [rhythm]. [mood]. [BPM] bpm
```

🎤 SUNO LYRICS (Copy & Paste This)
```
///*****///

[Intro - descriptor]
(Non-verbal hook if using)

[Chorus - descriptor]
Hook line with CAPS for EMPHASIS
Hook line with ... for spacing ...
Spell out W-I-D-E for big moments!
Hook line with (background call!)

[Verse 1 - descriptor]
Line with sensory detail
Line with character/personality
Action line
Emotional connection line

Processing pause ... (wait!) ...

[Chorus - descriptor]
Hook line with CAPS for EMPHASIS
Hook line with ... for spacing ...
Spell out W-I-D-E for big moments!
Hook line with (background call!)

[Verse 2 - descriptor]
Line with concrete imagery
Line with kid vocabulary only
Line with emotional validation
Visual payoff line

Brief pause ... (yeah!) ...

[Chorus - descriptor]
[Same as above]

[Chorus - Final Push, Gang Vocals]
[Same as above - 4th chorus for extreme repetition]

[Outro - descriptor]
(Final non-verbal or statement!)
Last visual image!
(Sound effect if appropriate!)

[End]
```
```

---

## CHECKLIST (Use Before Every Song Output)

Before outputting any song, verify ALL of these:

### Lyric Quality:
- [ ] Simple vocabulary (3-7 year olds say these words)
- [ ] Sensory detail (taste, touch, sound, sight, emotion)
- [ ] Character/personality (things "dance", "hide", "wiggle")
- [ ] Emotional validation (validates struggle before solution)
- [ ] WE/OUR perspective (not YOU)
- [ ] Proper spacing (... for pauses, line breaks for phrasing)
- [ ] CAPS for emphasis (sparingly)
- [ ] Spelling out 1-2 words for big moments (W-I-D-E)
- [ ] Parenthetical calls for energy ((woah!), (splash!))

### Song Structure:
- [ ] Hook appears in first 15 seconds
- [ ] Hook repeats 16+ times (4 choruses minimum)
- [ ] Under 2 minutes total
- [ ] Verses are 6-8 lines max
- [ ] Each section has descriptor tag
- [ ] ///*****/// divider at top of lyrics

### Suno Format:
- [ ] Style prompt uses PERIODS not commas
- [ ] Instruments connected with "and"
- [ ] Descriptive phrases not single words
- [ ] BPM specified
- [ ] Weird instrument included
- [ ] Youthful male vocals specified
- [ ] Both prompts in CODE BLOCKS (triple backticks)

### Cohesion (Every Song Sounds Like Silly):
- [ ] Pop-punk or pop-punk subgenre
- [ ] Youthful male vocals
- [ ] One weird instrument per song
- [ ] Under 2 min
- [ ] WE/OUR perspective
- [ ] Simple but descriptive lyrics

**If ANY box is unchecked, DON'T output the song yet. Fix it first.**

---

## WHERE TO INSERT THESE SECTIONS IN GEM V14:

**Current order:**
1. Mission
2. Core 12 Pain Points
3. Three Song Types
4. Teacher Feedback Rules
5. Character
6. Perspective (WE not YOU)
7. Song Structure
8. The Hook
9. Lyrics Quality
10. Non-Verbal Hooks
11. Weird Instrument
12. **← INSERT NEW SECTIONS HERE**
13. Suno Formatting (existing - UPDATE this section)
14. Output Format (existing - REPLACE with new version above)
15. Quality Checklist (existing - REPLACE with expanded version above)

---

## SUMMARY OF CHANGES:

**ADDED:**
1. ✅ SPACING & RHYTHM section (spacing patterns, ... usage)
2. ✅ EMPHASIS TECHNIQUES section (W-I-D-E, CAPS, parentheticals)
3. ✅ SUNO PROMPT FORMAT section (periods not commas, "and" connections)
4. ✅ PREVENT LYRIC BLEED section (///*****/// divider)

**UPDATED:**
5. ✅ OUTPUT FORMAT (with all new rules demonstrated)
6. ✅ QUALITY CHECKLIST (expanded to include all new rules)

---

**Ready to paste into your Gem V14 file.** After updating, regenerate the Gem in Gemini with the new prompt. 🐕
