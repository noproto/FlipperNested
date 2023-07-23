# TODO:

1. Review Nested and Hardnested literature (http://www.proxmark.org/files/Documents/13.56%20MHz%20-%20MIFARE%20Classic/) as well as code (https://github.com/nfc-tools/mfoc, https://github.com/nfc-tools/mfoc-hardnested)
2. Review limitations of FZ NFC hardware
3. Review parity implementation, update Crypto1/Crapto1 to optimized equivalents
4. Remove code writing to SD when possible (queue keys)
5. Port nonce cracking (mfcuk/Darkside) from Mfkey32 (https://github.com/noproto/FlipperMfkey)
6. Fix alleged PRNG timing issue
7. Reduce the number of statelists from 2 to 0: Neither mfoc nor mfoc-hardnested use 2 states, seems to be an optimization that is not required

Original:

# TODO:

1. Better (faster) detection of delay in a nested attack
