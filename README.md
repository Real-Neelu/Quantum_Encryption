# Quantum_Encryption
"Installing dependencies"
pip install numpy

"Logic"
Alice prepares 1000 random bits and bases
Bob measures with his own bases
Eve (if enabled) intercepts some photons and introduces errors
Alice & Bob keep only same-basis bits
A portion is checked for QBER
QBER ≤ 11% → Secure key
QBER > 11% → Eavesdropper detected
