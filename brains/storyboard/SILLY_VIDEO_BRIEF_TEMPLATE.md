# SILLY VIDEO PRODUCTION BRIEF
## Reverse Engineered from "Taste It Try It #7" (Feb 3, 2026)

---

# 📖 STORY NARRATIVE

## Core Message
Silly discovers that trying new things—even scary ones—leads to joy. The video follows a classic "reluctance → attempt → delight" arc that kids intuitively understand.

## Emotional Journey
```
COMFORT → CURIOSITY → SKEPTICISM → COURAGE → JOY → CELEBRATION → FREEDOM
```

## Story Beat Structure
1. **COMFORT** (0-10s): Silly in his element—beach cafe, smoothie, chill vibes
2. **JOY** (10-20s): Easy wins—spaghetti, familiar foods, instant bliss
3. **CHALLENGE** (20-30s): Exotic fruit appears—skeptical "what is THIS?" energy
4. **COURAGE** (25-35s): Takes the bite anyway—rewarded with bliss
5. **EXPRESSION** (30-50s): Guitar performance—joy needs to be shared
6. **HARDER CHALLENGE** (50-55s): Broccoli—the ultimate kid nemesis
7. **VICTORY** (55-70s): Conquers broccoli, double veggie flex, triumph
8. **TRANSCENDENCE** (70-85s): Extreme close-up bliss—pure ecstasy, particles
9. **FREEDOM** (85-96s): Skates away into sunset—back to the world, changed

## Theme
**"Taste it, try it—you might like it."** Universal kid lesson wrapped in Venice Beach cool.

---

## 🎭 CHARACTER DYNAMICS — HARDCODED FEB 4, 2026

### The Formula (Every Video):

**Hero + Sidekick vs. Villain**

**Structure:**
1. **Main Hero:** Silly (always)
2. **Sidekick:** Changes per video (toothbrush, skateboard, etc.)
3. **Villain:** The problem/obstacle (sugar bugs, mess, scary food)

**Why This Works:**
- Clear good vs. bad (kids understand instantly)
- Teamwork wins (positive message)
- Sidekick makes hero confident
- Villain defeat = satisfying payoff

### Example: "Brush It Up"
- **Hero:** Silly
- **Sidekick:** Toothbrush (animated, eager, loyal helper - think Buzz to Woody)
- **Villain:** Sugar bugs (gross but silly, attacking teeth)

**Battle Sequence:**
1. Villain appears (sugar bugs on teeth)
2. Hero worried/skeptical
3. Sidekick arrives (toothbrush animated, ready to help!)
4. Team up
5. Battle ("Tiny circles, sugar bugs GO!")
6. Victory (sparkly clean teeth)

### Sidekick Personality Template:
- Eager, energetic
- Wants to help
- Brave/heroic stance
- Loyal companion energy
- Makes hero confident

**NEVER make the tool/helper the villain.** It reinforces resistance.

---

## 🥚 EASTER EGGS — HARDCODED FEB 4, 2026

### Rule: 2-3 Hidden Objects Per Video

**Inspired by:** Where's Waldo / I Spy books

**Purpose:**
- Rewatch value (kids look for them)
- Engagement (parents point them out)
- Builds continuity across videos

**Requirements:**
- 2-3 objects hidden in BACKGROUND per video
- Can be consistent across videos OR themed per video
- Not obvious, but findable
- Examples: Hidden star, specific toy, character cameo

**Placement:**
- Background shelves
- Wall decorations
- Through windows
- On furniture

**Production:**
- Generate separately
- Add during image generation or CapCut
- Document in shot notes

**Example Easter Eggs:**
- Tiny skateboard on shelf
- Hidden lightning bolt
- Mini Room of Wonder sign
- Specific colored object (always teal)

**Document:** List in each video's storyboard

---

# 🎬 TECHNICAL SPECS

## Output
- **Duration:** 96 seconds (1:36)
- **Resolution:** 3840x2160 (4K)
- **Aspect Ratio:** 16:9 horizontal
- **Frame Rate:** 24fps (cinematic) or 30fps
- **Format:** MP4 (H.264)

## Tools Used
- **Image Generation:** Higgsfield Cinema (image mode) + Nano Banana Pro 2
- **Video Generation:** Higgsfield Cinema (5-second clips from images)
- **Editing:** CapCut (assembly, transitions, audio sync)
- **Audio:** Original song
- **Beat Analysis:** aubio (beat detection for precise timing)

## Audio Analysis Workflow — HARDCODED FEB 4, 2026

### BEFORE Creating Storyboard:

**1. Analyze beats with aubio:**
```bash
aubiotrack /path/to/song.wav > /tmp/beats.txt
```

**2. Review beat markers:**
- First beat: Song start energy point
- Beat intervals: Where to cut shots
- Total beats: Pacing reference

**3. Map song structure to beats:**
- Chorus beats (high energy)
- Verse beats (story/teaching)
- Bridge beats (transition)
- Climax beats (peak energy)

**4. Use beats for shot timing:**
- Hard cuts on beat markers
- Shot length = beat to beat (typically 0.4-0.5s intervals)
- Climax = rapid cuts (multiple beats/second)

**This ensures:** Perfect sync to music, no guessing on timing

---

## Shot Length Rules — HARDCODED FEB 4, 2026

| Shot Type | Duration |
|-----------|----------|
| **MTV lip sync performance** | **3-4 seconds max** |
| **All other shots (narrative, montage)** | **~2 seconds** |
| **Establishing shot** | 3-4 seconds (orientation) |
| **Money shot climax** | 2-3 seconds |

**Why 2 seconds:**
- Keeps energy high (like Taste It Try It)
- Matches ~5 beat intervals at 130 BPM
- Never let shots drag
- Cut before audience gets bored

**Exception:** Lip sync needs 3-4s to land the lyric clearly

## Clip Chaining (For Longer Sequences)

### 🔗 CHAINING RULE — HARDCODED FEB 4, 2026:

**5 seconds = sweet spot for stability.**

For shots longer than 5 seconds:
1. Generate Clip A (5 sec) — action part 1
2. **Export LAST FRAME of Clip A**
3. Use that as START FRAME for Clip B
4. Generate Clip B (5 sec) — action part 2
5. Stitch in CapCut (hard cut or 2-frame dissolve)

**This maintains consistency across 10-15+ seconds without drift.**

---

## Higgsfield Settings

### ⚠️ SLOW-MO RULE — UPDATED FEB 4, 2026:
> **Higgsfield/Kling outputs slow by default. Speed up in CapCut.**
> **MAX 2 slow-mo moments per video (money shots only).**

| Shot Type | Slow-Mo Toggle | CapCut Speed | Notes |
|-----------|---------------|--------------|-------|
| Action (eating, guitar) | **OFF** | **1.5x-2x** | Punchy energy |
| Reaction (skeptical, looking) | **OFF** | **1.5x-2x** | Snappy cuts |
| Transitions | **OFF** | **1.5x** | Keep momentum |
| Skating/movement | **OFF** | **1.5x-2x** | Speed = freedom |
| **MONEY SHOT 1** (mid-video bliss) | **OFF** | **1x** | First big payoff |
| **MONEY SHOT 2** (climax extreme CU) | **OFF** | **1x** | Peak ecstasy + particles |

### DEFAULT WORKFLOW:
1. Generate ALL clips at normal speed (slow-mo OFF)
2. Import to CapCut
3. **Speed up 1.5x-2x** for action/energy (most clips)
4. **Keep 1x** for 1-2 climax bliss moments only

## Kling 3 Video Generation (Higgsfield)

### START + END FRAME WORKFLOW — HARDCODED FEB 4, 2026:

**For complex motion shots (expression changes, action):**

1. **Generate START FRAME** — Initial state (e.g., skeptical face)
2. **Generate END FRAME** — Final state (e.g., blissful face)
3. **Match these elements between frames:**
   - ✅ Same lighting direction + warmth
   - ✅ Same color palette
   - ✅ Same composition/framing
   - ✅ Same background elements
   - ✅ Same wardrobe
4. **Can change:**
   - Expression
   - Arm/hand position
   - Object state (e.g., pizza → pizza with bite)
   - Slight camera position (for push-in)

5. **In Higgsfield Video Gen:**
   - Upload START FRAME
   - Upload END FRAME
   - Upload CHARACTER REF (Silly canon)
   - Duration: 5 seconds
   - Prompt: Keep minimal — frames do the work

**PROMPT TEMPLATE FOR START/END:**
```
Smooth transition, [brief action description], subtle movement, gentle camera push-in
```

**Example:**
```
Smooth transition, Silly takes small bite, expression shifts from skeptical to blissful, subtle head movement, gentle camera push-in
```

### SIMPLE SHOTS (no end frame needed):
- Static poses with subtle motion
- Single expression holds
- Simple camera moves on still subject

Use START FRAME + CHARACTER REF only. Prompt describes motion.

---

## Camera Setup (Higgsfield Cinema)

### ⚠️ HIGGSFIELD ACTUAL LIMITS — HARDCODED:
- **Focal Length:** 8mm (min) – 50mm (max)
- **Aperture:** f/1.4, f/2.4, f/4, f/11

### 🔴 CRITICAL RULE — REFS > CAMERA SETTINGS:
> **Reference images control LIGHTING and EXPOSURE.**
> **Camera settings control FRAMING and DEPTH OF FIELD.**
>
> - Same camera settings + different refs = totally different look
> - Good refs (in-scene renders) = natural exposure
> - Bad refs (white background statics) = blown out, flat
>
> **ALWAYS use in-scene renders as refs, NOT white background statics.**

### FOCAL LENGTH GUIDE:
| mm | Use For |
|----|---------|
| **8mm** | Epic wide establishing, "here's our world", room feels massive |
| **16mm** | Wide environmental, action with context |
| **24mm** | Standard wide, group shots |
| **35mm** | General purpose, mild wide |
| **50mm** | Close-ups, portraits, emotional beats |

### APERTURE GUIDE:
| f-stop | Depth of Field | Use For |
|--------|----------------|---------|
| **f/1.4** | Very shallow (heavy bokeh) | Bliss close-ups, dreamy |
| **f/2.4** | Moderate bokeh | General medium shots |
| **f/4** | Balanced | Interiors, standard |
| **f/11** | Deep (everything sharp) | Wide establishing, exteriors |

---

**Setup 1 — "Silly Bliss" (close-ups, emotional beats):**
- Camera: Arri Alexa 35 (Digital)
- Lens: ARRI Signature Prime (Spherical)
- Focal Length: **50mm**
- Aperture: **f/1.4** ← dreamiest bokeh, shallow DOF

**Setup 2 — "Silly Standard" (general/medium shots):**
- Camera: Arri Alexa 35 (Digital)
- Lens: ARRI Signature Prime (Spherical)
- Focal Length: **50mm**
- Aperture: **f/2.4** ← balanced

**Setup 3 — "Silly Wide" (general wide, action):**
- Camera: Arri Alexa 35 (Digital)
- Lens: ARRI Signature Prime (Spherical)
- Focal Length: **35mm**
- Aperture: **f/11** ← deep focus, everything sharp

**Setup 4 — "Silly Epic" (establishing, "here's our world"):**
- Camera: Arri Alexa 35 (Digital)
- Lens: ARRI Signature Prime (Spherical)
- Focal Length: **8mm** ← ultra-wide, dramatic
- Aperture: **f/11** ← everything in focus

---

# 🎞️ POST-PRODUCTION (CapCut)

## Transitions
- **80% hard cuts** — on the beat, clean energy
- **Dissolves** — only for bliss moments (skeptical → bliss transition)
- **1-2 whip pans** — for guitar chorus energy
- **AVOID:** Star wipes, slides, anything cheesy

## Captions
- **Font:** Rounded bold (Nunito Bold, Baloo, or CapCut's "Komika")
- **Placement:** Lower third, centered
- **Style:** White text + subtle drop shadow OR black outline
- **When:** Only key lyric phrases, not every word
- **Animation:** Simple pop-on/pop-off, slight bounce on hook ("Taste it, try it")
- **Size:** Big enough for phone viewing

## Color Treatment (Subtle) — LOCKED FEB 4, 2026

### ⚠️ CAPCUT DESKTOP COLOR GRADE (HARDCODED):

| Adjustment | Value |
|------------|-------|
| **Temperature** | **+3** |
| **Saturation** | **+3** |
| **Contrast** | **+5** |

**Optional:**
- Subtle film grain at 5-10% for texture
- Adjust exposure/shadows ONLY if specific clip needs it

**DO NOT:**
- Over-brighten (kills depth)
- Over-warm (goes orange/flat)
- Over-saturate (looks fake)

**DON'T:**
- Heavy vignette
- Crushed blacks
- Teal & orange LUT (too trendy/adult)
- Oversharpening

---

# 🎨 VISUAL STYLE

## Look & Feel
- **Pixar-quality 3D animation** (NOT photorealistic)
- **Golden hour lighting** throughout
- **Saturated, warm color palette** (teal, coral, gold)
- **Shallow depth of field** for emotional shots
- **Cinematic aspect ratio** with subtle letterboxing feel

## Silly's Consistent Appearance
- White seal with fluffy fur
- Jean vest (sleeveless denim) with lightning bolt pin
- Green "SILLY" t-shirt underneath
- Checkered Vans sneakers
- Expressive eyebrows (KEY for emotion)
- Spiky tuft of fur on head

---

# 📍 LOCATIONS (2 Total)

## 1. Venice Beach Exterior
**Use for:** Establishing shots, guitar performance, skating, energy
**Key Elements:**
- Room of Wonder teal beach house (2-story, shingle siding)
- "ROOM OF WONDER" sign on building
- Palm trees, golden sunset sky
- Sand beach visible
- Boardwalk/sidewalk for skating
- Surfboards leaning on porch

## 2. Room of Wonder Interior
**Use for:** Food scenes, emotional beats, close-ups
**Key Elements:**
- Teal shiplap walls
- Orange/coral couch with yellow + blue pillows
- "ROOM OF WONDER" vintage sign (orange frame, colorful letters)
- blink-182 poster
- The Offspring poster
- Skateboards mounted on wall
- Neon palm tree lamp (teal glow)
- Round wooden coffee table with teal top
- Yellow bean bag
- Shelves with colorful ceramics/vases

---

# 📸 SHOT LIST (32 Shots)

## ACT 1: COMFORT + EASY WINS (Shots 1-8, 0:00-0:20)

### Shot 1 — Establishing Wide
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:00-0:03 |
| Location | Beach exterior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **35mm** |
| Aperture | **f/4** |
| Angle | Wide, eye level, slightly low |
| Description | Silly at cafe table with chocolate smoothie, Room of Wonder building visible right of frame |
| Emotion | Content, relaxed |
| Movement | Static or slow push in |

### Shot 2 — Sunglasses Try-On
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:03-0:05 |
| Location | Beach shop / hat rack |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **50mm** |
| Aperture | **f/2.8** |
| Angle | Close-up, eye level, front 3/4 |
| Description | Silly trying on Ray-Ban style sunglasses, hands on temples |
| Emotion | Playful, fun |
| Movement | Static |

### Shot 3 — Guitar Window Shopping
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:05-0:07 |
| Location | Guitar store window |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **50mm** |
| Aperture | **f/2.8** |
| Angle | Medium, side profile |
| Description | Silly looking through window at guitars, hands pressed on glass |
| Emotion | Longing, wanting |
| Movement | Static |

### Shot 4 — Mural Discovery
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:07-0:09 |
| Location | Venice mural alley |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **50mm** |
| Aperture | **f/2.8** |
| Angle | Close-up, front 3/4 |
| Description | Colorful palm tree mural background, Silly with curious expression |
| Emotion | Curious, intrigued |
| Movement | Static |

### Shot 5 — Spaghetti Bliss
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:09-0:12 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **50mm** |
| Aperture | **f/2.8** |
| Angle | Medium, eye level |
| Description | Silly eating spaghetti with fork, noodles in mouth, eyes closed |
| Emotion | Bliss |
| Movement | Static |
| Higgsfield | Slow-mo OFF |

### Shot 6 — Cookie + Ice Cream
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:12-0:14 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **50mm** |
| Aperture | **f/2.8** |
| Angle | Medium, eye level |
| Description | Eating cookie, ice cream cone visible in other hand, eyes closed joy |
| Emotion | Pure joy |
| Movement | Static |
| Higgsfield | Slow-mo OFF |

### Shot 7 — Savoring Close-up
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:14-0:16 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **85mm** |
| Aperture | **f/2** |
| Angle | Close-up face, eye level |
| Description | Eyes closed, peaceful satisfied smile, just finished eating |
| Emotion | Satisfied, content |
| Movement | Static |
| Higgsfield | Slow-mo ON |

### Shot 8 — Transition Look
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:16-0:18 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **50mm** |
| Aperture | **f/2.8** |
| Angle | Close-up, slight low angle |
| Description | Slight skeptical look, one eyebrow starting to raise |
| Emotion | Curious turning skeptical |
| Movement | Static |

---

## ACT 2: FIRST CHALLENGE - EXOTIC FRUIT (Shots 9-14, 0:18-0:35)

### Shot 9 — Skeptical at Fruit (THE POSE)
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:18-0:21 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **50mm** |
| Aperture | **f/2.8** |
| Angle | Medium, slight low angle (makes Silly look confrontational) |
| Description | Hands on hips, eyebrows furrowed, staring DOWN at exotic fruit plate on table |
| Emotion | **SKEPTICAL** — "what is THIS?" |
| Movement | Static |

### Shot 10 — Fruit Insert (Overhead)
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:21-0:23 |
| Location | Table / Room of Wonder |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **35mm** |
| Aperture | **f/4** |
| Angle | **Bird's eye / overhead** |
| Description | Plate of exotic fruit: dragonfruit (cut), kiwano, kiwi, rambutan. Silly's paw reaching into frame |
| Emotion | N/A (object shot) |
| Movement | Static |

### Shot 11 — Reaching for Fruit
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:23-0:25 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **50mm** |
| Aperture | **f/2.8** |
| Angle | Close-up, eye level |
| Description | Hand reaching toward fruit, uncertain expression, slight frown |
| Emotion | Hesitant, nervous |
| Movement | Static |

### Shot 12 — Dragonfruit Bite
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:25-0:28 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **85mm** |
| Aperture | **f/2** |
| Angle | Medium close-up, eye level |
| Description | Biting into pink dragonfruit slice, eyes closing as flavor hits |
| Emotion | Bliss awakening |
| Movement | Static |
| Higgsfield | Slow-mo ON |

### Shot 13 — Face in Fruit Plate
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:28-0:30 |
| Location | Table / Room of Wonder |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **35mm** |
| Aperture | **f/4** |
| Angle | Close-up overhead, looking down at plate |
| Description | Face buried in fruit plate, eating ravenously, messy and happy |
| Emotion | Joyful abandon |
| Movement | Static |

### Shot 14 — Post-Fruit Bliss
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:30-0:32 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **85mm** |
| Aperture | **f/2** |
| Angle | Close-up face, eye level |
| Description | Eyes closed, big satisfied smile, fruit juice on chin |
| Emotion | Satisfied, converted |
| Movement | Static |
| Higgsfield | Slow-mo ON |

---

## ACT 3: EXPRESSION - GUITAR (Shots 15-20, 0:32-0:50)

### Shot 15 — Guitar Reveal (Wide)
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:32-0:35 |
| Location | Beach exterior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **35mm** |
| Aperture | **f/4** |
| Angle | Wide, eye level |
| Description | Silly with sticker-covered white Fender guitar, Room of Wonder building behind, surprised happy expression |
| Emotion | Excited, surprised |
| Movement | Static or slight dolly in |

### Shot 16 — Guitar Playing (Medium)
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:35-0:38 |
| Location | Beach exterior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **50mm** |
| Aperture | **f/2.8** |
| Angle | Medium, front 3/4 |
| Description | Playing guitar, strumming, big toothy smile |
| Emotion | Joy, rock star energy |
| Movement | Static |

### Shot 17 — Guitar Close-up
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:38-0:41 |
| Location | Beach exterior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **85mm** |
| Aperture | **f/2** |
| Angle | Medium close-up, eye level |
| Description | Tighter on face while playing, engaged focused expression |
| Emotion | Focused, in the zone |
| Movement | Static |

### Shot 18 — Full Body Guitar Pose
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:41-0:44 |
| Location | Beach exterior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **35mm** |
| Aperture | **f/4** |
| Angle | Wide, slight low angle (heroic) |
| Description | Full body, Room of Wonder centered behind, guitar hero pose |
| Emotion | Confident, powerful |
| Movement | Static |

### Shot 19 — Guitar Side Angle
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:44-0:47 |
| Location | Beach exterior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **50mm** |
| Aperture | **f/2.8** |
| Angle | Medium, side profile |
| Description | Different angle, still playing, sunset behind |
| Emotion | Energy, momentum |
| Movement | Static |

### Shot 20 — Guitar Face Joy
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:47-0:50 |
| Location | Beach exterior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **85mm** |
| Aperture | **f/2** |
| Angle | Close-up face, eye level |
| Description | Face while playing, eyes squinting with huge smile, pure elation |
| Emotion | Maximum joy |
| Movement | Static |

---

## ACT 4: HARDER CHALLENGE - BROCCOLI (Shots 21-26, 0:50-1:10)

### Shot 21 — Snack Survey
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:50-0:53 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **35mm** |
| Aperture | **f/4** |
| Angle | Over-shoulder, looking at couch |
| Description | Back of Silly's head, looking at spread of snacks on orange couch |
| Emotion | Pondering, surveying |
| Movement | Static |

### Shot 22 — Broccoli Skeptical (THE POSE)
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:53-0:56 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **50mm** |
| Aperture | **f/2.8** |
| Angle | Medium close-up, slight low angle |
| Description | Holding single broccoli floret, one eyebrow raised, skeptical frown |
| Emotion | **SKEPTICAL** — same energy as fruit |
| Movement | Static |

### Shot 23 — Skeptical Tighter
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:56-0:58 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **85mm** |
| Aperture | **f/2** |
| Angle | Close-up face, eye level |
| Description | Even tighter on skeptical face, eyebrow still raised |
| Emotion | Deep doubt |
| Movement | Static |

### Shot 24 — Taking the Bite
| Attribute | Value |
|-----------|-------|
| Timestamp | 0:58-1:01 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **50mm** |
| Aperture | **f/2.8** |
| Angle | Medium, eye level |
| Description | Brings broccoli to mouth, takes bite, expression starts to shift |
| Emotion | Surprise |
| Movement | Static |

### Shot 25 — Broccoli Bliss + SPARKLES
| Attribute | Value |
|-----------|-------|
| Timestamp | 1:01-1:04 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **85mm** |
| Aperture | **f/2** |
| Angle | Medium, eye level |
| Description | Eyes closed, blissful smile, holding broccoli, **SPARKLE PARTICLES around body** |
| Emotion | Transcendent |
| Movement | Static |
| Higgsfield | Slow-mo ON |
| Post FX | Add sparkle particles in CapCut |

### Shot 26 — New Respect
| Attribute | Value |
|-----------|-------|
| Timestamp | 1:04-1:07 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **50mm** |
| Aperture | **f/2.8** |
| Angle | Close-up, eye level |
| Description | Looking at broccoli with soft eyes, new appreciation |
| Emotion | Wonder, respect |
| Movement | Static |

---

## ACT 5: VICTORY + CLIMAX (Shots 27-30, 1:07-1:25)

### Shot 27 — Double Veggie Flex
| Attribute | Value |
|-----------|-------|
| Timestamp | 1:07-1:12 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **35mm** |
| Aperture | **f/4** |
| Angle | Medium, slight low angle (heroic) |
| Description | Both arms raised—veggies in each hand (carrots, peppers, broccoli), looking to side proudly |
| Emotion | **TRIUMPHANT** |
| Movement | Static |

### Shot 28 — Victory Face
| Attribute | Value |
|-----------|-------|
| Timestamp | 1:12-1:17 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **85mm** |
| Aperture | **f/2** |
| Angle | Close-up face, eye level |
| Description | Veggies near face, eyes closed, huge happy smile |
| Emotion | Victory, peace |
| Movement | Static |
| Higgsfield | Slow-mo ON |

### Shot 29 — EXTREME BLISS (MONEY SHOT)
| Attribute | Value |
|-----------|-------|
| Timestamp | 1:17-1:22 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **85mm** |
| Aperture | **f/2** |
| Angle | **EXTREME CLOSE-UP**, slight low angle |
| Description | Head tilted BACK, eyes closed, BIGGEST smile, particles/sparkles floating, Room of Wonder sign soft in background |
| Emotion | **ECSTASY** — peak joy |
| Movement | Static |
| Higgsfield | **Slow-mo ON** |
| Post FX | **Particles in CapCut** |
| Notes | **THIS IS THE HERO SHOT** |

### Shot 30 — Hero Pose
| Attribute | Value |
|-----------|-------|
| Timestamp | 1:22-1:25 |
| Location | Room of Wonder interior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **35mm** |
| Aperture | **f/4** |
| Angle | **Low angle looking UP** |
| Description | Arm raised holding broccoli up high, looking up at it, heroic backlit |
| Emotion | Heroic, triumphant |
| Movement | Static |

---

## ACT 6: FREEDOM - OUTRO (Shots 31-32, 1:25-1:36)

### Shot 31 — Skating Away
| Attribute | Value |
|-----------|-------|
| Timestamp | 1:25-1:32 |
| Location | Beach exterior |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **35mm** |
| Aperture | **f/4** |
| Angle | Wide, **back shot** (from behind) |
| Description | Silly skating away from camera on boardwalk toward Room of Wonder, sunset sky, motion blur |
| Emotion | Freedom |
| Movement | Static or slow follow |

### Shot 32 — Fade to Peace
| Attribute | Value |
|-----------|-------|
| Timestamp | 1:32-1:36 |
| Location | — |
| Camera | Arri Alexa 35 |
| Lens | ARRI Signature Prime |
| Focal Length | **85mm** |
| Aperture | **f/2** |
| Angle | Extreme close-up |
| Description | Silly's peaceful face fading to halftone/dark, final smile |
| Emotion | Peace, contentment |
| Movement | Static |
| Post FX | Halftone filter, fade to black |

---

# 🔑 KEY PATTERNS TO REPLICATE

## 1. The Skeptical → Bliss Cycle
Every video needs **at least 2** of these:
- Show Silly confronting something unfamiliar
- **SKEPTICAL FACE** (eyebrows furrowed, one raised, slight frown)
- Hesitation beat
- Takes the leap
- **BLISS PAYOFF** (eyes closed, big smile)

## 2. Escalating Stakes
- First challenge = easy (familiar food)
- Second challenge = medium (exotic but appealing)
- Third challenge = hard (broccoli = kid nemesis)
- Each victory is bigger than the last

## 3. Guitar/Performance as Chorus
- Use guitar scenes as "chorus" energy boost
- Cut to exterior for performance
- Return to interior for next challenge

## 4. The Money Shot (Extreme Close-up Bliss)
- Save for climax (around 75-80% mark)
- Head tilted back
- Eyes closed
- Biggest possible smile
- Particles/sparkles floating
- **Higgsfield slow-mo ON**

## 5. Bookend with Venice Exterior
- Open with establishing (cafe, smoothie)
- Close with skating away (freedom, sunset)

---

# 📋 REFERENCE IMAGES — CRITICAL

### 🔴 REF IMAGE RULES — HARDCODED (UPDATED FEB 4, 2026):

> **REFS GO AT TOP OF EVERY SHOT BRIEF — EXPLICIT, NOT ASSUMED**
>
> Every shot spec MUST start with:
> - **CHARACTER REF:** [specific image]
> - **SCENE REF:** [specific image for lighting match]
> - **START FRAME:** [if using start/end workflow]
> - **END FRAME:** [if using start/end workflow]

> **USE IN-SCENE RENDERS, NOT WHITE BACKGROUND STATICS**
>
> ❌ **BAD:** Plain white background character refs → blown out, flat lighting
> ✅ **GOOD:** Actual renders from previous videos → natural lighting, consistent look
>
> The refs you attach to Higgsfield control the lighting/exposure MORE than camera settings.

### REQUIRED REFS BY SHOT TYPE:

| Shot Type | Ref To Use | Why |
|-----------|------------|-----|
| **Interior (Room of Wonder)** | Previous interior render with good exposure | Matches room lighting |
| **Exterior (Beach)** | Previous exterior render at golden hour | Matches sunset warmth |
| **Guitar shots** | Previous guitar render | Consistent guitar + pose |
| **Bliss close-up** | Previous close-up with natural fur exposure | White fur not blown out |
| **Skateboard** | Previous skate render | Consistent board + pose |

### REF IMAGE LIBRARY (Save your best renders here):

| Ref Name | Description | Location |
|----------|-------------|----------|
| `ref_silly_interior_01.png` | Room of Wonder, good lighting, medium shot | `/clawd/silly/refs/` |
| `ref_silly_interior_closeup.png` | Interior close-up, natural fur exposure | `/clawd/silly/refs/` |
| `ref_silly_exterior_01.png` | Beach, golden hour, Room of Wonder visible | `/clawd/silly/refs/` |
| `ref_silly_guitar_01.png` | Guitar pose, exterior, good lighting | `/clawd/silly/refs/` |
| `ref_silly_bliss_01.png` | Eyes closed bliss, not overexposed | `/clawd/silly/refs/` |

### LEGACY REFS (Still useful for character consistency):

| Ref Name | Description | Use For |
|----------|-------------|---------|
| `silly_canon.png` | Locked character design | Character consistency only |
| `room_of_wonder_interior.png` | Interior layout reference | Composition reference |
| `room_of_wonder_exterior.png` | Beach house reference | Composition reference |

---

# 📝 PROMPT TEMPLATES

## IMAGE PROMPT FORMAT — HARDCODED FEB 4, 2026

**EVERY image prompt MUST follow this exact structure:**

```
Using the character from image [X], Environment from image [Y],
[SHOT TYPE] shot, [CHARACTER with SPECIFIC ACTION/POSE/STANCE DETAILS],
[specific body positions, hand placement, facial expression],
[environment/location details],
[outfit details],
Pixar-quality 3D animation, NOT photorealistic, 16:9
```

**Example (Shot 1):**
```
Using the character from image 1, Environment from image 2,
ultra Wide establishing shot, Silly the Seal walking forward on Venice Beach boardwalk,
holding blue toothbrush casually in right paw at waist level, left arm swinging naturally,
relaxed walking stance, slight smile, looking forward,
Room of Wonder teal beach house in background with sign, palm trees, morning golden light,
jean vest with lightning bolt pin over green SILLY t-shirt, checkered Vans,
Pixar-quality 3D animation, NOT photorealistic, 16:9
```

**Shot Types:** 
- **Aerial/Drone:** ultra Wide aerial establishing (16mm, f/8-f/11, descending/ascending/orbiting)
- **ultra Wide establishing** (35mm, f/4)
- **Wide** (35mm-50mm, f/2.8-f/4)
- **Medium** (50mm, f/2.8)
- **Close-up** (85mm, f/2)
- **Extreme close-up** (85mm-100mm, f/2)
- **Macro** (100mm+, f/2)

**MUST INCLUDE:**
- "Using the character from image X, Environment from image Y" (FIRST LINE)
- Shot type specification
- Specific pose/action/stance (e.g., "one eyebrow raised, arms crossed", "holding toothbrush high above head with both hands")
- Body position details (which paw, arm placement, facial expression)
- Environment details
- Outfit/props

**DO NOT use generic templates - every shot needs specific action details**

## Exterior Shot Template
```
[SHOT DESCRIPTION], [EMOTION/EXPRESSION],
[SPECIFIC ACTION OR POSE],
Venice Beach boardwalk, golden hour sunset,
Room of Wonder teal beach house visible with "ROOM OF WONDER" sign,
palm trees, sand beach, warm golden lighting,
Silly wearing jean vest over green "SILLY" t-shirt, checkered Vans,
Pixar-quality 3D animation style, cinematic lighting,
NOT photorealistic, 16:9 aspect ratio
```

## Bliss Close-up Template
```
CLOSE-UP of Silly the Seal face, eyes closed, [huge smile / peaceful expression],
[just finished eating / savoring moment], pure bliss,
[Room of Wonder interior / Venice Beach exterior] soft focus background,
Pixar-quality 3D animation, shallow depth of field, warm lighting,
NOT photorealistic, 16:9 aspect ratio
```

## Skeptical Face Template
```
Silly the Seal looking at [OBJECT] with SKEPTICAL expression,
one eyebrow raised, slight frown, head tilted, [hands on hips / arms crossed],
"what is THIS?" energy, confrontational but curious,
[Room of Wonder interior] background,
Pixar-quality 3D animation, NOT photorealistic, 16:9 aspect ratio
```

---

# ⏱️ PRODUCTION CHECKLIST

## Pre-Production
- [ ] Lock song/audio file
- [ ] Map audio beats to shot list (where do cuts land?)
- [ ] Gather all reference images
- [ ] Write all image prompts
- [ ] Create mood board for any new elements

## Production
- [ ] Generate hero images for each shot
- [ ] QC images for consistency (outfit, face, location)
- [ ] Run each image through Higgsfield
- [ ] Set slow-mo ON for bliss shots
- [ ] Export all clips

## Post-Production (CapCut)
- [ ] Import audio track
- [ ] Drop clips on timeline in order
- [ ] Sync to beat/lyrics
- [ ] Add transitions (simple cuts, occasional dissolve)
- [ ] Add particle effects to climax shot
- [ ] Color grade for consistency
- [ ] Export 4K

## Finishing (Polish Pass)
- [ ] **Speed adjust:** All clips → 1.5x-2x (except 1-2 money shots at 1x)
- [ ] **Captions:** Key lyric phrases only (Komika font, lower third, white + drop shadow)
- [ ] **Effects check:**
  - [ ] Sparkle particles on first bliss moment
  - [ ] Floating particles on climax extreme CU
  - [ ] Halftone + fade on outro
- [ ] **Color grade all clips:**
  - [ ] Temperature +3
  - [ ] Saturation +3
  - [ ] Contrast +5
  - [ ] Film grain 5-10% (optional)
- [ ] **Audio:** Volume balance + fade out
- [ ] **Export:** 4K (3840x2160), 30fps, H.264, high quality

---

# 🎯 APPLY TO NEXT VIDEO

## Fill In For New Video:

**Song Title:** ____________________

**Core Message:** ____________________

**Skeptical → Bliss Cycle 1:**
- Challenge: ____________________
- Skeptical beat: ____________________
- Bliss payoff: ____________________

**Skeptical → Bliss Cycle 2:**
- Challenge: ____________________
- Skeptical beat: ____________________
- Bliss payoff: ____________________

**Guitar/Performance Placement:** ____________________

**Money Shot (Extreme Bliss):** ____________________

**Opening Establishing:** ____________________

**Closing Freedom:** ____________________

---

*Template reverse-engineered from Taste It Try It #7 (Feb 3, 2026)*
*96 seconds | 32 shots | 2 locations*
