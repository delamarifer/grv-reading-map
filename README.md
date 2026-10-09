# Gender, Respect, and Violence: Reading and Discussion Map

A shared sticky-note board for each of the nine modules. Hosted on GitHub Pages, notes stored in Firebase Firestore.

The syllabus (`syllabus.enc.json`) and every note, reply and name are encrypted in the browser (AES-GCM, key from the group passphrase via PBKDF2). This repository and the database only ever hold ciphertext. Card positions, colours and links are not encrypted.

Anyone who finds the site can see that it exists, and someone with the Firebase config could delete or scramble cards, but cannot read them without the passphrase.
