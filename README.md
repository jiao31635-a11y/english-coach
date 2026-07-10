# AI Voice Coach 2.0

A GitHub Pages friendly English speaking coach built with plain HTML, CSS, and JavaScript.

## Features

- Push to Talk and Continuous Conversation modes
- Safe browser SpeechRecognition state handling
- Browser microphone permission flow with clear errors
- Text-to-speech with accent and speaking speed settings
- Existing conversation practice scenarios and feedback report
- IELTS Speaking Part 1 practice
- IELTS Speaking Part 2 cue cards with 1-minute preparation and 2-minute speaking timers
- IELTS Speaking Part 3 discussion practice
- Full IELTS mock-test flow
- AI-estimated IELTS band report with pronunciation limitations clearly labeled
- Improve My Answer panel
- Automotive Parts Business English scenarios for BOLYNX-style distributor conversations
- Local learning history with JSON export and transcript download

## Security

The Gemini API key is never hard-coded. It is stored only in the user's browser localStorage and is not included in learning-history exports.

## Deployment

This project has no build step. Push index.html and phase2.js to the main branch and serve the repository with GitHub Pages.

## Browser Notes

Use Google Chrome over HTTPS for microphone and speech recognition support. Browser SpeechRecognition can produce transcripts, but it cannot measure phoneme-level pronunciation, so IELTS pronunciation feedback is approximate.
