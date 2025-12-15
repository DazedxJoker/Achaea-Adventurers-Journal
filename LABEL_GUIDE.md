# 🏷️ Label Guide for Achaea Journal Database

## How Labeling Works

Just add labels to GitHub issues - the website automatically filters by them!

---

## Label Categories

### 📍 Area Labels (format: `area-name`)

**Cities:**
- `area-mhaldor`
- `area-ashtan`
- `area-cyrene`
- `area-hashan`
- `area-eleusis`
- `area-targossas`

**Regions:**
- `area-moghedu`
- `area-azdun`
- `area-manara`
- `area-delos`
- `area-underworld`
- `area-black-forest`
- `area-aalen`
- `area-dun-valley`
- `area-new-thera`

**Continents:**
- `area-meropis`
- `area-sapience`

**Ocean/Islands:**
- `area-ocean`
- `area-ulangi`
- `area-mysia`

**Multiple Areas:**
Just add multiple labels! Example:
- `area-mhaldor` + `area-dun-valley` for a quest spanning both

### 🎯 Quest Numbers (format: `quest-###`)

Link to Achaea's quest system:
- `quest-123`
- `quest-456`

Website can filter by quest number!

### 🗡️ Quest Types (format: `type-name`)

- `type-combat` - Fighting/killing
- `type-delivery` - Deliver items
- `type-gather` - Collect items
- `type-rescue` - Save someone
- `type-escort` - Protect/guide NPCs
- `type-puzzle` - Riddles/brain teasers
- `type-exploration` - Find locations

### ✅ Status

- `solved` - Quest completed (or just close the issue!)
- `help-needed` - Stuck on this one
- `difficult` - Hard quest
- `easy` - Simple quest
- `newbie-friendly` - Good for beginners

---

## How to Add Labels

### Method 1: On GitHub (Easy)

1. Go to issue: https://github.com/DazedxJoker/Achaea-Adventurers-Journal/issues
2. Click an issue
3. On the right sidebar, click **Labels**
4. Type label name (e.g., `area-moghedu`)
5. If it doesn't exist, click **"Create new label"**
6. Done! Website updates automatically

### Method 2: When Creating Labels

**Create labels once, reuse forever:**

1. Go to: https://github.com/DazedxJoker/Achaea-Adventurers-Journal/labels
2. Click **"New label"**
3. Name: `area-moghedu`
4. Color: Pick a color (blue for areas, purple for quests, etc.)
5. Click **"Create label"**

Now you can use it on any issue!

---

## Quick Setup: Pre-Make Common Labels

Go to Labels page and create these:

**Areas (Blue #1f6feb):**
```
area-mhaldor
area-moghedu
area-azdun
area-manara
area-delos
area-cyrene
area-ashtan
```

**Quest Types (Red #f78166):**
```
type-combat
type-delivery
type-gather
type-puzzle
```

**Status (Green #3fb950 / Yellow #d4a72c):**
```
solved
help-needed
easy
difficult
```

---

## Website Features

### Filter by Area

Dropdown shows all areas with entry counts:
```
Moghedu (15)
Azdun (8)
Mhaldor (23)
```

### Filter by Multiple Labels

Click labels in the cloud to combine filters:
- Click `type-combat` + `area-moghedu` = Combat quests in Moghedu only

### Search Quest Numbers

Type quest number in filter:
```
Quest Number: 123
```

Shows all hints related to quest #123

---

## Example Workflow

**New journal entry captured:**

1. Entry appears on GitHub as issue
2. You open the issue
3. Add labels:
   - `area-moghedu` (quest is in Moghedu)
   - `quest-789` (it's quest #789 in-game)
   - `type-combat` (involves fighting)

4. Website now shows:
   - Under "Moghedu" filter
   - Under "combat" type
   - Searchable by "quest-789"

**Quest solved:**

1. Close the issue on GitHub
2. Website shows ✓ Solved badge
3. Still searchable for reference!

---

## Tips

### Multi-Area Quests

Add ALL areas the quest touches:
```
area-mhaldor
area-dun-valley
area-black-forest
```

Website can filter by any of them!

### Quest Chains

Use labels to connect related quests:
```
quest-series-dragon
quest-789
quest-790
quest-791
```

### Difficulty

Help new players:
```
newbie-friendly
easy
area-manara
```

### Organize by Race

```
type-grook
type-tsolaa
type-dragon
```

---

## Color Coding Suggestions

- **Blue (#1f6feb):** Areas
- **Purple (#a371f7):** Quest numbers
- **Red (#f78166):** Quest types
- **Green (#3fb950):** Solved/easy
- **Yellow (#d4a72c):** Help needed/difficult

---

## Advanced: Label Templates

Create labels in bulk:

1. Go to repo Settings → Labels
2. Delete default labels if you want
3. Add your custom set

Or use GitHub CLI:
```bash
gh label create "area-moghedu" --color 1f6feb
gh label create "area-mhaldor" --color 1f6feb
gh label create "type-combat" --color f78166
```

---

## The Beauty of This System

✅ **No coding** - Just add labels on GitHub
✅ **Instant updates** - Website reads labels automatically
✅ **Flexible** - Create any labels you want
✅ **Multiple labels** - Quest can have many areas/types
✅ **Searchable** - GitHub and website both search labels
✅ **Community driven** - Anyone can add/suggest labels

---

## Example: Fully Labeled Entry

**Issue Title:**
`[2024-12-08] PlayerName - Quest #123 - Seek the hermit in...`

**Labels:**
- `journal-entry` (auto)
- `2024-12-08` (auto)
- `area-black-forest` (manual)
- `area-dun-valley` (manual)
- `quest-123` (manual)
- `type-delivery` (manual)
- `newbie-friendly` (manual)

**Result on Website:**
- Appears in "Black Forest" filter
- Appears in "Dun Valley" filter
- Shows "Quest #123"
- Tagged as "delivery" type
- Marked "newbie-friendly"

Perfect organization with zero programming! 🎉
