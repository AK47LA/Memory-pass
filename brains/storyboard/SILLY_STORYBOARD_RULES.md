# SILLY STORYBOARD RULES (HARDCODED)
**Last Updated:** February 2, 2026  
**Source:** Taste It Try It production learnings + Pick It Up analysis

---

## 🚨 MANDATORY PRE-STORYBOARD CHECKLIST

Before creating ANY Silly storyboard:

### 1. AUDIO ANALYSIS FIRST (NON-NEGOTIABLE)
```bash
# Get word-level timestamps from actual audio
curl -s https://api.openai.com/v1/audio/transcriptions \
  -H "Authorization: Bearer $OPENAI_API_KEY" \
  -F file="@[AUDIO_FILE]" \
  -F model="whisper-1" \
  -F response_format="verbose_json" > /tmp/transcription.json

# Parse segments
python3 -c "
import json
with open('/tmp/transcription.json') as f:
    data = json.load(f)
for seg in data['segments']:
    print(f\"{seg['start']:.1f}s - {seg['end']:.1f}s: {seg['text'].strip()}\")
"
```

**NEVER estimate timestamps. ALWAYS verify against actual audio.**

### 2. CONFIRM SONG STRUCTURE
Map out actual sections with verified timestamps:
- Intro duration
- Chorus start time (hook placement)
- Verse durations
- Bridge timing
- Outro duration

---

## 📏 SHOT LENGTH RULES (HARDCODED)

| Rule | Value | Source |
|------|-------|--------|
| **Average shot** | 1.5-2.0s | Kid attention research |
| **Maximum shot** | 4.0s | Only for final logo shot |
| **Minimum shot** | 0.14s | Micro-cuts only |
| **NO LONG HOLDS** | Never > 4s | Pick It Up 8.8s failure |
| **Hook timing** | Within first 10s | Engagement research |

### WHY NO LONG HOLDS:
- Pick It Up had 8.8s hold at 20-29s mark
- Adrian's daughter lost attention there
- Kids expect cuts every 1-2s
- Long holds = brain shifts from "following" to "waiting"
- **FIX:** Break any section > 4s into multiple shots

---

## 🎯 SHOT COUNT FORMULA

```
Total Shots = Song Duration (seconds) ÷ 1.7

Examples:
- 60s song = ~35 shots
- 90s song = ~53 shots
- 120s song = ~70 shots
```

**Add 7 micro-cuts for climax/outro**

---

## 🎤 LIP SYNC RULES

### MUST FLAG AS 🎤 LIP SYNC:
- All hook/chorus repetitions ("Taste it, try it, yum, let's go!")
- Key phrases ("One little bite now!")
- Bridge dialogue
- Outro exclamations ("Whoa!", "Hey!")

### LIP SYNC PROCESSING:
- Use Kling AI for mouth animation
- Process AFTER image-to-video generation
- Only needed for 2-3 close-up shots per song (optional)

### EXPECTED COUNT:
- ~25-30% of shots should be lip sync flagged
- For 55-shot video = ~15-20 lip sync shots

---

## 🔄 MULTISHOT RULES

### WHAT MULTISHOT IS:
1. Generate a shot (with your prompt)
2. Click "multishot" button on that image
3. Get 9 variations automatically (no additional prompts)
4. Pick best 2-3 for editing variety

### WHEN TO USE MULTISHOT:
Flag these moments as 🔄 MULTISHOT:
- **First emotional beat** (first bite, first try, discovery)
- **Key dialogue** ("YEP!", response moments)
- **Victory/celebration** (climax poses)
- **Final hero shot** (logo shot)

### EXPECTED COUNT:
- 3-5 multishot moments per song
- Pick 2-3 variations from each for editing

---

## 🎬 MICRO-CUT RULES

### WHAT THEY ARE:
- 7 rapid shots in ~1 second (0.14s each)
- Create energy burst at climax
- Hard cuts, NO transitions

### STANDARD MICRO-CUT ELEMENTS:
1. Character eyes (ECU)
2. Skateboard wheels spinning (ECU)
3. Sun/light glint (detail)
4. Character hair/mohawk (ECU)
5. Environment element (palm tree, wave)
6. Character smile (ECU)
7. Sound visualization (trumpet burst, energy)

### PLACEMENT:
- At climax (usually around 85-90% through song)
- Before final hero shot
- During outro energy peak

---

## 📍 LOCATION RULES

### ONLY TWO LOCATIONS:
1. **Room of Wonder** (indoor, teaching moments)
2. **Venice Beach** (outdoor, energy/celebration)

### TYPICAL SPLIT:
- Teaching/ritual songs: 70% ROW / 30% Beach
- Energy/anthem songs: 40% ROW / 60% Beach
- Always end at Beach (celebration/reward)

### NEVER:
- Random cities
- Fantasy locations
- Schools/classrooms
- Other people's houses

---

## 📝 STORYBOARD FORMAT

### SHOT TEMPLATE:
```
**SHOT [#]** | [START]-[END] | [DURATION]s | [TYPE]
```
ACTION: [What Silly is doing]
LOCATION: [Room of Wonder / Venice Beach]
CAMERA: [Shot type, angle, movement]
EXPRESSION: [Silly's emotion]
SYNC: [🎤 YES / NO]
LYRICS: "[The lyrics during this shot]"
CUT ON: [What triggers next cut]

NANO BANANA PROMPT:
"[Full detailed prompt for image generation]"

CANON REFERENCE: [XX_silly_soul_id.png] - [EXACT/CLOSE/GENERATE NEW]

🎬 KLING: [Motion description for video generation]
```

### REQUIRED SECTIONS:
1. Quality checklist (all passed)
2. Audio structure table (verified timestamps)
3. Shot-by-shot breakdown
4. Production summary
5. Multishot checklist

---

## ✅ QUALITY CHECKLIST (MUST PASS ALL)

Before delivering storyboard, verify:

- [ ] **Audio timestamps verified** (not estimated)
- [ ] **No shot > 4 seconds** (except final logo)
- [ ] **Average shot 1.5-2s** (calculate actual)
- [ ] **Hook in first 10 seconds** (verify against audio)
- [ ] **No long holds** (no 8.8s Pick It Up problem)
- [ ] **Micro-cuts at climax** (7 shots, 0.14s each)
- [ ] **Lip sync flagged** (25-30% of shots)
- [ ] **Multishot flagged** (3-5 key moments)
- [ ] **All prompts copy-paste ready**
- [ ] **Canon references noted**

---

## 🔧 TOOLS & WORKFLOW

### PHASE 1: AUDIO ANALYSIS
- Tool: OpenAI Whisper API (verbose_json)
- Output: Section timestamps, lyrics sync points

### PHASE 2: STORYBOARD CREATION
- Tool: Music Brain Gem (optional for lyrics)
- Tool: Storyboard Brain Gem (shot breakdown)
- Or: Manual creation following this template

### PHASE 3: IMAGE GENERATION
- Tool: Higgsfield nano-banana-pro (text-to-image)
- Process: Copy prompt → Generate → Download
- Enhancement: Click Multishot for key moments

### PHASE 4: VIDEO ANIMATION
- Tool: Higgsfield image-to-video
- Settings: 3-5 sec per shot, medium motion
- Optional: Kling AI for lip sync (2-3 close-ups)

### PHASE 5: EDITING
- Tool: CapCut
- Style: MTV pop-punk (see CAPCUT_WORKFLOW_MTV_STYLE.md)
- Key: Cuts on beats, no slow builds

---

## 📚 REFERENCE FILES

| File | Purpose |
|------|---------|
| `CAPCUT_WORKFLOW_MTV_STYLE.md` | Editing style guide |
| `GEM_SILLY_STORYBOARD_BRAIN_FINAL_V2.md` | Storyboard Gem prompt |
| `GEM_SILLY_MUSIC_BRAIN_V15_COMPLETE.md` | Music/lyrics Gem |
| `SILLY_SONGS_LIBRARY.md` | Song catalog |
| `SOUL_ID_EXACT_PROMPTS.md` | Character consistency |
| `~/Desktop/Silly the Seal Canon/` | 51 reference images |

---

## 🚫 COMMON MISTAKES TO AVOID

1. **Estimating timestamps** → Always analyze actual audio
2. **Long establishing shots** → Max 2.5s, not 4s
3. **Slow pre-climax build** → Kids don't appreciate tension
4. **Missing lip sync flags** → Flag all hook lines
5. **Wrong Multishot understanding** → It's POST-generation, not 3-prompt setup
6. **Forgetting micro-cuts** → Essential for climax energy
7. **Locations outside world** → Only ROW and Venice Beach
8. **Too much text, not enough reference** → REFERENCE IMAGES ARE SOURCE OF TRUTH

---

## 🎯 REFERENCE IMAGE RULE (HARDCODED Feb 2, 2026)

**Relying too much on text causes character drift. Reference images are the source of truth.**

### REFERENCES PER SHOT:
- **Ref 1 (Character):** `~/Desktop/Silly the Seal Canon/[XX]_silly_soul_id.png` — ALWAYS full-body
- **Ref 2 (Environment):** `~/Desktop/SILLY_CANON_REFS/[location].png`
- **Ref 3 (Guitar):** `~/Desktop/SILLY_CANON_REFS/Silly Guitar.png` — FOR SINGING SHOTS ONLY

### ENVIRONMENT REFERENCES:
- Room of Wonder: `Room Of Wonder Master Main.png`
- ROW Exterior: `Room Of Wonder Extiroir.png`
- Venice Beach: `Venice Beach Skatepark.png`

### GUITAR RULE (HARDCODED Feb 2, 2026):
**When Silly is SINGING/PERFORMING → he has his GUITAR**
- Use guitar reference as 3rd image
- Describe guitar in pose: "holding guitar", "strumming", etc.
- Guitar refs in `~/Desktop/SILLY_CANON_REFS/`:
  - `Silly Guitar.png`
  - `Silly + guitar standing.png`
  - `Silly + guitar interaction and poses.png`

### PROMPT FORMAT:
Text describes:
- ACTION (what Silly is doing)
- POSE (body position, flippers, guitar if singing)
- EXPRESSION (face, mouth, eyes, energy)
- CAMERA (shot type, angle, framing)
- STYLE (always include: "Pixar-quality 3D animation")
- FORMAT (16:9 horizontal)

Let the reference images define character appearance and environment style.

---

## 🎬 CINEMA STUDIO RULES (HARDCODED Feb 2, 2026)

**Cinema Studio produces more photorealistic output. Must explicitly request Pixar style.**

### ALWAYS INCLUDE IN PROMPTS:
```
STYLE: Pixar-quality 3D animation, NOT photorealistic
```

### FOR FOOD/OBJECTS:
```
STYLE: Pixar-quality 3D animated style. Stylized cartoon. NOT photorealistic. Same art style as the animated character.
```

### CAMERA SETTINGS IN CINEMA STUDIO:
- Camera: Arri Alexa 35
- Lens: ARRI Signature Prime
- Wide shots: 24mm
- Medium shots: 35mm
- Close-ups: 50-85mm

### WHY THIS MATTERS:
- Cinema Studio defaults to cinematic/realistic
- Without explicit style direction → photorealistic food, environments
- Must match Silly's Pixar/3D animated look
- Jarring to cut between realistic and animated

---

## 📐 FORMAT RULES (HARDCODED Feb 2, 2026)

### MASTER FORMAT: 16:9 HORIZONTAL
- YouTube/TV is where kids actually watch
- Parents put on long-form, not endless scroll
- Cocomelon, Pinkfong, Super Simple all use 16:9

### CENTER-FRAME ALL ACTION:
- Keep Silly in middle 60% of frame
- Allows cropping to 9:16 for Shorts/TikTok without cutting him off

### WORKFLOW:
```
16:9 Horizontal (MASTER) → YouTube, TV, tablets
        ↓
Crop center for 9:16 → Shorts, TikTok, Reels (clips/teasers)
```

### NEVER:
- Generate 9:16 vertical as master
- Put important action at edges of frame

---

## 🎤 LIP SYNC WORKFLOW (HARDCODED Feb 2, 2026)

### FOR SINGING SHOTS:
1. **Generate IMAGE** in Cinema Studio (mouth open in singing pose)
2. **Generate VIDEO** from image (Higgsfield image-to-video)
3. **Process through KLING** for lip sync animation (2-3 close-ups per song)

### FLAG IN STORYBOARD:
Use 🎤 emoji to mark lip sync shots

### WHEN SILLY SINGS:
- He has his GUITAR
- Mouth is OPEN (for lip sync base)
- Flag with 🎤 for Kling processing

---

## 💡 KEY LEARNINGS (HARDCODED)

### From Pick It Up Analysis (Jan 31, 2026):
- 8.8s long hold killed attention
- Pre-climax slow build = boredom for kids
- Visual pacing matters as much as audio tempo
- Kids don't appreciate "tension" or "build-up"
- **Rule: 1.5-2s cuts throughout, no exceptions**

### From Taste It Try It (Feb 2, 2026):
- Always verify audio timestamps before storyboarding
- Multishot = click after generating (not 3-prompt setup)
- 60 shots for 90s song is correct density
- Science/discovery angle works for teaching songs
- Trumpet as weird instrument = distinctive identity

### From Cinema Studio Session (Feb 2, 2026):
- **Cinema Studio = more photorealistic** — must explicitly request Pixar style
- **Food/objects go photorealistic** if not specified — add "NOT photorealistic" to prompts
- **Face-only refs cause drift** — always use FULL-BODY character reference
- **Silly has GUITAR when singing** — use guitar ref as 3rd reference
- **16:9 horizontal master** — kids watch on YouTube/TV, not TikTok
- **Center-frame for crop safety** — allows 9:16 crop for Shorts later
- **Text describes action/pose/expression** — refs handle character/environment consistency

---

*This file is the source of truth for all Silly storyboard production.*
*Read this FIRST before starting any new song storyboard.*
