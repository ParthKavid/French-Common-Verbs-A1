# 📚 French-Common-Verbs-A1-Level

Start Practice: https://mrbitbcoder.github.io/French-Common-Verbs-A1/


A comprehensive verb practice app for A1 Level French learners.

## 🎮 App Features (4 Modes)

| Mode                        | Sub-mode / Feature | What it does                                                                                                                                                                 |
| --------------------------- | ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 💪 **Conjugation Drills**   | 📋 Sequential Mode | Practice one verb with all 6 pronouns; checklist shows progress; finish all pronouns to earn +1 count; option to skip verb; celebration when completed                       |
|                             | 🎲 Random Mode     | Random verb + pronoun each round; no need to finish full set; fast variety practice; still tracks mistakes and accuracy                                                      |
| ❗ **Mistake Review**        | Error Tracking     | Lists verbs with mistakes; grouped by verb and mistake count; shows recent wrong vs correct answers; practice weak verbs button; clear history; sorts by most mistakes first |
| 📚 **Reference Table**      | Mastery Indicators | 🔴 Not practiced (0); 🟡 Learning (1–2); 🟢 Mastered (3+)                                                                                                                    |
|                             | Table Features     | Full conjugation table (70+ verbs); all pronouns shown; 6 categories; live search; sticky headers; hover shows completion count                                              |
| 🌍 **Translation Practice** | Sentence Practice  | English → French conjugation; random verb + pronoun; accepts full phrase or verb only; tracks accuracy; auto-advances after correct answer                                   |


*All practice focuses on the present tense.*

---

## Local testing & deployment (added)

Quick local test (choose one):

1) Python 3

```powershell
cd /d D:\Coding\French-Common-Verbs-A1
python -m http.server 8000
# open http://localhost:8000
```

If `python` isn't on PATH, try `py -3 -m http.server 8000`.

2) Node (npx)

```powershell
npx http-server -p 8000
# or
npx serve -p 8000
```

3) VS Code Live Server extension — click "Go Live".

### Verify
- `Total Verbs` stat shows verbs count from `verbs.json`.
- Conjugation drills, random mode, translation, and reference table should function.
- Check DevTools Console for fetch errors if verbs don't load.

## `verbs.json` template

Edit `verbs.json` at project root. Keep structure exactly as shown:

```json
{
	"categoryName": [
		{
			"infinitive": "parler",
			"english": "to speak",
			"conjugations": {
				"je": "parle",
				"tu": "parles",
				"il": "parle",
				"nous": "parlons",
				"vous": "parlez",
				"ils": "parlent"
			}
		}
	]
}
```

Filenames are case-sensitive on GitHub Pages — make sure `verbs.json` is exactly that.

If you'd like, I can populate `verbs.json` with more verbs (e.g., +100 or +500). Tell me how many and any preferred categories.

## 📖 French Verbs Included

### ⭐ 1. Essential Verbs (MOST IMPORTANT)
*Learn these first:*
- être → to be
- avoir → to have
- aller → to go
- faire → to do/make
- dire → to say
- pouvoir → can/may
- vouloir → to want
- devoir → must / have to
- prendre → to take
- mettre → to put
- donner → to give
- trouver → to find

### 🏠 2. Daily Routine Verbs
*Used for everyday life:*
- manger → to eat
- boire → to drink
- dormir → to sleep
- se lever → to wake up
- se coucher → to go to bed
- travailler → to work
- étudier → to study
- habiter → to live
- rentrer → to return home
- sortir → to go out

### 🗣️ 3. Communication Verbs
*For speaking and learning:*
- parler → to speak
- dire → to say
- demander → to ask
- répondre → to answer
- écouter → to listen
- regarder → to watch
- lire → to read
- écrire → to write
- apprendre → to learn
- comprendre → to understand

### 🚶 4. Movement & Travel Verbs
*Very common in conversations:*
- venir → to come
- partir → to leave
- arriver → to arrive
- entrer → to enter
- rester → to stay
- monter → to go up
- descendre → to go down
- marcher → to walk
- voyager → to travel

### ❤️ 5. Feelings & Preferences
*Needed to talk about yourself:*
- aimer → to like/love
- adorer → to love
- préférer → to prefer
- détester → to hate
- penser → to think
- croire → to believe
- espérer → to hope

### 🎯 6. Common Regular Verbs (-ER group)
*These follow the same pattern (easy!):*
- jouer → to play
- acheter → to buy
- chercher → to look for
- visiter → to visit
- rencontrer → to meet
- préparer → to prepare
- cuisiner → to cook
- nettoyer → to clean

---
