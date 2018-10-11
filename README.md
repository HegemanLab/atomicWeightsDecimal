# atomicWeightsDecimal

A Python dictionary of atomic weights in Python Decimal objects.

Atomic weight measurements come from IUPAC's **Atomic Weights of the Elements: Review 2000**. Standard weights are from Table 3. Most-abundant isotope weights are from Part 2.

## Implementation

Per IUPAC, only elements with stable isotopes are included.

Chemical elements can be called from the dictionary using the element's chemical symbol (e.g., `"H"`) as a key which returns a dictionary of weights. The dictionary of weights consists of (1) standard weight with the key`standard` and (2) most-abundant isotope weight with the key `abundant`.

All weights, except for <sup>12</sup>C, are stored as Python Decimal objects. Decimal objects are useful for significance arithmetic.

<sup>12</sup>C is the scale-determining reference for atomic measurements and is exactly `12`. atomicWeightsDecimal stores <sup>12</sup>C as `int(12)`. Mixing Decimal and integer objects is acceptable and desirable, because arithemtic between the two does not degrade measurement resolution and <sup>12</sup>C has infinite resolution.

Tab characters are used as whitespace in the dictionary to simplify regex manipulation.

A for loop iterates through all chemical element's weights.

## Caution

Care should be taken when applying these measurements. Standard weights may not be applicable to high-resolution mass spectrometry. Some elements have multiple stable isotopes with similar relative abundances. For  instance, 50.69% of Bromine is <sup>79</sup>Br and the other 49.31% is <sup>81</sup>Br. Chlorine's isotope abundances are particularily relevant to biochemists: 75.76% <sup>35</sup>Cl (`34.9688527 71 Da`) and 24.24% <sup>37</sup>Cl (`36.96590260 Da`).
