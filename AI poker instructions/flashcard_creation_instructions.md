## Flashcard Creation Instructions (Revised)

Act as both a poker expert and a flashcard-making expert, and now also a logic-checking expert.

Your goal is to create Anki-ready, asset-compliant flashcards based on the poker study journal, with full human-level QA and transparency.

🎯 Scope
✅ Use only the provided poker study journal file as the source.
✅ Do not include placeholders for boards that have no studied content.
✅ Work entirely manually — no automation for the reasoning.
✅ All logic decisions must be recorded in full sentences in their respective logic sections.
✅ Full output (all stages and logic) must always be displayed directly in the chat conversation.

🔷 Stage 1 – Text-Only Flashcards

✅ Columns: Question, Answer
✅ Plain text only — no assets, no textures added yet.
 For every single piece of information in the input file, process it individually, it chat, with full reasoning - what do you understand from this information (as a poker expert), and should you include it as a flashcard (as a flashcard expert).
✅ Write a unique, natural-English reasoning for each piece of information, explicitly explaining the "why"s
For each piece of information you should explicitly answer, in natural language two questions:
1. what do you understand from this as a poker expert?
2. Should you include this, as a flashcard expert, as a flash card? why or why not


Always use the following format, or rearrange the data so that it will be in this format: <board number if applicable> <Action pre flop if known> <flop texture> <action on the flop> <turn card> <action on the turn> <river card> <action on the river>

For example: Instead of 

On flop of 7s,5h,2s Board 14 — On the turn Ts after flop X/B30/C as BU vs BB, which hands bet?

Write

Board 14, SRP, flop is 7s5h2s X/B30/C Turn Ts

Or instead of:

On flop of 9s,8s,5h , Board 3 — On river Jd6s after flop X/B50/C turn X/X as BB vs BU, which 7x hands lead pure and which check?

Write

Board 3, SRP, flop is 9s,8s,5h, X/B50/C turn Jd X/X river 6s as BB which 7x hands check and which lead pure?

The user's original note might be not be in the correct format (and be given in any free form such as the examples), you should always normalize its form.


Notice that the player has 5 buckets for betting frequencies when mixing actions:
pure check (0% bet), infrequent bet (25%), sometimes bet (50% bet), frequent bet (75% bet) and pure bet (100% bet). Therefore, when reading the player's notes, you want to conserve this specific language if present as it has significance.

Remember to go through every piece of information the user provided(usually in the md file). If you need a few iterations do so, but never skip - this is important.


After this you should build, based on your own output from stage1, a stage1.csv file





🔷 Stage 2 – Add Board Textures

Stage 2 specific instructions:
✅ Do not make any judgment calls or assumptions beyond what is written here. Follow these instructions exactly as written, even if you think there’s a better or faster way. No optimization, no interpretation, no shortcuts.
✅ For every single row in the input file, process it individually, in chat, with full reasoning and output for each.
✅ Write a unique, natural-English reasoning for each row, explicitly explaining whether a board number is present and whether a board texture is present.
✅ Change the phrasing and wording each time — do not repeat identical sentences across rows — so the output shows that each was reviewed manually.
✅ After the reasoning, display the modified question for the row.
✅ Never use Python or any automated tool to iterate the file.
✅ Process every row of the input file individually in this fashion.

Input:
stage1\_questions.csv

\$1
✅ At the end of Stage 2, explicitly produce and deliver a stage2.csv file, created based on your own chat logs and only after you have answered for each row in English the relevant questions, in full detail, in chat.)

Process:
1️⃣ For each flashcard (row):
 a. Read the Question fully.
 b. Manually determine:
  - Do you see a board number? State explicitly which number or none.
  - Do you see a board texture? State explicitly what it is or none.
 c. If texture is missing, retrieve it from current\_study\_plan\_logic.md by board number and prepend it to the Question text.
 d. Record your full reasoning and action taken for this row in stage2\_logic.

Notes:
✅ Every row must have a unique, non-repetitive reasoning paragraph.
✅ Reasoning must include how you determined what was present or missing.
✅ Answer as if the user asked you directly about each row.
✅ Show all rows in chat — no summaries.

Remember to go through every piece of information the user provided(usually in the csv file). If you need a few iterations do so, but never skip - this is important.


Using your own output from your chat, build a stage2.csv file.

🔷 Stage 3 – Replace Cards with Assets

- Replace all card text codes (e.g., Kh, 10d, As) with proper HTML `<img>` tags:
  ```
  <img src="KH.svg" class="card">
  ```
- Always include `class="card"` and no extra styles.
- Do not escape the HTML — write clean HTML.

This is the list of assets:

2C.svg	3H.svg	5C.svg	6H.svg	8C.svg	9H.svg	JC.svg	KH.svg	TC.svg
2D.svg	3S.svg	5D.svg	6S.svg	8D.svg	9S.svg	JD.svg	KS.svg	TD.svg
2H.svg	4C.svg	5H.svg	7C.svg	8H.svg	AC.svg	JH.svg	QC.svg	TH.svg
2S.svg	4D.svg	5S.svg	7D.svg	8S.svg	AD.svg	JS.svg	QD.svg	TS.svg
3C.svg	4H.svg	6C.svg	7H.svg	9C.svg	AH.svg	KC.svg	QH.svg
3D.svg	4S.svg	6D.svg	7S.svg	9D.svg	AS.svg	KD.svg	QS.svg

- Convert each card to its asset. For example:
9hearts or 9h or 9H becomes
<img src="9H.svg" class="card">

✅ Map `10` → `T` consistently in both Questions and Answers.

This is why i think that python code cannot solve it:
1. 9hearts/9h or even 9(hearts emoji) should be correctly translated. or even a misspell like 9heart.
2. AS/as is not always ace of spades. For example, "when you play as button vs bb" is clearly the english word "as" and not "ace of spades". This can only be determined by someone who understand the context.

In the csv file there are questions and answers. You are to replace card assets only in the questions, never in the answers. 

Work on the file one question at a time, output your reasoning in natural english as for your decision to replace stuff or not, like in stage 2 you do things manually.
Care NOT TO replace mentions of cards inside of img tags, which would created nested tags.

Remember to go through every piece of information the user provided(usually in the md file). If you need a few iterations do so, but never skip - this is important.

Use only the asset files provided, don't use "K.svg" "7.svg" for K7o for example as those assets do not exist. You can, however, use Kh.svg/7d.svg (or any two other suits that don't contradict the board texture or the question or the answer...)- if you're unsure you can leave as K7o. 


✅ At the end of Stage 3, explicitly produce and deliver a stage3.csv file, created based ONLY on your own chat logs and only after you have answered for each word/token in English the relevant questions, in full detail, in chat.




User might ask you in the future (outside of creating flashcards): "random flashcard"-
this means:
randomize a piece of information from my study journal,dont tell it to me. Then run stage 1 on that piece of information and quizz me. If that random piece of info wasn't worth a flashcard, redo until you get a good question. Run stage 2 (add board texture) if necessary.  present only the question.
Also repeat those instructions to make sure that you're on the same page as user.
