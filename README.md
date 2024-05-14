
# Spelling Correction System
## Overview
This Python script provides a basic spelling correction system. It uses a probabilistic model to suggest the most likely correct spelling for a given word based on a pre-defined dictionary. The correction process involves generating potential corrections for a misspelled word and then selecting the correction with the highest probability.

## Setup
Ensure you have Python installed on your system. This script requires the re (Regular Expression) and collections modules, which are included in the Python standard library.

## Usage
Clone or download the repository containing the script.
Ensure that your input files (sherlock.txt, test.txt, aspell.txt, big.txt, birkbeck.txt, spell-testset1.txt, spell-testset2.txt, wikipedia.txt) are placed in the appropriate directory or update the file paths in the script accordingly.
Run the script using a Python interpreter. It will execute the spelling correction process on the provided test sets and generate a file named corrected_test containing the corrected text.
## Functions
correction(word): Returns the most probable correction for a given misspelled word.
candidates(word): Generates potential corrections for a misspelled word.
known(words): Filters out known words from a list of words.
edits1(word): Generates all possible edits that are one edit away from a word.
edits2(word): Generates all possible edits that are two edits away from a word.
run_tests(): Runs test cases to validate the correction function.
test_correction(input_word, expected_correction): Tests the correction function against expected results.
