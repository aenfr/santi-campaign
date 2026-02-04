---
description: 'Execute the Santi Sponsorship Campaign - from asset creation through sponsor outreach'
---

# Santi Sponsorship Campaign Workflow

This workflow guides the creation and execution of a sponsorship campaign for a youth football player.

## Prerequisites
- Photos of the player in action (stored in `assets/photos/`)
- Player information filled in `docs/narrative/historia-de-santi.md`
- Access to AI tools (Nano Banana Pro, music generator)

---

## Phase 1: Story Development

### Step 1.1: Personalize the Narrative
1. Open `docs/narrative/historia-de-santi.md`
2. Replace all `[BRACKETED PLACEHOLDERS]` with real information:
   - Player's real name
   - Club name  
   - Contact information
3. Review emotional arc - does it tell his story authentically?

### Step 1.2: Gather Player Insights
Interview the player (or family) for:
- What does football mean to him?
- What's his biggest challenge?
- What's his dream?
- A memorable moment on the field

Add these personal touches to the narrative.

---

## Phase 2: Visual Asset Enhancement

### Step 2.1: Photo Selection
1. Review all available photos in `assets/photos/`
2. Select 5-7 strongest action shots
3. Categorize by: Action, Emotion, Team, Portrait

### Step 2.2: AI Enhancement with Nano Banana Pro
For each selected photo:
// turbo
1. Upload to Nano Banana Pro
2. Generate alternate angles (front, side, dynamic)
3. Create consistent "campaign look" - same lighting/style
4. Export in formats:
   - Social media (1080x1080, 1080x1920)
   - Print (high resolution)
   - Video thumbnail (16:9)

### Step 2.3: Animation (Optional)
Use Nano Banana Video or RunwayML to:
1. Create 2-3 second motion clips from still photos
2. Add subtle movement (wind, dust particles)
3. Export as GIF and MP4

---

## Phase 3: Video Production

### Step 3.1: Hero Video (60-90 seconds)
Structure:
```
[0-15s] Hook - Dramatic action shot, music builds
[15-35s] Origin - His story, where he comes from
[35-50s] Challenge - What stands in his way
[50-70s] Invitation - How sponsors become part of the story
[70-90s] Call to Action - How to get involved
```

### Step 3.2: Sponsor Pitch (30 seconds)
Quick, professional pitch for businesses:
- What sponsorship offers them
- Community impact
- How to participate

### Step 3.3: Thank You Templates
Create video templates for:
- New sponsor welcome
- Monthly update
- Goal/achievement celebration

---

## Phase 4: Barra Music Creation

### Step 4.1: Compose the Anthem
Use AI music generator (Suno, Udio, or similar):

**Prompt template:**
```
Create a football stadium chant in Latin American barra style.
Tempo: energetic, march-like
Instruments: bombo drums, brass, crowd vocals
Mood: triumphant, passionate, community pride
Language: Spanish (Venezuelan)
Theme: Supporting young player "Santi" and naming sponsors

Lyrics to include:
- "¡Dale Santi!" (Go Santi!)
- "[SPONSOR NAME] nos apoya" (Sponsor supports us)
- "Táchira presente" (Táchira is here)
```

### Step 4.2: Create Sponsor Variations
Generate versions with different sponsor names inserted.
Each sponsor gets their own personalized version.

---

## Phase 5: Sponsor Outreach

### Step 5.1: Target List
Create spreadsheet in `docs/sponsors/target-list.xlsx`:
| Business | Contact | Type | Priority | Status |
|----------|---------|------|----------|--------|
| [Name] | [Email/Phone] | [Industry] | [High/Med] | [Pending] |

### Step 5.2: Outreach Sequence

**Day 1: Initial Contact**
- WhatsApp message with 15-sec video teaser
- Brief intro: "Tenemos una propuesta especial para [BUSINESS]..."

**Day 3: Follow-up**  
- Send full campaign video
- Include sponsor tier options

**Day 7: Personal Touch**
- Voice note or call
- Offer in-person meeting

**Day 14: Proposal**
- Custom proposal document
- Specific tier recommendation

### Step 5.3: Closing
- Prepare simple agreement template
- Define payment methods (bank, mobile, etc.)
- Set up recognition delivery timeline

---

## Phase 6: Recognition Delivery

### Step 6.1: Immediate
Within 48 hours of sponsorship:
- Personalized thank you video from Santi
- Welcome post on social media
- Certificate of sponsorship

### Step 6.2: Ongoing
Monthly:
- Progress update with photos
- Training/match highlights
- Sponsor mention in content

### Step 6.3: Special
For Campeón tier:
- Barra anthem version with their name
- Jersey photo opportunity
- Featured video testimonial

---

## Folder Structure

```
Santi Donation/
├── assets/
│   ├── photos/
│   │   ├── original/
│   │   └── enhanced/
│   ├── videos/
│   └── music/
├── docs/
│   ├── narrative/
│   │   └── historia-de-santi.md
│   ├── sponsors/
│   │   ├── target-list.xlsx
│   │   └── proposals/
│   └── templates/
└── output/
    ├── social/
    └── print/
```

---

## Success Metrics

Track and celebrate:
- [ ] Number of sponsors acquired
- [ ] Total monthly support secured
- [ ] Social media engagement
- [ ] Video views
- [ ] Sponsor retention rate
