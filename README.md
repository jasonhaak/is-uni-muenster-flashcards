# Anki Flashcards – Information Systems Master @ University of Münster
[![en](https://img.shields.io/badge/Language-en-green.svg)](https://github.com/jasonhaak/is-uni-muenster-flashcards/blob/main/README.md)
[![de](https://img.shields.io/badge/Language-de-red.svg)](https://github.com/jasonhaak/is-uni-muenster-flashcards/blob/main/README-de.md)

Welcome to this repository containing Anki flashcards for the Master in Information Systems at the University of Münster.

> Note: All flashcards are written in German. Specific terms may appear in English, but explanations, definitions and context are provided in German.

> Note: Some flashcards may appear in multiple decks, as the organization is based on categories rather than individual courses. As a result, a card might be included in both _Course 1_ and _Course 2_. This structure may also lead to the inclusion of supplementary material from other courses within a given deck.

## Table of Contents
1. [Purpose of This Repository](#purpose-of-this-repository)
2. [Included Modules](#included-modules)
3. [How to Use](#how-to-use)
4. [Contact & Support](#contact--support)
5. [Donations](#donations)
6. [How to Contribute](#how-to-contribute)
7. [Author & Licence](#author--licence)

## Purpose of This Repository
This repository provides a comprehensive set of Anki flashcards that include:
- Definitions and key concepts from official lecture scripts
- Examples, explanations, and application-based tasks
- Past exam questions with solutions
- Additional material from textbooks and other academic sources

## Included Modules
- **BPM3:** Enterprise Architecture Management (SS 25) – Kalla  
- **MDB3:** Network Economics (SS 25) – Haines  
- **MDB5:** Digital Innovation and Sustainable Development (SS 25) – Püchel  
- **MDB6:** Strategic IT/IS Management & Cases (SS 25) – Teubner  

## How to Use
1. Download and install [Anki](https://apps.ankiweb.net/)
2. Download the relevant `.apkg` file(s) from this repository
3. Import the deck into Anki via *File → Import* or drag and drop

## Contact & Support
For questions, suggestions, or corrections: Open an [issue](https://github.com/jasonhaak/is-uni-muenster-flashcards/issues) or submit a Pull Request.

## Donations
If you find these flashcards helpful and want to buy me a coffee, you can donate me via PayPal:

<a href="https://www.paypal.com/paypalme/jasonhaak01">
  <img src="https://raw.githubusercontent.com/stefan-niedermann/paypal-donate-button/master/paypal-donate-button.png" alt="Donate with PayPal" height="80"/>
</a>

## How to Contribute
While contributions are welcome, this repository is not actively maintained. I will review and merge fixes, but do not guarantee ongoing support. If you want to contribute flashcards, corrections or improvements, please follow this workflow to ensure consistency.

### Step-by-Step Contribution Guide
1. Fork this repository
2. Clone your fork locally
3. Create or update flashcards in Anki as needed
4. Export your deck twice:
   - As `.apkg` (anki card package, without scheduling information, but including media)
   - As `.txt` using the notes export option:
     - Export format: Notes with unformatted text (.txt)
     - Settings: Include HTML and media file references
5. Create a new folder named as `MODULE-SEMESTER` (e.g., `BWL3-WS-23-24`)
6. Place your exported CrowdAnki files and the APKG file in this folder
7. Edit this README.md and add your lecture
8. Commit your changes with a clear message
9. Push to your fork and open a Pull Request against this repository

### Version Control and File Format
- Do not commit a `.apkg` files (binary, not diff-friendly) without using the `.txt` for version control
- Use the exported `.txt` as the primary source tracked in Git
- Track only the `.txt` for clear version history

## Author & Licence
This flashcards were written by Jason Haak and are licensed under the Creative Commons Attribution-NonCommercial 4.0 International.
