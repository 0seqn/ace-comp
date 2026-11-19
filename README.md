# ACE Competition Questions 2026-27


## Question 1

- Notes: N/A
- Answer: 24

## Question 2

- Notes: https://www.avast.com/c-ip-address-public-vs-private
- Answer: 256.10.0.1

## Question 3

- Notes: Not sure just ones I found
- Answer: PASS, AUTH, MFA, PIN, FIDO, FACTOR, ONE, and CERT

## Question 4

- Notes: https://www.base64decode.org/ enter the string to the decoder and it will print the answer
- Answer: NEVER USE THE SAME PASSWORD TWICE

## Question 5

- Notes: N/A
- Answer: No the file is intact according to the hashes but it contains errors and may not be reliable evidence of carrier records in court.

## Question 6

- Notes: searched "1930s British moles"  source: https://en.wikipedia.org/wiki/Cambridge_Five
- Answer:
- Kim Philby
- Guy Burgess
- Donald Maclean
- Anthony Blunt
- John Cairncross

## Question 7

- Notes: I rewrote the code to get the results in class, can send the code snippet if u want. 
- Answer:
Admin - EhEdDBw=

paSSwoRD123 - AxQjNgUCMypCR0M= 

Sup3rUs3r - IAAAVgA4El0B 

r@dPanda - ATUUNRMDBQ8= 

## Question 8

- Notes: The attacker was still able to get in using alice’s account after Bobs was removed, removing bob only closed one entry point, so the attacker simply switched to another account that was also in the admins list
- Answer: B

## Question 9

- Notes: the loop never ends and print("Account Locked") never happens an attacker can keep guessing and sees “CAPTCHA required” over and over again
- Answer: D

## Question 10

- Notes:
- Answer: 01111

## Question 11

- Reasoning and evidence:
- Answer:
Q11A. B  

Q11B. B 

Q11C. B 

Q11D. C 

Q11E. A 

## Question 12

- Notes: N/A super long justification if I was to write it. 
- Answer: F. A dockyard contractor gained unsupervised access to the deck-seven terminal through the systems tech.

## Question 13

- Notes: The input "; DROP TABLE users; -- is pasted straight into the SQL string with +, so the database reads it as commands, not as a name. overview of SQLI - https://portswigger.net/web-security/sql-injection
- Answer: SQLI "SQL injection" 

## Question 14

- Notes: The subnet mask 255.255.255.0 means the first three octets (192.168.1) are the network portion and the last octet is the host portion. To get the network address, AND the IP with the mask: the first three octets stay the same mask = 255 and the last octet becomes 0 mask = 0, so 192.168.1.45 becomes 192.168.1.0.  sources to understand - https://www.digitalocean.com/community/tutorials/understanding-ip-addresses-subnets-and-cidr-notation-for-networking / https://www.auvik.com/franklyit/blog/what-is-subnet-mask/
- Answer: 192.168.1.0.

## Question 15

- Notes: /login page, so the goal is to trick the user into entering their credentials on a fake site.
- Answer: Phishing "paypa1.com"

## Question 16

- Notes: N/A
- Answer:
1. Presentation metadata: “carefully look at the layers” — a clue.
2. Slide 5, behind an image: “The secret password is `flyinghorseplymouth`.”
3. Slide 8, at the bottom edge: “attack in the morning.”

## Question 17

- Notes:
- Answer:

## Question 18

- Notes: decode from base 64 - decode from ROT-13 sources: https://www.dcode.fr/rot-13-cipher / https://www.dcode.fr/cipher-identifier
- Answer: SOCIAL ENGINEERING EXPLOITS PEOPLE NOT CODE

## Question 19

- Notes: go to - https://www.exifdata.com/ enter the image and look at thumbnail. 
- Answer: Mini piano? 

## Question 20

- Notes: I averaged the RTT differences between hops 2 and 4 to isolate each inter-city link. The known 940 km Dundane–Perthos distance calibrates the fibre speed at about 264,950 km/s. That gives distances of approximately 1,459 km from Arboathia to Montrosia and 1,104 km from Montrosia to Carnoustis. Since the bearings differ by 132°, applying the cosine rule gives about 2,300 km between Arboathia and Carnoustis.
- Answer: 2300 KM

## Question 21

- Notes: Work backwards from the token: 7106 − 13 − 100 = 6993, and 6993 ÷ 7 = 999
- Answer: ID=999

## Question 22

- Notes: Bobs statement is true CCTV shows charlie entered, so charlies “I never entered” and davids “bob is lying” are false. “Exactly two true” means alices must be the second true one: David downloaded the file, some evidence to back this up also is his active computer at 14:04 and presence in the building support towards him being the one.
- Answer: Most likely david

## Question 23

- Notes: Decoded the five tools in CyberChef: Base64 gave “ROT13”, Morse gave “BASE64”, hex gave “Citrix” (Citrix CTX1), the 5-bit Bacon cipher gave “HEX” and the 10-bit binary gave “Base32”.
  sentences:
“The user enters the first factor.”
“The system then sends a one-time passcode to the user’s registered device.”
“The user confirms their identity using a fingerprint scan.”
“Access is granted only after all three factors are verified.”
What type of authentication is being used here? - last sentence 
- Answer: Multi-factor authentication (MFA) 3FA

## Question 24

- Notes: OPHcrack is needed which I dont want to install nor can we install in college so left this one. 
- Answer:

## Question 25

- Notes:
1. From Hex, with the delimiter set to “space”, turns the string into raw bytes.
2. XOR Brute Force, with the scheme set to “standard”, tries every possible one-byte key.
3. Scan the output for the one line that reads as English. Key 5a is the only one that does.
- Answer: RANSOMWARE ENCRYPTS FILES THEN DEMANDS PAYMENT

## Question 26

- Notes: Very hard, The spectrogram revealed the key **STARSHIP**. I fixed the script so it seeds the PRNG once, then XORed each ciphertext byte with the successive keystream bytes. The readable result was `flag{seed_the_prng_once}` I used an online spectogram and entered the .wave file which gave me the "starship" key.
- Answer: flag{seed_the_prng_once}

## Question 27

- Notes: Not sure if this is right but judging by the fact that the highest response time 85.8 ms indicates that all four digits matched
- Answer: 5821

## Question 28

- Notes: I can get a lot of answer for this unfortunately so I would just pick one of these or try get a better answer than me. my method for this was 26= 2x13
  reversed key 6231>1326 for example for the first answer I mentioned the others are the same its just backwards, no digits repeat.
- Answer: 1326, 1428, 1632, 1836, 2346, 2754, 3264

## Question 29

- Notes: - `2468` has 0 correct digits, so 2, 4, 6, and 8 are excluded.
- In `1234`, the two correct digits must be 1 and 3
- In `5678`, the two correct digits must be 5 and 7
- So the code uses exactly `{1, 3, 5, 7}`.
`7091` has 2 correct digits and 2 correct positions. Since 0 and 9 are excluded, **7 is first** and **1 is fourth**.
In `1357`, exactly two positions are correct. The 1 and 7 positions are now known to be wrong, so **3 is second** and **5 is third**.
- Answer: 7351

## Question 30

- Notes: Sources: https://exiftool.org/ - https://exifmeta.com/ - - https://www.metadata2go.com/ - https://jimpl.com/ - https://contentcredentials.org/verify - https://29a.ch/photo-forensics/ - https://github.com/rsmbl/Resemble.js / This one took long but is not hard if u want to try get the results yourself also
- Answer: 
  A) Manually edited: D

  `D.jpg` is a 2000×1500 JPEG with no C2PA/AI provenance. It matches the original scene dimensions and appears to be a local object removal.

- B) AI-edited: A and C

  `A.png` contains Google C2PA metadata: “Created by Google Generative AI” and “Applied imperceptible SynthID watermark.”

  `C.png` contains: “Azure OpenAI ImageGen” and “Created image using artificial intelligence technology.”

- C) Edit of another edit: A

  A’s C2PA metadata includes an ingredient/parent relationship, and its background aligns with the manually cleared scene in D.

- D) Fully regenerated with AI: C

  C explicitly identifies Azure OpenAI ImageGen and AI creation, with no ordinary local-edit provenance.

## Question 31

- Notes: I tried but it was taking too long im sure if you keep trying combinations eventually you will get it. 
- Answer: 

## Question 32

- Notes: The file decrypts to a PNG blueprint sheet which is our secret recovered PNG. / I am surprised this is 8 marks because its super easy hopefully I done it correctly
- Answer: The secret file is called recovered-secret.png I will attach it to this repo under an images folder
