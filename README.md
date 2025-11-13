This script is developed for educational and research purposes only.

By using this code, you agree to the following:

    You will not use this code, in whole or in part, for malicious intent, including but not limited to unauthorized mining on third-party systems.
    You will seek explicit permission from any and all system owners before running or deploying this code.
    You understand the implications of running mining software on hardware, including the potential for increased wear and power consumption.
    The creator of this script cannot and will not be held responsible for any damages, repercussions, or any negative outcomes that result from using this script.

If you do not agree to these terms, please do not use or distribute this code.
How it works?

We'll begin by delving into the foundational concepts. Upon establishing a wallet through platforms like Exodus/TrustWallet or similar services, users receive a mnemonic phrase (seed-phrase) comprised of 12 unique words. The selection of words for this passphrase isn't arbitrary; they are derived from a specific lexicon containing 2048 potential words. From this collection, the passphrase words are selected at random (the entire list of these words is accessible HERE). Utilizing this passphrase, an individual has the capability to access their wallet on any device and manage their assets. My application operates by employing brute force techniques to decipher these passphrases.

If EnigmaCracker finds a wallet with a balance, it will create wallets_with_balance.txt file that will contain the info of the discovered wallet.

Upon execution, EnigmaCracker generates a comprehensive log file named enigmacracker.log, which neatly records the entire session history for review and analysis.
