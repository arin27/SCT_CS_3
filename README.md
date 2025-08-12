# SCT_CS_3

# Password Strength Checker

A Tkinter-based GUI application to evaluate the strength of a password in real time.
It provides instant feedback, color-coded strength labels, and an animated progress bar to help users create strong passwords.

---

# Features

1) Real-time strength analysis as you type.
2) Color-coded feedback:

🟥 Weak – Red label

🟨 Moderate – Yellow label

🟩 Strong – Green label

3) Detailed suggestions for improvement.
4) Progress bar animation for a smooth user experience.
5) Password visibility toggle (eye button 👁 / 🙈).
6) Clear button to reset the checker.

---

# Requirements

1) Python 3.10+
2) Built-in libraries only:
   tkinter
   string
   time
3) No external dependencies required.

---

# How to Run

Save the script as password_checker.py.

Run it in your terminal:

python password_checker.py

---

# Usage

1) Enter a password in the input box.
2) The app will automatically update:
   1) Strength label (Weak / Moderate / Strong)
   2) Reasons for weaknesses (e.g., missing uppercase, no numbers, etc.)
   3) Progress bar animation
   4) Click 👁 to reveal/hide the password.
   5) Click Clear to reset the input and results.

---

# Strength Checking Logic

The password is scored based on the following criteria:

Requirement	Points	Notes
Length ≥ 6	+1	Required minimum length
Contains lowercase letters	+1	
Contains uppercase letters	+1	
Contains numbers	+1	
Contains special characters	+1	

Weak → Score ≤ 2

Moderate → Score 3–4

Strong → Score = 5

---

# Future Enhancements

1) Password generation feature.
2) More advanced scoring based on entropy.
3) Dark/light theme toggle.

---

# Image Description

1) Before entering a password
<img width="1920" height="1080" alt="Screenshot (48)" src="https://github.com/user-attachments/assets/4c5f9642-473a-499b-abe7-66ab3a7bfc11" />

2) Encrypted weak password
<img width="1920" height="1080" alt="Screenshot (49)" src="https://github.com/user-attachments/assets/8ec69b84-a75f-414d-81ac-7978b76fefcc" />

3) On decrypting weak password
<img width="1920" height="1080" alt="Screenshot (50)" src="https://github.com/user-attachments/assets/807ee987-13e6-4b89-9d64-99f080f7904b" />

4) Decrypted moderate password
<img width="1920" height="1080" alt="Screenshot (51)" src="https://github.com/user-attachments/assets/ac692bf7-babb-4e32-89e7-3dac36e35639" />

5) Decrypted strong password
<img width="1920" height="1080" alt="Screenshot (52)" src="https://github.com/user-attachments/assets/da3767ff-62b6-4f43-b3cc-6caa02643b33" />

6) Cleared message
<img width="1920" height="1080" alt="Screenshot (53)" src="https://github.com/user-attachments/assets/ec39572f-7c99-41b4-9050-38ba401fcb01" />

---

Made with love and curiosity.
Harini.

