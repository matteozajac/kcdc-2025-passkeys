# Agenda for "Passkeys: The End of Passwords and the Future of Authentication"

**Talk Duration:** 35 minutes (fits 30-40 minute slot, leaving room for Q&A in a 60-minute session)  
**Conference:** Kansas City Developer Conference 2025  
**Session Details:** Friday, 1:00 PM - 2:00 PM, Session (60 min), Security Track  
**Presenter:** Mateusz Zając
**Overview:** This agenda structures the talk to start with password problems, introduce passkeys, cover implementation, advanced topics, and conclude with a future outlook. It draws from provided notes and WWDC inspirations (2022-2024). Use screenshots for visuals instead of live demos. Allocate times for pacing, transitions, and audience engagement.

## Sections

| Section | Time Allocation | Key Content and Activities |
|---------|-----------------|----------------------------|
| **Introduction** | 2-3 minutes | - Welcome and overview: Hook with the promise of ditching passwords for a phishing-proof, convenient future.<br>- Introduce yourself and session goals: What passkeys are, why they matter, and practical implementation.<br>- Tease business benefits (fewer breaches, simpler UX, reduced support costs). |
| **The Problems with Passwords** | 5-6 minutes | - Common attacking methods: Phishing (Delta app/airport example), credential stuffing, server breaches (2022 Verizon report stats).<br>- UX/UI pain points: Complexity, resets, rotation, poor experience (side-by-side comparison with passkeys).<br>- Why 2FA isn't enough: Phishing SMS/TOTP, push fatigue. |
| **Introducing Passkeys: Better UX with Superior Security** | 4-5 minutes | - Explanation: Public/private key pair vs. hashed passwords.<br>- How they work: Phishing resistance, no server-side secrets.<br>- Screenshot walkthrough: Signing in with an existing account (Face ID/Touch ID vs. typing).<br>- Benefits: Faster creation/sign-in, automatic upgrades (silent creation). |
| **Implementing Passkeys: Practical Steps and Code Walkthrough** | 10-12 minutes | - Creating a passkey: iOS code example (ASAuthorization API).<br>- Backend: WebAuthn/FIDO2 integration (no full overhaul).<br>- Edge cases: No passkey in browser? Remote devices via Bluetooth/QR.<br>- Syncing: iCloud Keychain.<br>- Screenshot walkthrough: Silent creation, next-time sign-in, multiple accounts, sharing (AirDrop). |
| **Enterprise and Advanced Topics** | 5-6 minutes | - Managed devices: Security options, Managed Apple IDs, attestation.<br>- Recovery: "Forgot password" strategies, fallback to passwords.<br>- Passwordless transition: Why 2FA is less secure long-term; solving real issues. |
| **Conclusion and Q&A Tease** | 2-3 minutes | - Recap: Passkeys as secure, convenient future.<br>- Call to action: Support passwords temporarily but guide to passkeys.<br>- Open for questions. |

## Additional Notes
- **Total Time:** 28-35 minutes (flexible for screenshot explanations or interaction).  
- **Visual Aids:** Use slides with high-resolution screenshots (annotated flows from WWDC). Diagrams for key pairs and attacks.  
- **Tips:** Practice narration to fit timings. If shortening to 30 minutes, condense code walkthrough. Engage audience with questions like "How many password resets do you handle weekly?"  
- **Sources/Inspirations:** Vague notes, talk abstract, WWDC transcripts (2022: basics; 2023: enterprise; 2024: upgrades). Update with any 2025 developments if needed.