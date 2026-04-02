# SILLY THE SEAL — COMPLETE PRODUCTION WORKFLOW
**Zero to YouTube: The Exact Step-by-Step Process**

**Created:** January 28, 2026  
**Purpose:** Complete onboarding guide for producing Silly videos  
**Status:** LIVE DOCUMENTATION (Building as we go)

---

## 📋 PREREQUISITES (What You Need)

### Tools & Accounts:
- ✅ Gemini account (for Silly Music Brain Gem)
- ✅ Suno account (music generation)
- ✅ Higgsfield account (image & video generation)
- ✅ CapCut (free video editor)
- ✅ YouTube channel

### Assets:
- ✅ Silly Music Brain Gem (`/clawd/silly/SILLY_MUSIC_BRAIN_GEM.md`)
- ✅ Silly Visual Brain Gem (`/clawd/silly/GEM_SILLY_VISUAL_BRAIN_V2_HARDENED.md`)
- ✅ Silly the Seal Canon (51 reference images at `~/Desktop/Silly the Seal Canon/`)

### Expected Time Per Video:
- **First video:** 3-4 hours (learning the workflow)
- **After 5 videos:** 90-120 minutes
- **At scale (10+ videos):** 60 minutes

### Expected Cost Per Video:
- Suno: $0 (free tier) or ~$0.50
- Higgsfield: ~$5-10 in credits
- **Total:** ~$5-10 per video

---

## 🎯 PRODUCTION PHILOSOPHY

**Key Principles:**
1. **Content first, perfection second** — Ship > polish
2. **Batch where possible** — Generate multiple at once
3. **Reuse assets** — Same environments, props, poses
4. **Test and iterate** — First video teaches you the workflow

**Quality Standards:**
- Character consistency: ✅ Must be perfect (Silly looks like Silly)
- Animation: Good enough (doesn't need to be Pixar-perfect)
- Music: Professional (Suno quality is excellent)
- Editing: Clean and simple (kids content doesn't need fancy transitions)

---

## 📖 THE COMPLETE WORKFLOW

### STEP 0: CHOOSE YOUR TOPIC

**Before generating anything, decide what the video will be about.**

**Question to answer:** What will this video teach or entertain?

**Topic Categories:**

1. **TEACHING Songs** (Tempo: 100-120 BPM)
   - Getting dressed
   - Brushing teeth
   - Tying shoes
   - Washing hands
   - Cleaning up toys

2. **RITUAL Songs** (Tempo: 130-150 BPM)
   - Good morning
   - Bedtime routine
   - Mealtime
   - School drop-off

3. **TRANSITION Songs** (Tempo: varies)
   - "It's hard to stop"
   - "One more minute"
   - "Switching gears"
   - "Almost time"

4. **ANTHEM Songs** (Tempo: 150-180 BPM)
   - "We can do it!"
   - "Mistakes are cool"
   - "Try again"
   - Celebration songs

**How to Choose:**
- Start with RITUAL or ANTHEM (easier to visualize)
- Avoid complex teaching songs for your first video
- Pick something with 3-5 distinct visual scenes
- Choose universal topics (all kids experience them)

**Recommended First Video:** "Good Morning Song" (RITUAL)
- Simple scenes: bedroom → window → stretching → ready to go
- Positive/upbeat
- Universal
- Multiple scenes for workflow testing

---

### STEP 1: GENERATE SONG OPTIONS FROM GEM

**Tool:** Silly Music Brain Gem (Gemini)

**What This Step Does:**
- Uses your Silly Music Brain to generate 3 song topic options
- Pulls from different TIERS (categories) to give variety
- Each option includes title, type, and rationale

**Time:** 2-3 minutes

---

#### 1A. GO TO YOUR SILLY MUSIC BRAIN GEM

**Location:** Gemini → Your Gems → "Silly Music Brain"

---

#### 1B. PASTE THIS EXACT PROMPT:

```
This is our FIRST Silly the Seal song. We're building the catalog from scratch.

Please give me 3 song topic options, pulling from different TIERS to give variety:

- 1 from TRANSITIONS (Tier 1 - highest priority)
- 1 from MORNING RITUALS or DAYTIME (Tier 3-4)
- 1 from EMOTIONAL REGULATION or LIFE SKILLS (Tier 2 or 6)

For each option, tell me:
- Song title
- Which TIER it's from
- Song TYPE (Teaching/Ritual/Anthem)
- Why it's a good first video
- Estimated runtime (target 90 seconds)

Format as a simple numbered list so we can pick one.
```

---

#### 1C. WAIT FOR GEM OUTPUT

**The Gem will return 3 options like:**

```
1. "It's Hard to Stop" (TIER 1: TRANSITIONS, Type: ANTHEM)
   - Validates difficulty of transitions
   - High energy, relatable for all kids
   - 90 seconds
   - Good first video: Universal struggle, emotional connection

2. "Good Morning!" (TIER 3: MORNING RITUALS, Type: RITUAL)
   - Daily motivation for waking up
   - Upbeat, positive energy
   - 90 seconds
   - Good first video: Simple, positive, easy to visualize

3. "We Can Try Again" (TIER 2: EMOTIONAL REGULATION, Type: ANTHEM)
   - Handling mistakes and persistence
   - Encouraging, singalong
   - 90 seconds
   - Good first video: Core Silly message, empowering
```

*(Exact output will vary)*

---

#### 1D. PICK ONE SONG

**Decision Criteria:**
- Which resonates most with you?
- Which is easiest to visualize (3-5 clear scenes)?
- Which matches your gut feeling?

**Mark your choice:** Circle or note which number (1, 2, or 3)

---

### STEP 2: GENERATE COMPLETE SONG (LYRICS + SUNO PROMPT)

**Once you've picked a song topic (e.g., "Good Morning!"), go back to the Gem.**

---

#### 2A. PASTE THIS PROMPT TO GEM:

```
I'm picking option [NUMBER]: [SONG TITLE]

Please generate the complete song with:
1. Full lyrics (verse, chorus, verse, chorus, bridge, outro)
2. Suno-formatted prompt with all tags
3. BPM, key, and style notes

Remember:
- Hook dominance (hook appears in first 15 seconds)
- "WE" not "YOU" perspective
- Target 90 seconds runtime
- Age 3-7 appropriate
```

*(Replace [NUMBER] and [SONG TITLE] with your choice)*

---

#### 2B. GEM WILL OUTPUT:

**Complete song package with:**

1. **Song Structure & Lyrics**
   - Intro
   - Verse 1
   - Chorus (the hook)
   - Verse 2
   - Chorus (repeated)
   - Bridge
   - Outro

2. **Suno Prompt** (copy-paste ready)
   - All style tags
   - BPM
   - Vocal directions
   - Mood markers

3. **Production Notes**
   - Key signature
   - Tempo
   - Vocal style
   - Instrumentation

---

#### 2C. SAVE THE OUTPUT

**Copy entire output and save to:**
`/Users/adriankarvinen/clawd/silly/songs/[SONG_TITLE].md`

**Example:**
`/Users/adriankarvinen/clawd/silly/songs/GOOD_MORNING_SONG.md`

**Why:** You'll reference this for video scripting and future re-generations

---

### STEP 3: GENERATE AUDIO IN SUNO (DETAILED)

**Tool:** Suno.com

**What This Step Does:**
- Takes the Suno-formatted prompt from Gem
- Generates the actual music track in TWO stages
- Stage 1: Generate base song with Suno's AI vocals
- Stage 2: (Optional) Replace vocals with cover/persona
- Produces final MP3 file for video sync

**Time:** 10-15 minutes (including both generation stages + listening)

**Cost:** Free tier (50 credits/day) or Pro ($10/month for 500 credits/month)

---

## 🎵 SUNO HAS TWO MODES:

### **MODE 1: CUSTOM (What You'll Use)**
- You write complete lyrics
- You control style tags and structure
- Best for Silly (you need exact lyrics from Gem)

### **MODE 2: SIMPLE (Don't Use)**
- Suno writes lyrics for you
- Less control
- Not good for Silly's specific needs

---

## 📝 THE COMPLETE SUNO WORKFLOW:

---

### STAGE 1: GENERATE BASE SONG

#### 3A. GO TO SUNO.COM

**Login to your Suno account**

**You should see the main creation interface**

---

#### 3B. CLICK "CUSTOM MODE"

**Look for toggle or button that says "Custom Mode" or "Custom"**

**Turn it ON** (if it's not already)

**Why:** Custom mode lets you paste your complete lyrics + style tags from the Gem

---

#### 3C. YOU'LL SEE TWO TEXT BOXES:

**Box 1: "Style of Music" (or "Genre/Style")**
**Box 2: "Lyrics"**

---

#### 3D. SPLIT YOUR GEM OUTPUT BETWEEN THE TWO BOXES

**The Gem gave you a prompt like this:**

```
[Intro - Gentle acoustic guitar, building energy]

[Verse 1 - Bright, encouraging]
Sun is up, time to go
Stretch those arms, nice and slow
WE can do it, here WE go
Good morning, let's start the show!

[Chorus - Catchy, singalong, major key]
GOOD MORNING! (hey!)
GOOD MORNING! (yeah!)
WE'RE READY FOR THE DAY!
GOOD MORNING! (let's go!)
GOOD MORNING! (woah!)
IT'S TIME TO PLAY!

[Verse 2 - Building momentum]
Open eyes, see the sun
Bright new day, let's have fun
WE got this, everyone
Good morning, day's begun!

[Chorus]
GOOD MORNING! (hey!)
GOOD MORNING! (yeah!)
WE'RE READY FOR THE DAY!
GOOD MORNING! (let's go!)
GOOD MORNING! (woah!)
IT'S TIME TO PLAY!

[Bridge - Building to peak]
Jump! Jump! Let's all jump!
Shake it out, get that pump!
WE are ready, feel the bump
Good morning makes us jump!

[Final Chorus - All energy]
GOOD MORNING! (HEY!)
GOOD MORNING! (YEAH!)
WE'RE READY FOR THE DAY!
GOOD MORNING! (LET'S GO!)
GOOD MORNING! (WOAH!)
IT'S TIME TO PLAY!

[Outro - Fading energy, upbeat close]
Good morning... (yeah!)
Let's go play!

[Style: Pop Punk, Kids Music, Upbeat, Male Vocals, Bright Production]
[Tempo: 140 BPM]
[Key: G Major]
[Tags: energetic, fun, encouraging, morning ritual, Venice Beach vibes]
```

---

**HERE'S HOW TO SPLIT IT:**

---

#### 3E. PASTE INTO BOX 1 (STYLE OF MUSIC):

**Take ONLY the style tags at the bottom:**

```
Pop Punk, Kids Music, Upbeat, Male Vocals, Bright Production, 140 BPM, G Major, energetic, fun, encouraging, morning ritual, Venice Beach vibes
```

**That's it. Just the comma-separated list.**

**Don't include the [Style:] brackets - just the tags**

---

#### 3F. PASTE INTO BOX 2 (LYRICS):

**Take EVERYTHING ELSE (all the lyrics with structure tags):**

```
[Intro - Gentle acoustic guitar, building energy]

[Verse 1 - Bright, encouraging]
Sun is up, time to go
Stretch those arms, nice and slow
WE can do it, here WE go
Good morning, let's start the show!

[Chorus - Catchy, singalong, major key]
GOOD MORNING! (hey!)
GOOD MORNING! (yeah!)
WE'RE READY FOR THE DAY!
GOOD MORNING! (let's go!)
GOOD MORNING! (woah!)
IT'S TIME TO PLAY!

[Verse 2 - Building momentum]
Open eyes, see the sun
Bright new day, let's have fun
WE got this, everyone
Good morning, day's begun!

[Chorus]
GOOD MORNING! (hey!)
GOOD MORNING! (yeah!)
WE'RE READY FOR THE DAY!
GOOD MORNING! (let's go!)
GOOD MORNING! (woah!)
IT'S TIME TO PLAY!

[Bridge - Building to peak]
Jump! Jump! Let's all jump!
Shake it out, get that pump!
WE are ready, feel the bump
Good morning makes us jump!

[Final Chorus - All energy]
GOOD MORNING! (HEY!)
GOOD MORNING! (YEAH!)
WE'RE READY FOR THE DAY!
GOOD MORNING! (LET'S GO!)
GOOD MORNING! (WOAH!)
IT'S TIME TO PLAY!

[Outro - Fading energy, upbeat close]
Good morning... (yeah!)
Let's go play!
```

**Keep all the [Intro], [Verse], [Chorus] tags - Suno uses these**

---

#### 3G. CHECK YOUR INPUTS

**Style Box:** Should have comma-separated style tags
**Lyrics Box:** Should have complete song structure with brackets

**Both boxes filled? Good.**

---

#### 3H. TITLE YOUR SONG (OPTIONAL BUT RECOMMENDED)

**Look for "Song Title" field**

**Type:** "Good Morning Song - Silly the Seal"

**Why:** Helps you organize your Suno library

---

#### 3I. CLICK "CREATE" (OR "GENERATE")

**Big button at the bottom**

**Suno will:**
1. Show you a loading animation
2. Generate 2 versions simultaneously
3. Take about 2-3 minutes

**Wait for both to finish**

---

#### 3J. LISTEN TO BOTH VERSIONS

**Suno always generates 2 versions (Version 1 and Version 2)**

**Click play on each one**

**Listen for:**
- Which has better vocal delivery?
- Which has more energy?
- Which hook sounds catchier?
- Which feels more "pop punk"?
- Which has clearer lyrics?

**Pick the better one**

---

#### 3K. DECISION POINT: KEEP OR REGENERATE?

**If one version is GOOD:**
- ✅ Move to Stage 2 (optional cover vocals)
- ✅ Or skip to 3P (download and save)

**If BOTH versions are mediocre:**
- Click "Create" again with same prompt
- Get 2 more versions
- Repeat until you get one you like

**Typical:** You'll get a good version in first 1-2 tries

---

### STAGE 2: APPLY SILLY PERSONA (VOICE MODEL)

**⚠️ YOU HAVE TWO OPTIONS:**

---

#### **OPTION A: USE SUNO'S DEFAULT VOICE (Skip Persona)**

**When to use:**
- Quick test videos
- Trying out new songs
- Don't need exact Silly voice consistency

**Process:**
- Skip to Stage 3 (Download)
- Uses whatever voice Suno generated
- Faster workflow

---

#### **OPTION B: USE YOUR SILLY PERSONA (Recommended)**

**When to use:**
- Final production videos
- Need consistent Silly voice across all videos
- Building the official catalog

**You already have a Silly persona/voice model in Suno**

---

#### 3L. FIND YOUR SILLY PERSONA IN SUNO

**Look for:**
- "My Personas" or "Voice Models" section in Suno
- Should see your saved Silly voice

**If you can't find it:** It might be under "Covers" or "Voice Library"

---

#### 3M. CLICK "COVER" OR "APPLY PERSONA"

**On the song version you picked (from Stage 1)**

**Click the button that says:**
- "Cover" or
- "Apply Voice" or  
- "Use Persona"

*(Exact wording depends on Suno's current UI)*

---

#### 3N. SELECT YOUR SILLY PERSONA

**From the list of available personas/voices:**

**Select:** Your existing Silly voice model

**If you have multiple Silly versions, pick the one that sounds most:**
- Youthful
- Energetic
- Pop-punk appropriate

---

#### 3O. CLICK "GENERATE COVER"

**Suno will:**
1. Take the instrumental from your generated song
2. Replace the vocals with your Silly persona voice
3. Generate new version with Silly's voice
4. Takes 2-3 minutes

**Wait for it to finish**

---

#### 3O-2. LISTEN TO THE PERSONA VERSION

**Play the new cover version**

**Check:**
- Does it sound like Silly?
- Is the vocal energy right?
- Does it match the vibe?

**If YES:** This is your final version
**If NO:** Try with different Suno voice or regenerate base song

---

### STAGE 3: DOWNLOAD AND SAVE

#### 3P. CLICK THE "..." MENU ON YOUR CHOSEN VERSION

**Three dots next to the version you picked**

---

#### 3Q. CLICK "DOWNLOAD"

**Downloads as MP3 file**

**Default name:** Something like `suno_good_morning_xyz123.mp3`

---

#### 3R. RENAME AND SAVE THE FILE

**Rename to:** `[song_title].mp3`

**Example:** `good_morning_song.mp3`

**Save to:**
`/Users/adriankarvinen/clawd/silly/audio/good_morning_song.mp3`

---

#### 3S. VERIFY THE FILE

**Open the MP3 and listen all the way through**

**Check:**
- ✅ Full song (intro to outro)?
- ✅ No cuts or glitches?
- ✅ Audio quality good?
- ✅ Roughly 90 seconds runtime?

**If anything is wrong:** Regenerate in Suno and download new version

---

### ✅ YOU NOW HAVE "THE SONG"

**File:** `/Users/adriankarvinen/clawd/silly/audio/good_morning_song.mp3`

**Status:** Ready for audio analysis

**Next Step:** Analyze audio with Gemini (STEP 3.5)

---

---

### STEP 3.5: ANALYZE AUDIO WITH GEMINI (AUDIO ANALYSIS BRAIN)

**Tool:** Silly Audio Analysis Brain Gem (Gemini)

**What This Step Does:**
- Listens to your actual Suno MP3 file
- Detects real BPM (not just what Suno prompt said)
- Maps energy levels throughout the song (1-10 scale)
- Identifies exact section timestamps (intro, verse, chorus, bridge, outro)
- Finds beat drop moments and optimal cut points
- Provides shot count and duration recommendations per section

**Why This Matters:**
- Storyboard timing becomes PRECISE (not guessing)
- Cuts land on actual beats (not arbitrary timers)
- Energy-informed shot selection (high energy = performance, low = teaching)
- The editor knows exactly where to cut in CapCut

**Time:** 3-5 minutes

**Location of Gem:** `/Users/adriankarvinen/clawd/silly/GEM_SILLY_AUDIO_ANALYSIS_BRAIN_v1.md`

---

#### 3.5A. GO TO GEMINI AND OPEN SILLY AUDIO ANALYSIS BRAIN GEM

**Or create new Gem if you haven't yet:**
1. Go to Gemini → Gems
2. Click "Create New Gem"
3. Copy entire contents of `GEM_SILLY_AUDIO_ANALYSIS_BRAIN_v1.md`
4. Paste into Gem instructions
5. Name it: "Silly Audio Analysis Brain"
6. Save

---

#### 3.5B. UPLOAD YOUR SUNO MP3 TO THE GEM

**In Gemini:**
1. Click the attachment/upload button
2. Select your MP3 file (`good_morning_song.mp3`)
3. Type: "Analyze this song"
4. Send

**Gemini will listen to the entire track and analyze it.**

---

#### 3.5C. GEM WILL OUTPUT COMPLETE AUDIO ANALYSIS

**The output includes:**

```
═══════════════════════════════════════════════════════════════
🎵 AUDIO ANALYSIS: GOOD MORNING SONG
═══════════════════════════════════════════════════════════════

📊 SONG OVERVIEW
BPM: 142 (verified from audio)
Key: G Major
Total Runtime: 1:38
Overall Energy: High (pop-punk anthem vibe)

📍 SECTION-BY-SECTION BREAKDOWN

INTRO (0:00 - 0:06)
Energy Level: 4/10
CUT RECOMMENDATION: 2 shots at 3 sec each

VERSE 1 (0:07 - 0:22)
Energy Level: 5/10
PHRASE ENDINGS AT: 0:10, 0:14, 0:18, 0:22
CUT RECOMMENDATION: 4 shots at 4 sec each

CHORUS 1 (0:23 - 0:38)
Energy Level: 9/10 ⚡ PEAK
SNARE/CUT POINTS AT: 0:23, 0:26, 0:29, 0:32, 0:35
CUT RECOMMENDATION: 5 shots at 3 sec each

[...continues for all sections...]

🎬 VIDEO EDITING SUMMARY
ENERGY MAP:
0:00 ████░░░░░░ [4] Intro
0:07 █████░░░░░ [5] Verse 1
0:23 █████████░ [9] Chorus 1 ⚡
...

TOTAL RECOMMENDED SHOTS: 30 shots
```

---

#### 3.5D. SAVE THE AUDIO ANALYSIS

**Copy entire output and save to:**
`/Users/adriankarvinen/clawd/silly/songs/[SONG_TITLE]_AUDIO_ANALYSIS.md`

**Example:**
`/Users/adriankarvinen/clawd/silly/songs/GOOD_MORNING_SONG_AUDIO_ANALYSIS.md`

**Why:** You'll paste this INTO the Storyboard Brain in Step 4

---

### ✅ YOU NOW HAVE:

1. **Song lyrics + Suno prompt** (from Step 2)
2. **MP3 audio file** (from Step 3)
3. **Audio analysis with timestamps** (from Step 3.5) ← NEW

**All three go into Step 4 (Storyboard Brain)**

---

## 🎯 SUNO TIPS & TRICKS:

**Tip 1:** First generation is usually good - don't overthink it

**Tip 2:** If vocals are too mature, add "youthful vocals" to style tags

**Tip 3:** If tempo feels wrong, regenerate with different BPM in style box

**Tip 4:** Save good versions to your Suno library for future reference

**Tip 5:** Suno has a "Remix" feature - you can tweak a good version instead of starting over

---

## ⏸️ PAUSE POINT:

**Before moving to STEP 4, make sure you have:**
- ✅ MP3 file downloaded
- ✅ File saved to `/clawd/silly/audio/`
- ✅ You've listened to the full song and like it
- ✅ Ready to create video for this song

**If yes → Move to STEP 4: Extract Video Script**

---

---

### STEP 4: GENERATE VIDEO STORYBOARD WITH SILLY STORYBOARD BRAIN GEM

**Tool:** Silly Storyboard Brain Gem (Gemini)

**What This Step Does:**
- Takes your song lyrics
- Converts into complete shot-by-shot storyboard
- Includes camera angles, expressions, locations
- Generates Higgsfield Shots prompts automatically
- Follows Silly's world-building rules (Room of Wonder/Venice Beach only)
- Balances MTV pop-punk aesthetic with kids teaching needs

**Time:** 3-5 minutes

**Location of Gem:** `/Users/adriankarvinen/clawd/silly/GEM_SILLY_STORYBOARD_BRAIN_v1.md`

---

#### 4A. GO TO GEMINI AND OPEN SILLY STORYBOARD BRAIN GEM

**Or create new Gem if you haven't yet:**
1. Go to Gemini → Gems
2. Click "Create New Gem"
3. Copy entire contents of `GEM_SILLY_STORYBOARD_BRAIN_v1.md`
4. Paste into Gem instructions
5. Name it: "Silly Storyboard Brain"
6. Save

---

#### 4B. PASTE YOUR SONG LYRICS + AUDIO ANALYSIS INTO THE GEM

**Format (UPDATED - includes Audio Analysis from Step 3.5):**

```
Song Title: [Your Song Title]
Song Type: [Teaching/Ritual/Anthem]

AUDIO ANALYSIS:
═══════════════════════════════════════════════════════════════
[PASTE ENTIRE AUDIO ANALYSIS OUTPUT FROM STEP 3.5]
═══════════════════════════════════════════════════════════════

LYRICS:
[PASTE COMPLETE LYRICS WITH VERSE/CHORUS STRUCTURE]
```

**Example:**

```
Song Title: Good Morning Song
Song Type: Ritual

AUDIO ANALYSIS:
═══════════════════════════════════════════════════════════════
🎵 AUDIO ANALYSIS: GOOD MORNING SONG

📊 SONG OVERVIEW
BPM: 142 (verified from audio)
Key: G Major
Total Runtime: 1:38

📍 SECTION-BY-SECTION BREAKDOWN

INTRO (0:00 - 0:06)
Energy Level: 4/10
CUT RECOMMENDATION: 2 shots at 3 sec each

VERSE 1 (0:07 - 0:22)
Energy Level: 5/10
PHRASE ENDINGS AT: 0:10, 0:14, 0:18, 0:22
CUT RECOMMENDATION: 4 shots at 4 sec each

CHORUS 1 (0:23 - 0:38)
Energy Level: 9/10 ⚡ PEAK
SNARE/CUT POINTS AT: 0:23, 0:26, 0:29, 0:32, 0:35
CUT RECOMMENDATION: 5 shots at 3 sec each

[...full audio analysis...]
═══════════════════════════════════════════════════════════════

LYRICS:
[Intro - Gentle acoustic guitar, building energy]

[Verse 1 - Bright, encouraging]
Sun is up, time to go
Stretch those arms, nice and slow
WE can do it, here WE go
Good morning, let's start the show!

[Chorus - Catchy, singalong, major key]
GOOD MORNING! (hey!)
GOOD MORNING! (yeah!)
WE'RE READY FOR THE DAY!

[Continue with rest of lyrics...]
```

**⚠️ IMPORTANT:** The Storyboard Gem now uses the Audio Analysis timestamps to determine EXACT shot timing and cut points. Without the audio analysis, it will guess. With it, timing is precise.

---

#### 4C. GEM WILL OUTPUT COMPLETE STORYBOARD

**The output includes for EVERY shot:**

```
SHOT 1 (0:00-0:08) - [8 sec]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
ACTION: Silly waking up and stretching arms overhead
LOCATION: Room of Wonder, orange couch with rainbow rug visible
CAMERA: Wide shot, slightly high angle
EXPRESSION: Sleepy transitioning to excited
SYNC: NO
LYRICS: "Sun is up, time to go / Stretch those arms, nice and slow"
REFERENCE IMAGE: 01_silly_soul_id.png
NOTES: Establishing shot, sets the morning vibe

HIGGSFIELD SHOTS PROMPT:
Silly the seal waking up and stretching arms overhead on orange 
couch in the Room of Wonder with teal walls and rainbow striped 
rug, wide shot from slightly high angle, warm morning sunlight 
through window, Pixar 3D style, vibrant colors, cozy atmosphere
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

**Plus:**
- Shot breakdown summary (performance vs teaching %)
- Production notes
- Reference to which shots repeat (for chorus reinforcement)

---

#### 4D. COPY THE ENTIRE OUTPUT

**Save to:**
`/Users/adriankarvinen/clawd/silly/storyboards/[SONG_TITLE]_STORYBOARD.md`

**Example:**
`/Users/adriankarvinen/clawd/silly/storyboards/GOOD_MORNING_SONG_STORYBOARD.md`

---

#### 4E. YOU NOW HAVE YOUR COMPLETE PRODUCTION BLUEPRINT

**What you can do with this:**

✅ **See every shot** (action, location, camera, expression)
✅ **Know which reference images to use** (from Silly Canon)
✅ **Have ready-to-paste Higgsfield prompts** (no thinking required)
✅ **Understand the flow** (performance vs teaching balance)
✅ **Know which shots need lip sync** (minimal)
✅ **See shot repetition** (chorus reinforcement for kids)

---

#### 4F. REVIEW THE STORYBOARD (OPTIONAL)

**Quick sanity checks:**
- Does flow make sense?
- Are locations correct (only Room of Wonder/Venice Beach)?
- Does it match the song's energy?
- Teaching vs performance balance feel right?

**If something feels off:**
- Go back to Gem and say: "Adjust shot 5 to be more energetic" or "Add more teaching moments"
- Gem will regenerate

**Most of the time:** First output is perfect, use it as-is

---

### STEP 5: GENERATE STORYBOARD IMAGES WITH HIGGSFIELD "SHOTS"

**Tool:** Higgsfield → Shots feature

**What This Step Does:**
- Takes ONE Silly reference image
- Generates 9 different camera angles/perspectives of that SAME pose
- NO text prompts - just different angles
- Gives you multiple camera angle options

**Time:** 20-30 minutes (for all shots)

**Cost:** ~1 credit per 9-shot grid

---

#### 5A. HOW HIGGSFIELD SHOTS ACTUALLY WORKS:

**Important:** Shots does NOT take text prompts.

**What it does:**
1. You upload a reference image (e.g., Silly putting toys in box)
2. Click "Shots"
3. It generates 9 different camera angles of that SAME action
4. That's it

**Example:**
- Upload: `silly_with_toys.png` (Silly holding a toy box)
- Get back: 9 angles (front, side, low angle, high angle, close-up, wide, etc.)
- All show the SAME action, just different perspectives

---

#### 5B. THIS MEANS: REFERENCE IMAGE SELECTION IS CRITICAL

**Your storyboard says: "Shot 3: Silly putting toys in box"**

**You need to find/have a reference image that shows Silly with toys/box**

**Two options:**

**OPTION A: Use existing Canon reference that's CLOSE ENOUGH**
- If you have `15_silly_holding_object.png`, use that
- The 9 angles will give you variety even if pose isn't perfect

**OPTION B: Generate NEW reference first (if needed)**
- Use Higgsfield Image-to-Video or other tool to create the exact pose
- Save as new reference
- Then run Shots on it

---

#### 5C. WORKFLOW FOR EACH SHOT:

**For each shot in your storyboard:**

1. **Look at storyboard:** "Shot 3: Silly putting toys in box, Room of Wonder"
2. **Pick closest reference image** from Canon:
   - Exact match? Use it
   - Close enough? Use it
   - No match? Generate new reference OR use neutral pose
3. **Upload to Higgsfield Shots**
4. **Click "Shots"** (no prompt needed)
5. **Get 9 camera angles back** (~60 seconds)
6. **Pick best angle** that matches your storyboard camera direction
7. **Download that frame**
8. **Move to next shot**

---

#### 5D. GO TO HIGGSFIELD → APPS → "SHOTS"

**Click on "Shots" tool**

---

#### 5E. FOR EACH SHOT IN YOUR STORYBOARD:

**Example: Shot 1 needs "Silly waking up and stretching"**

---

#### 5F. BROWSE YOUR SILLY CANON FOR CLOSEST MATCH

**Open:** `~/Desktop/Silly the Seal Canon/`

**Find closest reference:**
- Stretching pose? Use that
- Neutral standing? Will work
- Similar energy? Good enough

**If no match:** Use `01_silly_soul_id.png` (versatile neutral)

---

#### 5G. UPLOAD REFERENCE IMAGE TO SHOTS

**Drag and drop your chosen reference**

**No text prompt - Shots doesn't use them**

---

#### 5H. CLICK "GENERATE" OR "SHOTS"

**Higgsfield generates 9 camera angles** (takes ~60 seconds)

You'll get:
- Front view
- Side views (left/right)
- 3/4 angles
- Low angle (looking up)
- High angle (looking down)
- Close-up
- Wide shot
- Over-shoulder
- etc.

**Same Silly, same pose, 9 different perspectives**

---

#### 5I. PICK THE BEST ANGLE FOR YOUR SHOT

**Your storyboard said:** "Wide shot, low angle"

**Look at the 9 frames, pick the one that's:**
- Widest composition
- Lowest camera angle
- Best matches your vision

**Download that specific frame**

---

#### 5J. SAVE THE FRAME

**Save to:**
`/Users/adriankarvinen/clawd/silly/storyboards/[SONG_TITLE]/shot_01.png`

**Name clearly:** `shot_01_waking_up.png`

---

#### 5K. REPEAT FOR EACH SHOT (12-16 times)

**For a 12-shot storyboard:**
- 12 Higgsfield Shots runs
- Pick 1 frame from each 9-grid
- Download 12 final frames

**By the end you have:**
- 12-16 keyframe images
- Perfect character consistency
- Ready for animation

---

#### 5L. OPTIMIZATION TIP: REUSE REFERENCES

**If multiple shots use similar poses:**

**Example:**
- Shot 3: Silly jumping (use `13_silly_jumping.png`)
- Shot 7: Silly jumping again in chorus (use SAME reference)
- Pick different angle from the 9-grid for variety

**You can run Shots on the same reference multiple times and pick different angles**

---

#### REALITY CHECK:

**Shots is simple:**
- Upload image → Get 9 angles → Pick one
- No prompting
- No scene descriptions
- Just different camera perspectives

**This means your Silly Canon needs to cover most actions you'll need.**

**If you're missing key poses:** Generate them first with another tool, add to Canon, then use Shots

---

---

### STEP 6: ANIMATE KEYFRAMES (IMAGE-TO-VIDEO)

**Tool:** Higgsfield → Image-to-Video

**What This Step Does:**
- Takes your static keyframe images from Shots
- Adds motion and animation
- Creates 4-5 second video clips for each shot
- These become the building blocks of your video

**Time:** 40-60 minutes (for 12-16 shots)

**Cost:** ~$8-12 (varies by Higgsfield pricing)

---

## 🎬 COMPLETE IMAGE-TO-VIDEO WORKFLOW:

---

#### 6A. ORGANIZE YOUR KEYFRAME IMAGES

**Before starting, make sure you have:**
- All 12-16 keyframe images saved from Step 5
- Files named clearly (e.g., `shot_01_waking_up.png`, `shot_02_stretching.png`)
- Saved in `/Users/adriankarvinen/clawd/silly/storyboards/[SONG_TITLE]/`

**Open that folder so you can easily access images**

---

#### 6B. GO TO HIGGSFIELD

**Open:** higgsfield.ai

**Navigate to:** Apps → Image-to-Video (or "Animate" depending on UI)

---

#### 6C. FOR EACH SHOT, ANIMATE ONE BY ONE

**You'll repeat this process 12-16 times:**

---

### SHOT 1 EXAMPLE WALKTHROUGH:

**Your storyboard says:**
```
SHOT 1 (0:00-0:08)
ACTION: Silly waking up and stretching arms overhead
```

---

#### 6C-1. UPLOAD SHOT 1 IMAGE

**Click "Upload Image" or drag-and-drop**

**Select:** `shot_01_waking_up.png`

**Image appears** in Higgsfield preview

---

#### 6C-2. WRITE MOTION PROMPT

**Higgsfield needs to know HOW to animate the image**

**Your storyboard ACTION field tells you what motion to describe:**

**From storyboard:** "Silly waking up and stretching arms overhead"

**Motion prompt for Higgsfield:**
```
Silly stretching arms upward, gentle waking motion, slight head tilt, breathing
```

**Prompt formula:**
```
[Character] [main action], [secondary motion], [subtle detail]
```

**Keep it simple and specific:**
- Focus on ONE main action
- Add subtle secondary motion (breathing, head turn)
- Avoid complex multi-step actions

---

#### 6C-3. SET ANIMATION SETTINGS

**Duration:** 5 seconds (recommended)
- Long enough to feel natural
- Easy to trim in CapCut later
- Short = cheaper/faster generation

**Motion strength:** Medium (if available)
- Low = subtle, minimal motion
- Medium = natural movement (BEST for most shots)
- High = dramatic, big movements

**Camera movement:** Static or subtle push-in
- Static = no camera move (just character animates)
- Push-in = slow zoom toward character
- Pull-out = slow zoom away

**For Shot 1 (waking up):**
- Duration: 5 sec
- Motion: Medium
- Camera: Static

---

#### 6C-4. GENERATE

**Click "Generate" or "Create"**

**Wait:** 60-90 seconds

**Higgsfield will:**
1. Analyze your image
2. Interpret motion prompt
3. Generate 5-second animation
4. Show preview

---

#### 6C-5. PREVIEW THE RESULT

**Play the generated clip**

**Check:**
- ✅ Does motion look natural?
- ✅ Does it match the action you wanted?
- ✅ Is Silly's character consistent (no weird morphing)?
- ✅ Is motion smooth (not jittery)?

**If YES:** Download it
**If NO:** Regenerate with adjusted prompt

**Common issues & fixes:**
- **Too much motion:** Lower motion strength or simplify prompt
- **Wrong action:** Clarify prompt ("arms raising UP" vs just "arms moving")
- **Character morphs:** Try simpler prompt with less motion
- **Jittery:** Regenerate (sometimes random)

---

#### 6C-6. DOWNLOAD THE CLIP

**Click "Download" or "Export"**

**Format:** MP4 (1080p or higher)

**Save to:** `/Users/adriankarvinen/clawd/silly/video_clips/[SONG_TITLE]/`

**Name it:** `clip_01_waking_up.mp4`

**Naming convention:**
```
clip_[NUMBER]_[ACTION_DESCRIPTION].mp4
```

**Keep names matching your storyboard shot numbers**

---

### REPEAT FOR ALL SHOTS (2-16):

**Now do the same process for each remaining shot:**

---

#### SHOT 2 EXAMPLE:

**Storyboard:** "Silly jumping with arms up celebrating"

**Motion prompt:**
```
Silly jumping upward, arms raising to celebration pose, energetic bouncing motion
```

**Settings:**
- Duration: 5 sec
- Motion: Medium-High
- Camera: Static

**Generate → Preview → Download → Save as `clip_02_jumping.mp4`**

---

#### SHOT 3 EXAMPLE:

**Storyboard:** "Silly playing guitar, strumming"

**Motion prompt:**
```
Silly strumming guitar, arms moving rhythmically, slight body sway, head bobbing
```

**Settings:**
- Duration: 5 sec
- Motion: Medium
- Camera: Static or slight push-in

**Generate → Preview → Download → Save as `clip_03_guitar.mp4`**

---

#### SHOT 4 EXAMPLE:

**Storyboard:** "Silly skateboarding, tracking shot"

**Motion prompt:**
```
Silly skateboarding forward, wheels rolling, slight balance motion, camera tracking
```

**Settings:**
- Duration: 5 sec
- Motion: Medium
- Camera: Tracking/Pan (if available)

**Generate → Preview → Download → Save as `clip_04_skateboard.mp4`**

---

## 💡 MOTION PROMPT TIPS:

### **For Performance Shots (singing, guitar, celebrating):**
```
[Character] [instrument/pose], [rhythmic motion], [subtle sway/breathing]
```

**Examples:**
- "Silly singing to camera, mouth moving slightly, head bobbing gently"
- "Silly with arms up triumphant, slight bounce, breathing motion"

### **For Action Shots (jumping, running, moving):**
```
[Character] [main action], [direction], [energy level]
```

**Examples:**
- "Silly jumping upward, energetic bouncing, landing softly"
- "Silly running forward, legs pumping, excited motion"

### **For Teaching Shots (demonstrating actions):**
```
[Character] [teaching action], [step motion], gentle demonstration
```

**Examples:**
- "Silly putting on shirt, arms pulling down, gentle dressing motion"
- "Silly brushing teeth, arm moving up and down, exaggerated motion"

### **For Static/Atmospheric Shots:**
```
[Character] [pose], subtle breathing, minimal motion, camera [movement]
```

**Examples:**
- "Silly standing looking out window, slight breathing, camera slowly pushing in"
- "Silly sitting on couch, gentle breathing, serene stillness"

---

## ⚙️ WORKFLOW OPTIMIZATION:

### **Batch Processing:**

Instead of Download → Next shot → Upload → Wait...

**Do this:**
1. **Upload Shot 1** → Set prompt → Click Generate
2. **While Shot 1 generates (60 sec wait):**
   - Open new Higgsfield tab/window
   - Upload Shot 2 → Set prompt → Click Generate
3. **By the time Shot 2 generates, Shot 1 is done**
4. Download Shot 1, start Shot 3
5. Download Shot 2, start Shot 4

**Parallel processing = saves 20-30 minutes**

**Limitation:** Depends on Higgsfield credits/concurrent generation limits

---

## 📊 BY THE END OF STEP 6:

**You'll have:**
- 12-16 animated video clips (each 4-5 seconds)
- All saved in `/clawd/silly/video_clips/[SONG_TITLE]/`
- Named clearly (clip_01, clip_02, etc.)
- Ready to import to CapCut

**File structure:**
```
/clawd/silly/video_clips/good_morning_song/
├── clip_01_waking_up.mp4
├── clip_02_stretching.mp4
├── clip_03_jumping.mp4
├── clip_04_window_view.mp4
├── clip_05_skateboard.mp4
...
├── clip_12_waving.mp4
```

---

## ⏭️ NEXT: Some clips need LIP SYNC (Step 7)

**Your storyboard told you which shots have SYNC: YES**

**For those 2-3 shots, you'll:**
1. Record yourself lip syncing the part
2. Use Kling to map your mouth to Silly
3. Replace those clips with lip-synced versions

**Most clips (9-13) are done - no lip sync needed**

---

### STEP 7: ADD LIP SYNC (FOR 2-3 CLOSE-UP SINGING SHOTS)

**Tool:** Kling AI → Motion Control (Lip Sync mode)

**What This Step Does:**
- Maps your mouth movements onto Silly's face
- Makes Silly's mouth move perfectly in sync with vocals
- Only needed for close-up singing shots (2-3 per video)

**Time:** 20-30 minutes (for 2-3 shots)

**Cost:** ~$2-3 (varies by Kling pricing)

**When to skip:** If no shots have SYNC: YES in storyboard (rare - usually at least chorus needs it)

---

## 🎤 COMPLETE LIP SYNC WORKFLOW:

---

#### 7A. IDENTIFY WHICH SHOTS NEED LIP SYNC

**Check your storyboard - look for SYNC: YES**

**Example:**
```
SHOT 3 (0:17-0:25) - Silly singing to camera
SYNC: YES ← This one needs lip sync
LYRICS: "GOOD MORNING! (hey!) GOOD MORNING! (yeah!)"

SHOT 7 (0:57-1:05) - Silly singing close-up
SYNC: YES ← This one too

SHOT 10 (1:25-1:32) - Silly final chorus
SYNC: YES ← And this one
```

**Typically: 2-3 shots per video**

**For each SYNC: YES shot, you'll do Steps 7B-7H**

---

### LIP SYNC SHOT 1 WALKTHROUGH (SHOT 3 EXAMPLE):

---

#### 7B. EXTRACT THE EXACT AUDIO SEGMENT

**You need JUST the audio for this specific shot**

**Your storyboard says:**
- SHOT 3: 0:17-0:25 (8 seconds)
- Lyrics: "GOOD MORNING! (hey!) GOOD MORNING! (yeah!)"

**Extract that audio segment:**

**Method 1: Use CapCut**
1. Import your full Suno MP3 to CapCut
2. Place on timeline
3. Use razor tool to cut at 0:17 and 0:25
4. Select just that segment
5. Right-click → Export → Audio only
6. Save as `shot_03_audio.mp3`

**Method 2: Use Audacity (free audio editor)**
1. Open full Suno MP3 in Audacity
2. Select 0:17 to 0:25 region
3. File → Export → Export Selected Audio
4. Save as `shot_03_audio.mp3`

**Method 3: Online audio trimmer**
1. Go to: mp3cut.net or audiotrimmer.com
2. Upload Suno MP3
3. Trim to 0:17-0:25
4. Download as `shot_03_audio.mp3`

**Save to:** `/Users/adriankarvinen/clawd/silly/audio_segments/`

---

#### 7C. RECORD YOURSELF LIP SYNCING

**This is your "driver video" - your mouth movements will be mapped onto Silly**

**Equipment needed:**
- Your phone (iPhone/Android)
- Good lighting (face well-lit)
- Quiet room

**Setup:**
1. **Play the audio segment** you extracted (`shot_03_audio.mp3`)
2. **Open phone camera** in selfie mode
3. **Frame your face** - mouth should be clearly visible, centered
4. **Practice once** - lip sync to the audio to get comfortable
5. **Record video** - lip sync as you play the audio

**Recording tips:**
- **Exaggerate mouth movements** slightly (Kling works better with clear motions)
- **Face camera directly** (not turned)
- **Keep face still** (don't bob head too much - just mouth moves)
- **Match the energy** (if song is energetic, animate your face)
- **Don't worry about perfect sync** - Kling will clean it up

**Record 2-3 takes**, pick the best one

**Save as:** `shot_03_driver.mov` or `.mp4`

**Save to:** `/Users/adriankarvinen/clawd/silly/driver_videos/`

---

#### 7D. GO TO KLING AI

**Open:** klingai.com

**Log in** to your account

**Navigate to:** Tools → Motion Control (or "Lip Sync" depending on UI)

---

#### 7E. UPLOAD DRIVER VIDEO (YOUR LIP SYNC)

**Look for "Driver Video" or "Motion Video" upload field**

**Click upload** and select `shot_03_driver.mov`

**Kling will analyze** your facial movements (takes ~10 seconds)

---

#### 7F. UPLOAD CHARACTER IMAGE (SILLY SHOT)

**Look for "Character Image" or "Target Image" upload field**

**Click upload** and select `shot_03_jumping.png` (the Silly keyframe for this shot)

**Important:** Use the STATIC keyframe image, NOT the animated clip
- If you only have the animated clip, extract first frame as PNG

---

#### 7G. SET KLING SETTINGS

**Mode:** Lip Sync or Motion Control (depending on Kling's interface)

**Settings:**
- **Motion strength:** Medium-High (you want clear mouth movement)
- **Face region:** Focus on mouth/jaw
- **Duration:** Auto (Kling matches driver video length)
- **Quality:** High or Max

**Advanced settings (if available):**
- **Preserve background:** ON (keep Room of Wonder/Venice Beach intact)
- **Character consistency:** ON (keep Silly looking like Silly)

---

#### 7H. GENERATE LIP-SYNCED VIDEO

**Click "Generate" or "Create"**

**Wait:** 2-4 minutes (Kling motion control takes longer than image-to-video)

**Kling will:**
1. Analyze your mouth movements from driver video
2. Map them onto Silly's face
3. Animate Silly's mouth to match
4. Keep rest of character/scene intact
5. Output lip-synced video clip

---

#### 7I. PREVIEW THE RESULT

**Play the generated clip**

**Check:**
- ✅ Does Silly's mouth move in sync with lyrics?
- ✅ Does Silly's face still look like Silly (no weird morphing)?
- ✅ Is background intact?
- ✅ Does motion feel natural?
- ✅ Is sync accurate enough?

**If YES:** Download it
**If NO:** 
- Try again with different driver video (maybe exaggerate mouth more)
- Adjust motion strength setting
- Use clearer driver recording

**Note:** Kling lip sync is ~85-90% accurate. Don't expect 100% perfect - it just needs to be "good enough" for kids content.

---

#### 7J. DOWNLOAD LIP-SYNCED CLIP

**Click "Download" or "Export"**

**Format:** MP4

**Save to:** `/Users/adriankarvinen/clawd/silly/video_clips/[SONG_TITLE]/`

**Name it:** `clip_03_jumping_LIPSYNCED.mp4`

**Naming convention:**
```
clip_[NUMBER]_[ACTION]_LIPSYNCED.mp4
```

**This REPLACES the regular Image-to-Video version for shots with SYNC: YES**

---

### REPEAT FOR OTHER LIP SYNC SHOTS:

**Shot 7 (SYNC: YES):**
1. Extract audio segment (0:57-1:05)
2. Record yourself lip syncing
3. Upload to Kling (driver video + Silly Shot 7 image)
4. Generate
5. Download as `clip_07_singing_LIPSYNCED.mp4`

**Shot 10 (SYNC: YES):**
1. Extract audio segment (1:25-1:32)
2. Record yourself lip syncing
3. Upload to Kling
4. Generate
5. Download as `clip_10_final_LIPSYNCED.mp4`

---

## 💡 LIP SYNC TIPS:

### **When Lip Sync Isn't Perfect:**
- **Kids won't notice** small sync issues
- **Energy matters more** than precision
- **Wide shots don't need perfect sync** (mouth is small on screen)
- **Close-ups need better sync** (mouth is prominent)

### **If Kling Fails:**
**Option 1:** Use the regular Image-to-Video clip (without lip sync)
- Just add more motion in mouth area
- Prompt: "Silly singing, mouth opening and closing rhythmically"

**Option 2:** Try alternative tool
- Veed Fast (fal.ai)
- D-ID (d-id.com)
- HeyGen (heygen.com)

**Option 3:** Accept "good enough"
- If it's 80% synced, that's fine for kids content
- Over-perfecting wastes time

### **For Multiple Takes:**
**If chorus repeats 4 times, you don't need to lip sync all 4:**
- Lip sync chorus 1 (Shot 3)
- Reuse same lip-synced clip for chorus 2, 3, 4
- Just use different camera angles from Shots

**Workflow:**
1. Generate 4 different angles of "Silly singing" using Higgsfield Shots
2. Lip sync ONE of them with Kling
3. Use lip-synced clip for close-ups
4. Use non-synced clips for wide shots (don't need precision)

---

## 📊 BY THE END OF STEP 7:

**You'll have:**
- 12-16 total video clips in your folder
- 2-3 are lip-synced versions (for SYNC: YES shots)
- 9-13 are regular animated versions (for SYNC: NO shots)
- All ready to import to CapCut

**File structure:**
```
/clawd/silly/video_clips/good_morning_song/
├── clip_01_waking_up.mp4 (regular)
├── clip_02_stretching.mp4 (regular)
├── clip_03_jumping_LIPSYNCED.mp4 ← Lip synced
├── clip_04_window.mp4 (regular)
├── clip_05_skateboard.mp4 (regular)
├── clip_06_guitar.mp4 (regular)
├── clip_07_singing_LIPSYNCED.mp4 ← Lip synced
├── clip_08_beach.mp4 (regular)
...
├── clip_12_waving.mp4 (regular)
```

---

## ⏭️ NEXT: STEP 8 - EDIT IN CAPCUT

**All clips ready → Time to assemble the video**

---

### STEP 8: EDIT VIDEO IN CAPCUT

**Tool:** CapCut (free desktop or mobile app)

**What This Step Does:**
- Assembles all clips into one video
- Syncs clips to music beats
- Adds text overlays (lyrics) - AUTO-GENERATED!
- Adds transitions
- Color grades
- Exports final video

**Time:** 45-60 minutes (first video) → 30 minutes (after workflow learned)

**Cost:** Free

---

## 🚀 NEW CAPCUT 2025/2026 FEATURES YOU'LL USE:

### **1. AUTO-CAPTIONS (For Lyrics Display)**
**What:** CapCut listens to your audio and auto-generates perfectly synced text
**Use for Silly:** Display song lyrics on screen without manual typing/timing
**Time saved:** 30+ minutes per video

### **2. BEAT MARKERS (Manual)**
**What:** Visual markers on timeline showing where beats hit
**Limitation:** Auto-beat detection only works with TikTok library audio (NOT custom MP3s)
**Solution:** Manually mark beats by playing song and hitting "M" key

### **3. VELOCITY EFFECTS**
**What:** Speed changes that sync to beat markers
**Use:** Slow-mo on beat drops for emphasis

### **4. AI AUTO-CUT (Optional)**
**What:** AI selects and cuts clips automatically to beat
**Pros:** Fast rough cut
**Cons:** Less control, better for simple edits
**Recommendation:** Skip for first video, use for batch production later

---

## 📋 COMPLETE CAPCUT WORKFLOW (STEP-BY-STEP):

---

### PHASE 1: SETUP & IMPORT (5 minutes)

#### 8A. OPEN CAPCUT

**Desktop or mobile** (desktop recommended for first video)

---

#### 8B. CREATE NEW PROJECT

**Click:** "New Project"

**Choose Aspect Ratio:**
- **9:16 (Vertical)** for TikTok/Instagram Reels/YouTube Shorts (RECOMMENDED)
- **16:9 (Horizontal)** for YouTube main feed
- **1:1 (Square)** for Instagram feed

**Recommendation:** Start with 9:16 (vertical = better algorithm reach)

**Name project:** `[SONG_TITLE]_v1`

---

#### 8C. IMPORT ALL ASSETS

**Import to CapCut:**
1. **Audio:** Your Suno MP3 (`good_morning_song.mp3`)
2. **Video clips:** All 12-16 animated clips (from `/silly/video_clips/[SONG_TITLE]/`)
3. **Lip sync clips:** Any Kling-generated lip sync clips (if applicable)

**How to import:**
- Drag and drop files into CapCut media library (left panel)
- Or click "Import" button

**Verify all files imported (should see thumbnails)**

---

#### 8D. ADD AUDIO TO TIMELINE FIRST

**CRITICAL:** Always add audio first

**Drag your Suno MP3 to the audio track (bottom of timeline)**

**Why audio first:**
- Everything else syncs to music
- You'll see exact runtime
- Can place beat markers
- Clips will snap to audio timing

**Your timeline now looks like:**
```
AUDIO:  [=================SONG MP3==================]
        0:00                                        1:30

VIDEO:  [empty - you'll add clips here]
```

---

### PHASE 2: MARK BEATS & KEY MOMENTS (10 minutes)

#### 8E. ADD BEAT MARKERS MANUALLY

**CapCut's auto-beat detection doesn't work for custom MP3s**

**Manual method (most reliable):**

1. **Click audio track** to select it
2. **Play the song** (press spacebar)
3. **Hit "M" key** on every major beat
4. **Focus on:**
   - Chorus starts (most important)
   - Verse transitions
   - Beat drops
   - Key lyric moments

**You'll see white markers** appear on timeline

**Don't mark every single beat - just the important ones:**
- Intro start (0:00)
- First chorus hit (~0:25)
- Second verse start (~0:41)
- Second chorus hit (~0:57)
- Bridge start (~1:13)
- Final chorus (~1:25)
- Outro start (~1:37)

**Total markers: 8-12 for 90-second song**

**Your timeline now:**
```
AUDIO:  [=================SONG MP3==================]
        ↓    ↓       ↓       ↓       ↓       ↓
       markers on key beats

VIDEO:  [empty - ready for clips]
```

---

### PHASE 3: ASSEMBLE VIDEO CLIPS (15 minutes)

#### 8F. LAY OUT ALL CLIPS IN ORDER

**Don't worry about timing yet - just get them on timeline**

**Drag clips from media library to video track:**

1. **Shot 1** → Drag to 0:00
2. **Shot 2** → Drag after Shot 1
3. **Shot 3** → Drag after Shot 2
4. Continue for all 12-16 shots

**They'll be too long - that's fine**

**Your timeline now:**
```
AUDIO:  [=================SONG MP3==================]
        ↓    ↓       ↓       ↓       ↓       ↓

VIDEO:  [Shot1][Shot2][Shot3][Shot4][Shot5][Shot6]...
```

---

#### 8G. TRIM CLIPS TO MATCH STORYBOARD TIMING

**Your storyboard told you:**
```
SHOT 1 (0:00-0:08) - 8 seconds
SHOT 2 (0:09-0:16) - 7 seconds
SHOT 3 (0:17-0:25) - 8 seconds
```

**For each clip:**

1. **Hover over clip edge** until you see resize cursor
2. **Drag edge** to trim
3. **Watch timestamp** in top corner (CapCut shows exact time)
4. **Trim to match storyboard duration**

**Shortcuts:**
- **S** = Split clip at playhead
- **Delete** = Remove selected clip
- **Cmd/Ctrl + Z** = Undo

**Goal:** Each clip is roughly the right length from storyboard

---

#### 8H. FINE-TUNE TO BEAT MARKERS

**Now make clips hit on beats:**

1. **Select a clip**
2. **Drag it left/right** until it aligns with nearest beat marker
3. **CapCut has "snap to marker"** - clips will magnetically snap when close
4. **Adjust clip length** so end also hits a marker (if needed)

**Example:**
- Shot 3 should START at 0:17 marker (chorus drop)
- Shot 3 should END at 0:25 marker (verse start)

**This is where your video starts feeling "on beat"**

**Tip:** Play through and listen - do cuts feel rhythmic? If not, shift clips slightly.

---

### PHASE 4: ADD LYRICS MANUALLY (20 minutes)

**⚠️ Note:** CapCut's auto-captions don't work reliably with singing/music. Manual is better.

#### 8I. IDENTIFY KEY LYRICS TO DISPLAY

**Don't put every single word on screen - just the HOOKS**

**From your storyboard, pick:**
- Main chorus hook (e.g., "GOOD MORNING!")
- Repeated phrases (e.g., "WE CAN DO IT!")
- Key teaching moments (e.g., "Brush brush brush!")

**Typical Silly video: 6-10 text displays total**

**Example for "Good Morning Song":**
1. "GOOD MORNING!" (appears 4 times - chorus)
2. "WE'RE READY FOR THE DAY!" (appears 4 times)
3. "Let's go!" (bridge)
4. "Jump! Jump!" (bridge action)

**Rule:** Less is more. Too much text = overwhelming for kids.

---

#### 8J. ADD TEXT CLIPS TO TIMELINE

**For each lyric moment:**

1. **Move playhead** to where lyric should appear (use your beat markers)
2. **Click "Text" button** (top toolbar)
3. **Choose "Default Text"** or any basic text template
4. **A text clip appears** on timeline above video

**Drag text clip edges** to set how long it stays on screen:
- Short punchy phrases: 2-3 seconds
- Hook phrases: 3-5 seconds
- Don't leave text on too long (kids lose interest)

---

#### 8K. STYLE TEXT FOR SILLY BRANDING

**For EACH text clip:**

1. **Double-click text clip** on timeline (opens text editor)
2. **Type the lyric** (e.g., "GOOD MORNING!")

**Customize in right panel:**

**FONT:**
- **Bold, kid-friendly fonts:**
  - Baloo 2 (rounded, friendly)
  - Fredoka One (bold, playful)
  - Lilita One (punchy)
  - Chewy (fun, bubbly)
- **Size:** 70-100pt (fill 25-30% of screen)
- **Weight:** Extra Bold

**COLOR:**
- **Primary:** White (#FFFFFF)
- **Outline/Stroke:** 
  - Black (#000000) - 6-8px thick
  - OR Teal (#1F6F6A) - 5px thick
- **Shadow:** Black drop shadow, 50% opacity, 4px offset
- **Alt colors:** Yellow (#FFD700), Orange (#FF6B35) for variety

**POSITION:**
- **Bottom third** (so Silly's face visible above)
- **OR top third** (if action is bottom-focused)
- **Never center** (covers Silly)
- **Alignment:** Center horizontal

**ANIMATION:**
- **In:** "Pop" or "Bounce" (0.2 sec)
- **Out:** "Fade" or "Shrink" (0.2 sec)
- **During:** "Bounce loop" (subtle, on beat)

**Example setup:**
```
Text: "GOOD MORNING!"
Font: Fredoka One
Size: 90pt
Color: White
Stroke: Black, 7px
Shadow: Black, 50%, 5px offset
Position: Bottom, centered, 15% from bottom
Animation In: Pop (0.2s)
Animation Out: Fade (0.2s)
```

---

#### 8L. SYNC TEXT TO BEAT MARKERS

**Make text appear ON THE BEAT:**

1. **Select text clip** on timeline
2. **Drag it left/right** until it snaps to a beat marker
3. **The "pop in" animation should hit exactly on beat**

**Play through and check:**
- Does text appear with the vocal?
- Does it pop on the beat?
- Is timing natural?

**Adjust by dragging clip edges or position**

---

#### 8M. ADD TEXT EFFECTS (OPTIONAL)

**For extra punch on chorus moments:**

**CapCut effects for text:**
1. **Select text clip**
2. **Click "Effects"** (top toolbar)
3. **Choose effect:**
   - **"Glitch"** - Quick flash on beat drop
   - **"Neon"** - Glowing text for energy
   - **"3D"** - Depth for emphasis
   - **"Shake"** - Vibration on beat

**Apply to 1-2 key moments only** (not every text or it's too much)

**Example:** Add "Glitch" effect to "GOOD MORNING!" on the first chorus drop

---

#### 8N. DUPLICATE TEXT FOR REPEATED LYRICS

**If chorus repeats 4 times, don't remake text 4 times:**

1. **Right-click first "GOOD MORNING!" text clip**
2. **Click "Duplicate"** (or Cmd/Ctrl+D)
3. **Drag duplicate** to next chorus position
4. **Repeat for all chorus appearances**

**This ensures consistency - same style, same animation**

---

### PHASE 5: ADD TRANSITIONS & EFFECTS (10 minutes)

#### 8L. ADD SIMPLE TRANSITIONS

**Between clips, add transitions:**

**Recommended transitions for Silly:**
- **Cross Dissolve** (smooth, most common) - 0.3 sec
- **Flash** (on beat drops) - 0.1 sec
- **Quick Cut** (no transition, just cut) - 0 sec

**How to add:**
1. **Click between two clips** on timeline
2. **Click "Transitions" button** (top toolbar)
3. **Choose transition type**
4. **Drag to timeline** between clips
5. **Adjust duration** (0.3 sec is good default)

**Rules:**
- Don't overuse fancy transitions (distracting for kids)
- Use flash/whip only on major beat drops
- Most cuts can be simple cross dissolve
- Some cuts need no transition (quick energy)

---

#### 8M. ADD VELOCITY EFFECTS (OPTIONAL)

**For emphasis on beat drops:**

**Example:** Slow-mo on chorus hit

1. **Select clip** where you want slow-mo
2. **Click "Speed"** button (top toolbar)
3. **Choose "Curve" or "Velocity"**
4. **Drag curve down** at the moment you want slow
5. **CapCut will smooth the speed change**

**Use sparingly - 1-2 times per video max**

---

### PHASE 6: COLOR GRADE (5 minutes)

#### 8N. APPLY COLOR CORRECTION FOR KIDS CONTENT

**Kids videos need to be BRIGHT and VIBRANT**

**Select all video clips:**
1. Click first clip
2. Shift+click last clip (selects all)

**Click "Adjust" button (top toolbar)**

**Adjust settings:**
- **Brightness:** +10 to +15
- **Contrast:** +5 to +10
- **Saturation:** +15 to +25 (more colorful)
- **Temperature:** +5 (slightly warmer/golden)
- **Highlights:** +10 (brighter)

**OR use CapCut's preset filters:**
- Click "Filters" (top toolbar)
- Choose: "Vivid", "Summer", "Bright", "Pop"
- Apply to all clips

**Goal:** Punchy, saturated, bright - not washed out

---

#### 8O. ADD SILLY BRANDING (OPTIONAL)

**If you have intro/outro clips:**

**Intro (3 seconds):**
- "SILLY THE SEAL" title card
- Place at 0:00 before first shot
- Teal background, rainbow text

**Outro (5 seconds):**
- "SUBSCRIBE FOR MORE SILLY!"
- Silly waving animation
- Place at end after last shot

**These can be templates you reuse for every video**

---

### PHASE 7: FINAL REVIEW & ADJUSTMENTS (10 minutes)

#### 8P. PLAY THROUGH ENTIRE VIDEO

**Watch from start to finish WITHOUT stopping**

**Check:**
- ✅ Does video feel on-beat?
- ✅ Do cuts hit where they should?
- ✅ Are lyrics readable and synced?
- ✅ Is Silly's face visible in most shots?
- ✅ Is energy level right (not too slow, not too chaotic)?
- ✅ Does it feel fun to watch?

---

#### 8Q. MAKE FINAL TWEAKS

**Common adjustments:**
- Trim a clip that feels too long
- Shift a cut to hit beat better
- Adjust a caption that's hard to read
- Add a flash transition on chorus drop
- Brighten a clip that's too dark

**Trust your gut - if something feels off, adjust it**

---

### PHASE 8: EXPORT (5 minutes)

#### 8R. EXPORT SETTINGS

**Click "Export" button (top right)**

**Settings:**
- **Resolution:** 1080p (minimum) or 2160p/4K (if available)
- **Frame Rate:** 30fps (standard for kids content)
- **Format:** MP4
- **Quality:** High or Best
- **Codec:** H.264 (most compatible)

**Name file:** `[SONG_TITLE]_FINAL_v1.mp4`

**Export location:** `/Users/adriankarvinen/clawd/silly/final_videos/`

**Click "Export"**

**Wait:** 3-5 minutes for export (depends on video length and computer speed)

---

#### 8S. VERIFY EXPORT

**After export completes:**

1. **Open the MP4 file**
2. **Watch the first 10 seconds** (does it play?)
3. **Scrub through** (any glitches?)
4. **Check audio sync** (does audio match video?)
5. **Check resolution** (is it 1080p+?)

**If something's wrong:** Re-export with different settings

**If it's good:** Ready for upload!

---

## 🛠️ ALTERNATIVE TOOLS (DISCOVERED JAN 2026)

**If you want FASTER beat sync in future:**

### **Option 1: VidBeat (FREE)**
- **What:** Auto-syncs video clips to music beat using AI
- **URL:** vidbeat.app
- **Discovered:** Sept 2025 on Reddit as free BeatLeap alternative
- **Process:**
  1. Upload your Suno MP3
  2. Upload all video clips
  3. AI auto-cuts and syncs to beat
  4. Export and import to CapCut for final polish
- **Pros:** Free, fast, automatic
- **Cons:** Less control than manual CapCut editing

### **Option 2: BeatLeap (PAID - $10/month)**
- **What:** Professional musically-driven video editor by Lightricks
- **Process:**
  1. Import clips + music
  2. AI analyzes beat and tempo
  3. Auto-syncs clips with ML
  4. Add filters and effects
  5. Export
- **Pros:** Professional results, very accurate
- **Cons:** Costs $10/month, less customization than CapCut

### **Option 3: CapCut Pro Auto-Cut (PAID)**
- **What:** CapCut's premium AI auto-editing feature
- **Process:**
  1. Import clips + audio
  2. Click "Auto Cut"
  3. AI generates rough cut synced to beat
  4. Manually refine
- **Pros:** Stays in one tool
- **Cons:** Requires CapCut Pro ($10/month), less control

---

## 💡 RECOMMENDED APPROACH:

**First 3-5 videos:** Manual CapCut editing (learn the workflow, full control)

**After 5 videos:** Consider VidBeat for rough cut, then polish in CapCut (saves 20-30 min)

**At scale (10+ videos/week):** Invest in BeatLeap or CapCut Pro for speed

---

---

### STEP 9: CREATE THUMBNAIL & UPLOAD TO YOUTUBE

**What This Step Does:**
- Creates eye-catching thumbnail
- Exports final video from CapCut
- Uploads to YouTube with optimized metadata
- Sets as kids content (COPPA)
- Publishes or schedules

**Time:** 20-30 minutes

**Cost:** Free

---

## 📸 PHASE 1: CREATE THUMBNAIL (10 minutes)

**Thumbnails = 50% of whether people click**

---

#### 9A. CHOOSE YOUR BEST SILLY FRAME

**Option 1: Export frame from CapCut**
1. In CapCut, scrub to a moment where Silly looks great (big smile, energetic)
2. Usually: chorus peak, jumping shot, celebrating
3. Click "Snapshot" or "Export Frame" button
4. Save as `silly_thumbnail_frame.png`

**Option 2: Use one of your keyframe images**
- Pick the most energetic/expressive shot
- E.g., jumping, celebrating, big smile

**Best frames show:**
- Silly's face clearly
- High energy expression
- Bright, colorful background (Room of Wonder or Venice Beach)

---

#### 9B. GO TO CANVA

**Open:** canva.com

**Create new design:**
- Search templates: "YouTube Thumbnail"
- Dimensions: 1280 x 720px (auto-set)

---

#### 9C. DESIGN THE THUMBNAIL

**Layout formula for Silly thumbnails:**

**Background:**
- Upload your Silly frame
- Full-bleed (covers whole thumbnail)
- OR use solid color background (teal #1F6F6A, orange #FF6B35)

**Silly character:**
- Should fill 50-60% of thumbnail
- Face clearly visible
- Positioned left or right (not center - leave room for text)

**Text overlay:**
- **Song title in BIG BOLD text**
- Example: "GOOD MORNING!"
- Font: Bold, chunky, kid-friendly (Fredoka One, Baloo, Lilita One)
- Size: HUGE (fills 30-40% of thumbnail)
- Color: Yellow (#FFD700) or White (#FFFFFF)
- Stroke: Black 10-15px (makes text pop)
- Position: Top or opposite side from Silly

**Additional elements (optional):**
- Musical notes graphics (🎵)
- Lightning bolts (matches Silly's shirt)
- Bright shapes/bursts behind text
- "NEW!" badge (for first few videos)

**Example thumbnail layout:**
```
┌─────────────────────────────┐
│  [Musical note]             │ ← Graphics
│                             │
│         GOOD                │ ← Big text
│        MORNING!             │
│                             │
│  [Silly jumping]            │ ← Character
│  [with big smile]           │
│                             │
└─────────────────────────────┘
```

---

#### 9D. OPTIMIZE FOR MOBILE

**70% of YouTube views = mobile**

**Test:** Zoom out thumbnail to 20% size - can you still read text?

**If NO:** Make text bigger

**Mobile-optimized means:**
- Text fills MORE space than you think
- High contrast (bright colors)
- Simple (not busy/cluttered)

---

#### 9E. DOWNLOAD THUMBNAIL

**Click "Download"**

**Format:** JPG (smaller file size than PNG, YouTube prefers it)

**Quality:** High

**Save as:** `[SONG_TITLE]_THUMBNAIL.jpg`

**Example:** `GOOD_MORNING_SONG_THUMBNAIL.jpg`

**Save to:** `/Users/adriankarvinen/clawd/silly/thumbnails/`

---

## 🎥 PHASE 2: EXPORT FROM CAPCUT (5 minutes)

**This should already be done from Step 8R, but verifying:**

---

#### 9F. FINAL EXPORT CHECK

**Your exported file should be:**
- **Location:** `/Users/adriankarvinen/clawd/silly/final_videos/`
- **Name:** `[SONG_TITLE]_FINAL_v1.mp4`
- **Resolution:** 1080p or higher
- **Format:** MP4
- **Size:** 50-200MB (for 90-second video)

**If not exported yet:** Go back to Step 8R and export

---

#### 9G. VERIFY VIDEO FILE

**Before uploading, double-check:**

1. **Play the video** start to finish
2. **Check audio sync** (does music match video?)
3. **Check for glitches** (any black frames, freezes?)
4. **Check resolution** (right-click file → Get Info → should say 1920x1080 or higher)
5. **Check file size** (if over 500MB, something's wrong - re-export with lower bitrate)

**If anything's wrong:** Re-export from CapCut with adjusted settings

---

## 📤 PHASE 3: UPLOAD TO YOUTUBE (15 minutes)

---

#### 9H. GO TO YOUTUBE STUDIO

**Open:** studio.youtube.com

**Log in** with your YouTube/Google account

**Click:** "Create" button (top right, camera icon with +)

**Select:** "Upload videos"

---

#### 9I. SELECT VIDEO FILE

**Click "SELECT FILES"** or drag-and-drop

**Choose:** Your exported MP4 (`GOOD_MORNING_SONG_FINAL_v1.mp4`)

**Upload begins** (takes 2-5 minutes depending on file size)

**While uploading, you'll fill in details:**

---

#### 9J. FILL IN VIDEO DETAILS

### **TITLE:**

**Formula:**
```
[Catchy Song Title] | Silly the Seal | [Video Type]
```

**Examples:**
- "Good Morning Song! 🌅 | Silly the Seal | Kids Pop Punk Songs"
- "It's Hard to Stop! | Silly the Seal | Transition Songs for Kids"
- "We Can Try Again! | Silly the Seal | Preschool Music"

**Tips:**
- Keep under 60 characters (better for mobile)
- Include emoji (catches eye in search)
- Front-load main keywords
- Mention Silly the Seal (brand recognition)

**Character limit:** 100 max, aim for 50-70

---

### **DESCRIPTION:**

**Formula:**
```
[Hook sentence]

[What the song is about - 2-3 sentences]

[Call to action]

[Links]

[Hashtags]
```

**Example:**

```
🎵 Start your day with energy! Join Silly the Seal for the Good Morning Song! 🌅

Perfect for kids ages 3-7 learning morning routines. Silly brings pop-punk energy to daily rituals with catchy hooks and fun animations. Sing along as Silly wakes up, stretches, and gets ready for an awesome day in Venice Beach!

🦭 SUBSCRIBE for new Silly songs every week!
🎸 Pop-punk music that kids AND parents love
🏖️ Made with love in Venice Beach, California

👉 Follow Silly the Seal:
YouTube: youtube.com/@sillythesealsongs
Instagram: @sillythesealsongs

---

ABOUT SILLY THE SEAL:
Silly is a pop-punk seal living in Venice Beach who teaches kids daily skills through high-energy music. Think Blink-182 meets Sesame Street! Perfect for preschoolers and early elementary kids learning routines, emotions, and life skills.

#kidssongs #goodmorning #morningroutine #preschoolsongs #toddlermusic #poppunk #educationalsongs #sillythesealsongs #kidsmusic #parenting
```

**Description character limit:** 5,000 (use 800-1,200)

---

### **THUMBNAIL:**

**Click "Upload thumbnail"**

**Select:** Your Canva-created thumbnail (`GOOD_MORNING_SONG_THUMBNAIL.jpg`)

**YouTube will show preview** - verify it looks good

---

### **PLAYLIST:**

**Add to playlist:** "Silly the Seal Songs" (create if first video)

**Why:** Playlists increase watch time (auto-play next video)

**Later, create specific playlists:**
- "Morning Routine Songs"
- "Transition Songs"  
- "Emotional Regulation Songs"
- etc.

---

### **AUDIENCE:**

**Is this video made for kids?** → **YES**

**Why this matters (COPPA compliance):**
- YouTube turns off comments
- Limits data collection
- Changes recommendation algorithm
- Required by law for kids content (age 3-7)

**Don't click NO - Silly content IS for kids**

---

### **AGE RESTRICTION:**

**No age restriction** (Silly is for young kids)

---

#### 9K. ADD VIDEO ELEMENTS (OPTIONAL BUT RECOMMENDED)

### **END SCREEN:**

**Click "End screen"**

**Add elements at end of video (last 5-20 seconds):**
- **Subscribe button** (encourages subs)
- **Best for viewer** (YouTube suggests related video)
- **Playlist** (your "Silly Songs" playlist)

**Template:** Use YouTube's default template (works fine)

---

### **CARDS:**

**Click "Cards"**

**Add mid-video pop-up links:**
- At 0:30 → Link to another Silly song
- At 1:00 → Link to Silly playlist

**Don't overuse** - 1-2 cards max

---

#### 9L. ADVANCED SETTINGS

**Click "Show more"**

### **CATEGORY:**
- **Education** (if teaching/routine song)
- **Entertainment** (if pure fun/anthem song)

**For Silly:** Usually **Education**

---

### **TAGS:**

**Add 10-15 tags** (keywords for search):

**Example tags for "Good Morning Song":**
```
kids songs
good morning song
morning routine
toddler songs
preschool music
pop punk kids
educational songs
childrens music
silly the seal
venice beach
kids entertainment
songs for kids
morning songs
daily routine
preschool routine
```

**Tips:**
- Mix broad tags ("kids songs") + specific tags ("good morning routine")
- Include brand ("silly the seal")
- Use song type ("pop punk kids")
- Don't spam - keep relevant

---

### **LANGUAGE:**
**English** (or your primary language)

---

### **CAPTIONS:**
**YouTube auto-generates captions** - leave default

**Later:** You can edit for accuracy if needed

---

#### 9M. SET VISIBILITY

**Three options:**

**1. PUBLIC** (everyone can see immediately)
- Use if you want to publish right now

**2. SCHEDULED** (publish at specific time)
- **Best for Silly:** Schedule for optimal time
- **Recommended times for kids content:**
  - **Weekdays:** 7-8am (before school) or 4-5pm (after school)
  - **Weekends:** 8-10am (Saturday/Sunday mornings)
- Click "Schedule" → Pick date/time

**3. UNLISTED/PRIVATE**
- Skip unless you're testing

**Recommendation for Silly:**
→ **Schedule for 8am on a weekday** (Tuesday, Wednesday, or Thursday)

---

#### 9N. PUBLISH!

**Click "PUBLISH"** (or "SCHEDULE" if scheduling)

**YouTube will:**
1. Process video (HD version takes 10-30 min)
2. Generate auto-captions
3. Create different quality options (1080p, 720p, 480p, etc.)
4. Index for search
5. Add to your channel

**You'll see:** "Video published!" confirmation

---

## 📱 PHASE 4: SHARE TO OTHER PLATFORMS (OPTIONAL)

---

#### 9O. UPLOAD TO TIKTOK (OPTIONAL)

**If you want maximum reach:**

**Steps:**
1. Open TikTok app (mobile)
2. Click "+" to create
3. Upload your MP4 video
4. **Caption:**
```
Good morning song with Silly the Seal! 🦭🌅 Pop-punk for kids! #kidssongs #goodmorning #poppunk #preschool
```
5. **Hashtags:** #kidssongs #toddlersongs #preschool #poppunk #morningroutine
6. Post

**Note:** TikTok is vertical-first, so if you exported 9:16, it'll look great

---

#### 9P. UPLOAD TO INSTAGRAM REELS (OPTIONAL)

**Steps:**
1. Open Instagram app
2. Click "+" → Reel
3. Upload your video
4. **Caption:**
```
🌅 Good morning with Silly! Pop-punk morning song for kids! 
#kidssongs #sillythesealsongs #poppunk #preschool
```
5. Post

---

## 📊 PHASE 5: VERIFY & MONITOR (5 minutes)

---

#### 9Q. CHECK YOUR VIDEO ON YOUTUBE

**After publishing:**

1. **Go to your channel** (youtube.com/@yourusername)
2. **Click on the video** to watch it
3. **Verify:**
   - ✅ Thumbnail showing correctly?
   - ✅ Title looks good?
   - ✅ Video plays in HD?
   - ✅ Description formatted correctly?
   - ✅ End screen working?

**If anything's wrong:** Edit video (YouTube Studio → Videos → Edit)

---

#### 9R. TRACK PERFORMANCE (AFTER 24-48 HOURS)

**YouTube Studio → Analytics**

**Key metrics for kids content:**
- **Views** (how many people watched)
- **Watch time** (how long they watched)
- **Audience retention** (where they drop off)
- **Traffic sources** (where viewers came from)

**Goals for first video:**
- 100+ views in first week = good start
- 50%+ average watch time = engaging content
- YouTube search/browse traffic = SEO working

**Don't stress if first video is slow** - algorithm needs data

---

## ✅ CONGRATULATIONS - YOUR FIRST SILLY VIDEO IS LIVE!

**You now have:**
- ✅ Complete production workflow
- ✅ First video published on YouTube
- ✅ Reusable process for future videos
- ✅ Foundation for Silly the Seal channel

---

## 🚀 WHAT'S NEXT:

**Immediate:**
- Share video with friends/family for initial views
- Post on your social media
- Watch analytics after 48 hours

**This week:**
- Start planning Video #2 (use same workflow, will be faster)
- Build backlog of 3-4 song ideas
- Create playlist structure on YouTube

**This month:**
- Produce 2-4 more videos (weekly or bi-weekly cadence)
- Refine workflow (by video 5, you'll be 2x faster)
- Start A/B testing thumbnails

**Long-term:**
- Build 20-30 video catalog (the "library")
- Consistent upload schedule (weekly recommended for kids content)
- Cross-promote on TikTok/Instagram
- Eventually: consider paid ads, partnerships, merchandise

---

---

## 🎉 CONGRATULATIONS - VIDEO COMPLETE!

**You now have:**
- ✅ Published Silly the Seal video
- ✅ Complete production workflow documented
- ✅ Reusable process for next videos

---

## 📊 PRODUCTION METRICS (FIRST VIDEO)

**Time Breakdown:**
- Song generation (Gem + Suno): 10 min
- Script extraction: 5 min
- Storyboard generation (Shots): 40 min
- Animation (Image-to-Video): 60 min
- Lip sync (optional): 20 min
- Editing (CapCut): 60 min
- Export & upload: 20 min
**TOTAL:** ~3-4 hours

**Cost Breakdown:**
- Suno: $0-0.50
- Higgsfield: $5-10
**TOTAL:** ~$5-10

---

## ⚡ OPTIMIZATION FOR FUTURE VIDEOS

**After 5 videos, time drops to ~90 minutes by:**
- Reusing environments (Room of Wonder, Venice Beach)
- Batch generating storyboards
- Using CapCut templates
- Faster editing decisions

**After 10 videos, time drops to ~60 minutes by:**
- Pre-generated pose library
- Refined prompts
- Editing templates
- Workflow muscle memory

---

## 📁 FILE ORGANIZATION

**Your complete file structure:**

```
/clawd/silly/
├── songs/
│   └── GOOD_MORNING_SONG.md
├── audio/
│   └── good_morning_song.mp3
├── scripts/
│   └── GOOD_MORNING_SONG_SCRIPT.md
├── storyboards/
│   └── good_morning_song/
│       ├── shot_01.png
│       ├── shot_02.png
│       └── ...
├── video_clips/
│   └── good_morning_song/
│       ├── clip_01_waking_up.mp4
│       ├── clip_02_stretching.mp4
│       └── ...
├── final_videos/
│   └── GOOD_MORNING_SONG_FINAL_v1.mp4
└── thumbnails/
    └── GOOD_MORNING_SONG_THUMBNAIL.jpg
```

---

## 🎓 ONBOARDING CHECKLIST

**For training someone new, they need:**
- [ ] Access to all tools (Gemini, Suno, Higgsfield, CapCut)
- [ ] Silly Music Brain Gem
- [ ] Silly Visual Brain Gem
- [ ] Silly the Seal Canon (51 reference images)
- [ ] This workflow document
- [ ] 3-4 hours for first video
- [ ] Patience - it gets faster!

---

## 🚀 READY TO SHIP

**This workflow is battle-tested and ready for:**
- Training new team members
- Scaling production (multiple videos/week)
- Maintaining quality while increasing speed
- Building Silly's content library

---

## 📋 QUICK REFERENCE GUIDE

**For when you've done this once and just need the steps:**

### **THE 10 STEPS:**

1. **Generate song options** (Silly Music Brain Gem → Pick one)
2. **Generate complete song** (Music Brain Gem → Lyrics + Suno prompt)
3. **Generate audio in Suno** (Paste prompt → Generate → Apply Silly persona → Download MP3)
4. **Analyze audio** (Silly Audio Analysis Brain Gem → Energy map + timestamps) ← NEW
5. **Generate storyboard** (Silly Storyboard Brain Gem → Lyrics + Audio Analysis → 28-32 shots)
6. **Generate images** (Higgsfield Shots → Pick angles)
7. **Animate images** (Higgsfield Image-to-Video → Motion prompts)
8. **Lip sync** (Record yourself → Kling motion control → 2-3 close-ups)
9. **Edit in CapCut** (Assemble → Cuts on beat markers from analysis → Lyrics → Polish)
10. **Create thumbnail + Upload** (Canva → YouTube → Schedule 8am)

---

## ⏱️ TIME BREAKDOWN (BY VIDEO NUMBER)

### **FIRST VIDEO:**
- Song generation: 10 min
- Audio analysis: 5 min ← NEW
- Storyboard: 5 min
- Image generation: 30 min
- Animation: 60 min
- Lip sync: 30 min
- CapCut editing: 50 min (faster with precise beat markers from analysis)
- Thumbnail + upload: 30 min
**TOTAL: 3.5-4 hours**

### **FIFTH VIDEO:**
- Song generation: 8 min
- Storyboard: 3 min
- Image generation: 20 min
- Animation: 45 min
- Lip sync: 20 min
- CapCut editing: 40 min
- Thumbnail + upload: 20 min
**TOTAL: 2-2.5 hours**

### **TENTH VIDEO:**
- Song generation: 5 min
- Storyboard: 3 min
- Image generation: 15 min (batch + reuse)
- Animation: 30 min
- Lip sync: 15 min
- CapCut editing: 30 min
- Thumbnail + upload: 15 min
**TOTAL: 90 minutes**

**Learning curve is REAL - you'll get 2-3x faster**

---

## 💰 COST BREAKDOWN (PER VIDEO)

### **TOOLS:**
- Suno: $0 (free tier) or $10/month unlimited
- Higgsfield Shots: ~$12 (12 shots × ~$1)
- Higgsfield Image-to-Video: ~$0 (included in Shots credits)
- Kling lip sync: ~$3 (3 shots)
- CapCut: $0 (free)
- Canva: $0 (free) or $13/month Pro
- YouTube: $0

**TOTAL PER VIDEO:** ~$15 (or ~$25/month amortized with subscriptions)

**At scale (10 videos/month):** ~$35/month for all tools

**Cost goes DOWN as you:**
- Reuse environments (same Room of Wonder shots)
- Reuse lip sync clips
- Batch generate
- Get better at first-time success rate

---

## 🛠️ TROUBLESHOOTING GUIDE

### **Problem: Higgsfield Shots doesn't match the action I need**
**Solution:** 
- Use closest Canon reference available
- Generate NEW reference first (Image-to-Video or Midjourney)
- Add to Canon for future reuse

---

### **Problem: Image-to-Video motion looks weird/jittery**
**Solution:**
- Simplify motion prompt (less complex actions)
- Lower motion strength
- Regenerate (sometimes random)
- Try different image (more neutral pose = smoother animation)

---

### **Problem: Kling lip sync doesn't sync well**
**Solution:**
- Re-record driver video with more exaggerated mouth movements
- Face camera more directly
- Use higher motion strength in Kling
- Accept "good enough" (80% sync is fine for kids)

---

### **Problem: CapCut timeline feels off-beat**
**Solution:**
- Re-mark beat markers (play song slowly and mark more carefully)
- Shift clips by 0.1-0.2 seconds (small adjustments matter)
- Trust your ears more than visual markers
- Watch reference music videos for pacing

---

### **Problem: Lyrics/text hard to read in CapCut**
**Solution:**
- Increase font size (go BIGGER than you think)
- Add thicker stroke/outline (8-10px black)
- Use higher contrast colors (white on dark, or dark on bright)
- Test on phone (not just computer)

---

### **Problem: Video looks washed out/not vibrant**
**Solution:**
- Increase saturation (+20 to +30)
- Increase brightness (+10 to +15)
- Apply CapCut "Vivid" or "Summer" filter
- Ensure original Higgsfield images are colorful (if not, add color grading prompt)

---

### **Problem: YouTube video not getting views**
**Solution (SEO & Algorithm):**
- Optimize title (front-load keywords: "Good Morning Song for Kids")
- Improve thumbnail (bigger text, brighter colors, Silly's face prominent)
- Add more tags (15-20 relevant tags)
- Share on social (initial views help algorithm)
- Create playlist (increases watch time)
- Post consistently (weekly uploads signal active channel)

---

### **Problem: Workflow taking too long**
**Solution (Speed Up):**
- Batch tasks (generate all images before animating)
- Reuse assets (same environments, poses, lip sync clips)
- Use VidBeat for auto beat-sync rough cut
- Create CapCut templates (save text styles, color grades)
- Skip perfection (kids won't notice 90% vs 100% quality)

---

## 📚 FILE ORGANIZATION TEMPLATE

**Copy this structure for each new song:**

```
/clawd/silly/
├── songs/
│   └── good_morning_song.md (lyrics + Suno prompt)
├── audio/
│   ├── good_morning_song.mp3 (full song)
│   └── audio_segments/
│       ├── shot_03_audio.mp3
│       └── shot_07_audio.mp3
├── storyboards/
│   ├── good_morning_song/
│   │   ├── GOOD_MORNING_SONG_STORYBOARD.md
│   │   ├── shot_01.png
│   │   ├── shot_02.png
│   │   └── ...
├── driver_videos/ (for lip sync)
│   ├── shot_03_driver.mov
│   └── shot_07_driver.mov
├── video_clips/
│   └── good_morning_song/
│       ├── clip_01_waking_up.mp4
│       ├── clip_02_stretching.mp4
│       ├── clip_03_jumping_LIPSYNCED.mp4
│       └── ...
├── final_videos/
│   └── GOOD_MORNING_SONG_FINAL_v1.mp4
└── thumbnails/
    └── GOOD_MORNING_SONG_THUMBNAIL.jpg
```

**Keep organized = easier to find assets for future videos**

---

## 🎓 SKILLS YOU'LL DEVELOP

**By video 10, you'll be expert at:**
- Visual storytelling (shot composition, pacing)
- Music video editing (beat matching, rhythm)
- Character consistency (maintaining Silly's look/vibe)
- Kids content optimization (what works, what doesn't)
- YouTube SEO (titles, tags, thumbnails)
- AI tool workflows (Suno, Higgsfield, Kling, CapCut)

**This workflow teaches PRODUCTION, not just creation**

---

## 🚀 SCALING BEYOND 10 VIDEOS

### **When you have 10+ videos:**

**Batch production:**
- Generate 3-4 songs in one session (Music Brain Gem)
- Generate 3-4 storyboards in one session
- Block time for "image generation day" (20-30 shots at once)
- Block time for "editing day" (assemble 2-3 videos)

**Reuse & templates:**
- Save CapCut project as template (text styles, color grades, transitions)
- Reuse Room of Wonder shots (same environment, different actions)
- Library of lip sync clips (remix for different songs)

**Outsourcing (when ready):**
- Hire video editor for CapCut assembly ($50-100/video on Fiverr)
- You focus on: song creation, storyboarding, quality control
- 10 videos/month becomes manageable

**Monetization (after 1,000 subs + 4,000 watch hours):**
- YouTube ad revenue (~$2-5 per 1,000 views for kids content)
- Sponsorships (brands, apps, products)
- Merchandise (Silly plushies, shirts, books)
- Licensing (educational platforms, streaming services)

---

## ✅ FINAL CHECKLIST (BEFORE CALLING VIDEO "DONE")

**Before publishing, verify:**

- [ ] Song is ~90 seconds (not too long)
- [ ] Storyboard has 12-16 shots (not too many cuts)
- [ ] All images use correct Silly character (consistency)
- [ ] Lip sync on 2-3 close-ups (not too much)
- [ ] Cuts hit on beat (feels rhythmic)
- [ ] Lyrics are readable (big text, high contrast)
- [ ] Video is bright & vibrant (kids content aesthetic)
- [ ] Exported at 1080p minimum (HD quality)
- [ ] Thumbnail is eye-catching (Silly + big text)
- [ ] Title is keyword-optimized (front-loads main phrase)
- [ ] Description has call-to-action (subscribe prompt)
- [ ] Set as "Made for Kids" (COPPA)
- [ ] Scheduled for optimal time (8am weekday)

**If all checked → SHIP IT!**

---

*COMPLETE WORKFLOW DOCUMENTED*  
*Last Updated: January 28, 2026, 9:55pm PST*  
*Status: PRODUCTION READY*  
*Version: 1.0*

**This document contains everything you need to produce professional Silly the Seal videos from zero to YouTube.**

**Questions? Issues? Updates?**  
→ Add notes to this file as you discover improvements  
→ Track changes in version number  
→ Share with team members for onboarding  

**Now go make Silly videos. 🐕🦭**
