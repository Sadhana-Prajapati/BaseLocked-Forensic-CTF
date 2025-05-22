# BaseLocked-Forensic-CTF
🧩 CTF Challenge — BaseLocked
“Two layers protect the truth — only those who decode both may see the light.”
   
A mysterious image named cover.jpeg was recovered from a breached server. At first glance, it looks harmless — a regular picture. But we’ve seen this pattern before. Something’s hidden.

🧠 Intel gathered:
The attacker didn’t just encrypt — they obscured the password itself, twice over using base64. And only after that, used it to encrypt the final message with AES-256-CBC.

You're given a single string: "Yldsc1pUST0="

It's not what it seems — it's a disguise.
This is your first layer to peel back.
