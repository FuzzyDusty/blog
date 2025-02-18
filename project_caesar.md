# Project Caesar

For my first "github" project, I am going to make a caesar cipher in python! 
  ~ (which also includes learning about git add, git commit, and git push) ~

# What is a Caesar Cipher?

- An rudimentry cipher algorithm that "shifts" an alphabet. For example below, the alphabet is shifted by 3. You can kind of think of it like you have 2 giant rings. The top ring is the full alphabet, and the bottom ring is the full alphabet as well. What you do is "turn" the bottom alphabet, so the "A" now corresponds to "X" for instance.
  
- I have pasted a picture from wikipedia below:

<img width="762" alt="Screenshot 2025-01-08 at 10 01 38 PM" src="https://github.com/user-attachments/assets/9b75cb63-8565-49d9-9edb-434f81191d42" />
<img width="936" alt="Screenshot 2025-01-08 at 10 01 53 PM" src="https://github.com/user-attachments/assets/7a639ea5-6f69-4f02-b9d4-c3b2ca55e51b" />
[Source](https://en.wikipedia.org/wiki/Caesar_cipher)


# What is the coding logic?

- In my opinion, once the logic for the algorithm has been determined, the actual coding is easy. In this example, using mod is going to be our best friend! 

This is my thought process:

- there are 26 letters in the English Alphabet
- Remember the ring analogy? How does one wrap around per se from Z -> A. The answer lies in the magic of mod. For example 34 mod (%) 26 = 8 or the letter "h" . This allows a wrap around!

- A tidbit about me: I used to be a middle school substitute teacher, so I hope people can learn from this!


# What am I going to implement?

1. Prompt that asks user what their message is
2. Ask user what shift they would like to use
3. Output!

The magic of this, is it allows users to input plaintext and encrypt, but also decrypt since they can input the shift or "password" for instance.
