# AI Creative Toolkit for Santi Campaign

Quick reference for AI tools to enhance campaign creativity.

---

## 🎨 Visual Enhancement

### Nano Banana Pro (Gemini-powered)
**Best for**: Photo transformation, angle changes, consistent style

```
Example prompts:
- "Transform this football action photo to show the player from a dramatic low angle"
- "Add stadium atmosphere: dust particles, dramatic lighting"
- "Create 4K version maintaining player likeness"
```

### Nano Banana Video
**Best for**: Animating still photos into motion

```
Example prompts:
- "Animate this photo: subtle wind in jersey, dust under feet"
- "Create 3-second loop of player running celebration"
```

### Alternatives
| Tool | Use When |
|------|----------|
| **RunwayML Gen-3** | Complex video generation |
| **FlexClip** | Quick social media edits |
| **Higgsfield** | Character-consistent video |

---

## 🎵 Music Generation

### Barra Anthem Creation

**Recommended**: Suno AI or Udio

**Master Prompt Template:**
```
[Style]
Latin American football barra chant
Tempo: 120 BPM, march rhythm
Instruments: Bombo drums, brass section, crowd vocals
Energy: Building from calm to triumphant

[Lyrics - Spanish]
Verse 1:
De las montañas del Táchira viene
Un guerrero con balón en los pies
Santi lucha, Santi sueña
¡Venezuela lo verá crecer!

Coro:
¡Dale Santi, dale Santi!
Con [PATROCINADOR] vamos adelante
La cancha es nuestra catedral
¡Tu sueño no tiene final!

[Instructions]
- Strong drum emphasis on "Dale Santi"
- Crowd join on chorus
- Insert sponsor name naturally in rhythm
```

### Sponsor Personalization
Create base track, then generate variations:
- Version A: "[Empresa X] nos apoya"
- Version B: "Gracias [Empresa Y]"
- Generic: "Nuestros patrocinadores"

---

## 📝 Text & Copy

### Campaign Messaging Generator

**For WhatsApp Outreach:**
```
Context: Cold outreach to local business owner in Táchira
Tone: Warm, professional, community-focused
Language: Venezuelan Spanish
Length: Under 100 words

Generate: Initial message introducing sponsorship opportunity
Include: Brief hook, value proposition, single question
```

**For Social Posts:**
```
Platform: Instagram
Audience: Táchira community
Content: Photo of Santi training
Goal: Build emotional connection
Include: Venezuelan expressions, football passion
```

---

## 🎬 Video Scripts

**Hero Video Structure:**
```
Generate 90-second video script:
- Opening: Dramatic hook (5 sec visual, 10 sec story setup)
- Act 1: Origin in San Cristóbal (20 sec)
- Act 2: The challenge - economic barriers (20 sec)  
- Act 3: The invitation - join his journey (20 sec)
- Closing: Clear call to action (15 sec)

Voice: Narrator or player direct-to-camera
Music: Builds from reflective to triumphant
```

---

## 🔧 Workflow Tips

1. **Batch process** - Enhance all photos in one session for consistency
2. **Save prompts** - Keep successful prompts in `docs/templates/ai-prompts.md`
3. **Iterate quickly** - Generate 3-4 versions, pick best
4. **Human review** - Always verify AI output feels authentic

---

## Quick Commands

```bash
# Photo enhancement session
# 1. Upload originals to Nano Banana Pro
# 2. Use style prompt for consistency
# 3. Export to assets/photos/enhanced/

# Music generation session  
# 1. Use master prompt in Suno/Udio
# 2. Generate 3 variations
# 3. Pick best, save to assets/music/

# Video creation
# 1. Compile enhanced photos + music
# 2. Use FlexClip or local editor
# 3. Export to assets/videos/
```
