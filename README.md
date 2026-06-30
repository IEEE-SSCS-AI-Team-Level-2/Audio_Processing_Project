# Voice-Controlled Arduino System (AI Pipeline)

## Project Purpose
This is an intelligent voice recognition and speaker identification system powered by Machine Learning. The pipeline processes real-time audio streams from a microphone to predict two outputs simultaneously:
1. **Command:** Recognizes the specific voice command (`ON` / `OFF`).
2. **Person Identification:** Identifies the unique voice biometric (voiceprint) of the speaker to ensure secure access control.

---

## How to Add New Data
To add your voice or register a new user into the system, follow these steps without modifying any code:

1. **Record Audio:** Record raw audio clips using the default Telegram format (`.ogg`).
2. **Directory Structure:** Navigate to the `Data` directory and organize your files exactly as follows:
   ```text
   Data/
   └── [New_Person_Name]/
       ├── ON/   <-- Place .ogg files for the turn-on command here
       └── OFF/  <-- Place .ogg files for the turn-off command here