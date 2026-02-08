
# AI-Driven Deepfake Content Verification using Blockchain

This project detects deepfake images using an AI model and stores the verification result on a blockchain to ensure immutability and transparency.

## Problem
Deepfake images are widely circulated online. There is no trusted way to verify whether content was checked earlier or if verification results were modified.

## Solution
- AI model classifies images as Real or Deepfake with a confidence score.
- SHA-256 hash uniquely identifies content.
- Blockchain stores verification result, confidence, and timestamp.
- Same content can be re-verified instantly without recomputation.

## Tech Stack
- Frontend: HTML, CSS, JavaScript
- Backend: Python (Flask)
- AI: Pretrained deepfake detection model
- Blockchain: Algorand Testnet (PyTeal)

## Team
- Riya – Blockchain
- Bhumika – Backend & AI
- Asmita – Frontend
