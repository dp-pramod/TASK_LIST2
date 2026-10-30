# O-Health Project Task Tracker

## Siddhant

| Task Description | Priority | Delivery Type | Status | Target Date | Completed Date | Remarks / Blockers |
|------------------|----------|---------------|--------|-------------|----------------|--------------------|
| **Sync RPI Offline with current latest version**<br>Sync Offline DEB code to have latest web code, integrate recent web updates into the offline implementation and addressed code-level differences to maintain feature parity. | Low | — | 🟢 Completed | 14-10-2026 | 14-10-2026 | — |
| **New DEB Package — Audio from DEB Instead of RPI**<br>Created a new DEB package that follows the existing web workflow, sending audio from the DEB instead of the Raspberry Pi (RPI). | — | Unplanned | 🟢 Completed | 19-10-2026 | 19-10-2026 | — |
| **Primary and Secondary Language Selection — Yashoda and Other Logins**<br>Added primary and secondary language selection, with the secondary language options based on the selected primary language.<br>The secondary language resets at the start of every assessment.<br>Implemented for two tenants: Yashoda and other logins. | — | — | 🟢 Completed | 23-10-2026 | 23-10-2026 | — |
| **No Internet Screen — Tauri**<br>Create a new screen which will be displayed when there is no internet. | — | — | 🟢 Completed | 26-10-2026 | 26-10-2026 | — |
| **Github workflow update — Tauri**<br>Update Git workflow to have workflow name and another to run on h200 self hosted server. | — | — | 🟢 Completed | 26-10-2026 | 26-10-2026 | — |
| **TTS Interrupt, Menu Icon Sizing, and Restart Assessment**<br>Interrupt TTS playback when the menu is opened or the microphone is closed.<br>Make all menu icons an even, consistent size.<br>Enable the Restart Assessment option. | — | — | 🟢 Completed | 27-10-2026 | 27-10-2026 | — |
| **RPI Configuration Scripts — Prod and Offline DEB Flows**<br>Write configuration scripts that automatically configure the Raspberry Pi (RPI) for both the production .deb flow and the offline .deb flow. | — | — | 🟢 Completed | 27-10-2026 | 27-10-2026 | [RPI_CONFIG](https://ohealthtech-my.sharepoint.com/my?id=%2Fpersonal%2Fsiddhant%5Fjaiswal%5Fo%2Dhealth%5Fin%2FDocuments%2FRPI%5FCONFIG&ga=1) |
| **DGX TLS Setup Script — CA Certificates**<br>Write a TLS setup script for the DGX server that handles creation of the CA certificates. | — | — | 🟢 Completed | 27-10-2026 | 27-10-2026 | [RPI_CONFIG](https://ohealthtech-my.sharepoint.com/my?id=%2Fpersonal%2Fsiddhant%5Fjaiswal%5Fo%2Dhealth%5Fin%2FDocuments%2FRPI%5FCONFIG&ga=1) |
| **Documentation for RPI and DGX Setup Scripts**<br>Create documentation covering the RPI configuration scripts (prod and offline .deb flows) and the DGX TLS setup script. | — | — | 🟢 Completed | 27-10-2026 | 27-10-2026 | [RPI_CONFIG](https://ohealthtech-my.sharepoint.com/my?id=%2Fpersonal%2Fsiddhant%5Fjaiswal%5Fo%2Dhealth%5Fin%2FDocuments%2FRPI%5FCONFIG&ga=1) |
| **Vitals — Use Offline Audio When Available**<br>Play the offline audio files for vitals when they are available locally, instead of generating audio online. | — | — | 🟢 Completed | 28-10-2026 | 28-10-2026 | — |
| **Tauri Env Config, Keyboard Changes, and Vitals Modal Close**<br>Read configuration from the Tauri environment.<br>Update keyboard behaviour.<br>Close the vitals modal when the user clicks outside it. | — | — | 🟢 Completed | 28-10-2026 | 28-10-2026 | — |
| **Version and package.json Update**<br>Bump the application version and update package.json. | — | — | 🟢 Completed | 28-10-2026 | 28-10-2026 | — |
| **Updated API Integration for Web and Tauri and End-to-End ABDM Verification**<br>Integrate the newly modified APIs into the application.<br>Verify the complete ABDM workflow end to end and resolve any integration issues. | High | — | 🟢 Completed | — | — | — |
| **Fix Vitals Disappearing After Manual Entry — Web and Tauri**<br>Fix the issue where manually entered vitals disappear when navigating to the Patient Information tab.<br>Ensure the entered values are retained in both web and Tauri applications. | High | — | 🟢 Completed | — | — | — |
| **Vitals Offline Audio Playback — TTS Logic**<br>Implement the missing text-to-speech (TTS) logic for vitals offline audio playback in both web branches and both mobile branches.<br>Ensure the behaviour matches the existing assessment audio logic. | High | — | 🟢 Completed | — | — | — |
| **Stop Audio When Leaving Assessment or Vitals**<br>Stop all audio playback immediately when the user exits an assessment or leaves the vitals page.<br>Ensure no audio continues or starts playing after leaving either screen. | Medium | — | 🟢 Completed | — | — | — |
| **Patient-Side Language Selection Across All Tenants**<br>Add a common language selection option to the patient-facing web and Tauri applications across all tenants.<br>Match the existing mobile language selection behaviour and experience. | High | — | 🟢 Completed | — | — | — |
| **Reusable Report Display Component — Web, Mobile, and Tauri**<br>Create a reusable component to display reports across web, mobile, and Tauri applications.<br>Ensure consistent report content, formatting, and behaviour across all three platforms. | High | — | 🟢 Completed | — | — | — |
| **Responsive Layouts Across Devices**<br>Make all screens and pages responsive across mobile phones, tablets, and desktops.<br>Ensure layouts, text, and controls adapt to different screen sizes and orientations. | High | — | 🟢 Completed | — | — | — |
| **Improve Vitals UI Animations**<br>Add smooth, intuitive animations to the vitals interface.<br>Improve visual feedback during data entry, loading, and vitals updates. | High | — | 🟢 Completed | — | — | — |
| **Radxa Board Setup — Ubuntu 26 LTS**<br>Download the Ubuntu 26 LTS image file and flash it to a new SD card.<br>Set up and configure the Radxa board with the new installation. | — | — | 🟢 Completed | — | — | Implemented Armbian OS not Ubuntu OS |
| **On Leave**<br>Full-day leave. | — | — | ⚫ On Leave | 29-10-2026 | 29-10-2026 | On leave on 29-10-2026 |
| **Microphone Usage Guide — 5-Second Animation**<br>Add a small visual guide with a 5-second animation demonstrating how users should position themselves and speak near the microphone. | High | — | 🔵 In Progress | — | — | Started 30-10-2026  |
| **App SOP Animation — Under 10 Seconds**<br>Show a short animation (under 10 seconds) before the first interaction: "Press mic button and start speaking clearly."<br>Ensure the user understands what to do before the first question. | High | — | 🔵 In Progress | — | — | Started 30-10-2026 |
| **Mic Guidance Animation — Speaking, Waiting, and Stopping**<br>Add a visual guide for speaking, waiting, and stopping.<br>Ensure the user sees a clear state for listening, processing, and the next question. | High | — | 🔵 In Progress | — | — | Started 30-10-2026 |
| **Language Guidance Instruction**<br>Show an instruction that the user can speak naturally in the selected language.<br>Reduce confusion during OPD use. | High | — | 🔵 In Progress | — | — | Started 30-10-2026 |
| **Application-Wide Event Logging — Web and Mobile**<br>Implement comprehensive logging across the entire web and mobile applications.<br>Capture every event, including minor interactions, user actions, system events, and errors.<br>Improve log clarity and consistency to simplify debugging and trace events back to their source. | Low | — | ⚪ Yet to Start | — | — | — |
| **Minimum 3-Second Wait on Consent Page**<br>Keep the Proceed button disabled for at least 3 seconds after the consent page loads.<br>Enable it once the waiting period has elapsed and the required consent has been provided. | Medium | — | ⚪ Yet to Start | — | — | — |
| **Fix Intermittent English Fallback in Language Selection**<br>Investigate and fix the issue where the selected primary or secondary language unexpectedly falls back to English.<br>Ensure the selected languages are consistently maintained throughout the application. | Medium | — | ⚪ Yet to Start | — | — | — |
| **Standardize Tenant Logo Sizes**<br>Apply consistent logo dimensions and spacing across all tenants.<br>Preserve each logo's aspect ratio and ensure consistent display across screen sizes. | High | — | ⚪ Yet to Start | — | — | — |
| **End-to-End Issue Documentation and FAQ PDF**<br>Document issues across the complete application workflow, including troubleshooting steps and resolutions.<br>Compile frequently asked questions and publish the documentation as a PDF. | Low | — | ⚪ Yet to Start | — | — | — |

---

**Priority:** High · Medium · Low

**Delivery Type:** Planned · Unplanned

**Status:** 🔵 In Progress · 🟡 Unit Testing · 🟣 Ready to Deploy · ⚪ Yet to Start · 🟠 On Hold · 🟢 Completed · ⚫ On Leave

**Date Format:** DD-MM-YYYY

**—:** Not specified
