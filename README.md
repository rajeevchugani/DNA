# DNA Explorer

An interactive website for teaching DNA structure, DNA vs RNA, transcription and translation (Year 7 up to roughly IGCSE level). It is a single self-contained file that works offline in any modern browser, on a computer, tablet or phone.

## How to open it
1. Unzip the folder.
2. Double-click `index.html`. No installation, internet connection or login is needed.
3. To share it, give students the `index.html` file or upload it to your school site or learning platform.

## What is in each tab

| Tab | What students do |
|---|---|
| **Helix** | Click the helix or drag the slider to unwind it into a flat ladder. Complementary base pairs, hydrogen bonds and the antiparallel 5′ and 3′ ends are shown. Click a label to spotlight one part (phosphate, deoxyribose, bases, bonds). |
| **History** | A timeline from the first clues to the double helix. Explore Photo 51 (Rosalind Franklin) and Chargaff's rules. |
| **Nucleotide & bonds** | Click any part or bond of a nucleotide to learn about it. Solid lines are covalent bonds. Turn on "Show atoms" to see the carbon numbers. |
| **Build puzzle** | Drag bases (or tap a slot, then a base) to build the complementary strand. Wrong answers are explained. |
| **Assemble** | Drag the phosphate, sugar and base onto the matching spots to build a nucleotide. Some pieces belong to RNA only. |
| **Sandbox** | Free play. Drag nucleotides onto the canvas, join them into strands and pair strands. Select a strand to flip, break apart or delete it. |
| **Spot the mistake** | A DNA ladder with 3 hidden errors chosen at random from: wrong complementary base, U in DNA, missing phosphate, a sugar facing the wrong way, a base bonded to the wrong carbon of the sugar, covalent bonds drawn between paired bases, hydrogen bonds drawn in the backbone, or strands not antiparallel. Tap the mistakes, press Check, and read the explanations. A hint button and unlimited new puzzles are included. |
| **DNA vs RNA** | Compare sugar, strands, bases, length, location and job, then play a sorting game (DNA, RNA or both). |
| **Transcription** | RNA polymerase unzips the gene. Students choose the RNA base that pairs with each template base to build the mRNA, then release it. A pairing key is available. |
| **Translation** | Follow the mRNA out of the nucleus through a nuclear pore to a ribosome. Choose the tRNA whose anticodon is complementary to each codon. Watch the ribosome move along the mRNA, the tRNA bind by base pairing, and peptide bonds join the amino acids until a stop codon releases the protein. A slider under the diagram lets you move the ribosome along the mRNA to show earlier steps, and "Play it for me" runs the whole process automatically. |
| **Decode it** | (1) Convert between a DNA template and mRNA. (2) Starting from a DNA template or an mRNA, fill in the blanks for the other strand, the tRNA anticodons and the amino acids, using the full codon table (3-letter abbreviations shown). |
| **Test mode** | A 10-question quiz mixing multiple choice and click-the-part questions on structure, bonding, history, RNA, transcription and translation. |

## Teaching tips
- **Starter:** open the Helix tab on the board and unwind it. Ask students to predict the partner base before clicking.
- **Pairs or independent work:** Build puzzle, Spot the mistake and Decode it work well as quick checks. Every task can be repeated with new random sequences.
- **Demonstrating translation:** use the position slider and "Play it for me" to show the ribosome moving along the mRNA, and point out the anticodon and codon hydrogen bonds and the peptide bonds.
- **Revision:** Test mode gives a different set of questions each time.

## Key facts the site teaches
- DNA pairs A with T (2 hydrogen bonds) and G with C (3). The two strands run in opposite directions (antiparallel).
- Covalent bonds hold each strand together (the sugar–phosphate backbone). Hydrogen bonds hold the two strands together.
- RNA is single stranded, has ribose and uses U instead of T.
- Transcription copies a gene into mRNA in the nucleus. The mRNA (not the DNA) leaves through a nuclear pore.
- Translation happens at a ribosome. Each tRNA's anticodon pairs with an mRNA codon and carries one amino acid. Amino acids join by peptide bonds until a stop codon.

## Notes
- Student work is not saved. Refreshing the page starts everything over.
- Google Analytics (tag G-MMCRQ7R1VM) is included in the `<head>` of `index.html` to measure visits. It only reports when the page is opened online. Remove that block if you don't want it.
- Works best in a current version of Chrome, Edge, Safari or Firefox.
- Dark theme is the default, with a Light/Dark switch in the top right. The choice is remembered on that device.
- Fonts (loaded from Google Fonts when online, with system fonts as a fallback): Bricolage Grotesque (headings), DM Sans (body text), DM Mono (labels and numbers).
- Right and wrong answers always show a tick or cross as well as colour (lime or green for right, orange for wrong).


## Added in this version
- **Grouped, numbered tabs** (1 Learn, 2 Practise, 3 DNA to protein, 4 Test yourself), a **Next** button at the bottom of each tab, and a tick on tabs already visited (remembered in the browser).
- **← Science Revision Hub** link at the top and on the Test mode score screen.
- **DNA replication** tab: helicase unzips the DNA, then students pick the complementary bases that DNA polymerase adds to each template strand, ending with two identical molecules (semi-conservative).
- **Purines & pyrimidines** tab with a short sorting quiz.
- **Test mode**: topic filter (All, History, Structure, RNA & protein, Replication), per-topic missed list and **Review missed**, plus more questions.
- **Spot the mistake** works with the keyboard: Tab to a part, press Enter or Space to mark it.
- Wide diagrams scroll sideways on phones (swipe hint shown).
