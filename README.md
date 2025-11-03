## Ballona Wetlands Wildlife Image Analysis

This project helps automate wildlife monitoring at the Ballona Wetlands using AI models for camera trap analysis.

### Tools
Using [AddaxAI](https://addaxdatascience.com/addaxai/), we run two open models:
- **[MegaDetector](https://github.com/agentmorris/MegaDetector)** – detects animals, people, or vehicles.
- **[SpeciesNet](https://github.com/google/cameratrapai)** – classifies detected animals by species.

### Workflow
1. Upload camera trap photos to shared folder
2. Run models w/ AddaxAI
3. Export detections as CSV
4. Append results to Sheets/Dashboard

### Example Output
| label | confidence | man_verified | DateTimeOriginal |
| ----- | ---------- | ------------ | ---------------- |
| northern raccoon | 0.982 | TRUE | 2025-08-01 01:27:09 |



## Example Photo 📸
![DSCF0142](https://github.com/user-attachments/assets/c7ea915b-2fa5-4e47-a1b8-82a7db62100c)

-------------

**Maintained by**: Gabrielle Barnes

**Affiliation**: Volunteer project with [Friends of Ballona Wetlands](https://www.ballonafriends.org/)

**Status**: In progress
