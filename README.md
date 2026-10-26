# O-Health Project Task Tracker

## Siddhant

| Task Description | Priority | Delivery Type | Status | Target Date | Completed Date | Remarks / Blockers |
|------------------|----------|---------------|--------|-------------|----------------|--------------------|
| **Updated API Integration and End-to-End ABDM Verification**<br>Integrate the newly modified APIs into the application.<br>Verify the complete ABDM workflow end to end and resolve any integration issues. | High | — | 🟢 Completed | — | — | — |
| **Fix Vitals Disappearing After Manual Entry — Web and Tauri**<br>Fix the issue where manually entered vitals disappear when navigating to the Patient Information tab.<br>Ensure the entered values are retained in both web and Tauri applications. | High | — | 🟡 Unit Testing | — | — | — |
| **Vitals Offline Audio Playback — TTS Logic**<br>Implement the missing text-to-speech (TTS) logic for vitals offline audio playback in both web branches and both mobile branches.<br>Ensure the behaviour matches the existing assessment audio logic. | High | — | 🟢 Completed | — | — | — |
| **Application-Wide Event Logging — Web and Mobile**<br>Implement comprehensive logging across the entire web and mobile applications.<br>Capture every event, including minor interactions, user actions, system events, and errors.<br>Improve log clarity and consistency to simplify debugging and trace events back to their source. | Low | — | ⚪ Yet to Start | — | — | — |
| **Stop Audio When Leaving Assessment or Vitals**<br>Stop all audio playback immediately when the user exits an assessment or leaves the vitals page.<br>Ensure no audio continues or starts playing after leaving either screen. | Medium | — | 🟡 Unit Testing | — | — | — |
| **Synchronize Web, Mobile, and Tauri Applications**<br>Align features, workflows, and application behaviour across web, mobile, and Tauri.<br>Ensure updates and fixes are consistently applied across all three platforms. | High | — | 🟢 Completed | — | — | — |
| **Patient-Side Language Selection Across All Tenants**<br>Add a common language selection option to the patient-facing web and Tauri applications across all tenants.<br>Match the existing mobile language selection behaviour and experience. | High | — | 🟢 Completed | — | — | — |
| **Offline Audio Sync — Background Downloads and Progress**<br>Enable offline audio files to download and sync in the background.<br>Display download progress in a visible location so users can track the sync status. | High | — | 🟢 Completed | — | — | — |
| **Reusable Report Display Component — Web, Mobile, and Tauri**<br>Create a reusable component to display reports across web, mobile, and Tauri applications.<br>Ensure consistent report content, formatting, and behaviour across all three platforms. | High | — | 🟢 Completed | — | — | — |
| **Responsive Layouts Across Devices**<br>Make all screens and pages responsive across mobile phones, tablets, and desktops.<br>Ensure layouts, text, and controls adapt to different screen sizes and orientations. | High | — | 🟢 Completed | — | — | — |
| **Play Store Deployment and Automatic App Update Pipelines**<br>Configure the mobile application deployment pipeline for the Google Play Store.<br>Set up automatic app update workflows for the Tauri and mobile applications. | Low | — | 🟠 On Hold | — | — | — |
| **Improve Vitals UI Animations**<br>Add smooth, intuitive animations to the vitals interface.<br>Improve visual feedback during data entry, loading, and vitals updates. | High | — | 🟢 Completed | — | — | — |
| **Microphone Usage Guide — 5-Second Animation**<br>Add a small visual guide with a 5-second animation demonstrating how users should position themselves and speak near the microphone. | High | — | 🔵 In Progress | — | — | — |
| **Minimum 3-Second Wait on Consent Page**<br>Keep the Proceed button disabled for at least 3 seconds after the consent page loads.<br>Enable it once the waiting period has elapsed and the required consent has been provided. | Medium | — | ⚪ Yet to Start | — | — | — |
| **Offline Audio Sync — Version and Language Status**<br>Display the currently synced audio version on the sync page.<br>Show which languages have synced successfully.<br>Indicate whether the latest version is synced or a newer version is available to download. | High | — | 🟢 Completed | — | — | — |
| **Fix Intermittent English Fallback in Language Selection**<br>Investigate and fix the issue where the selected primary or secondary language unexpectedly falls back to English.<br>Ensure the selected languages are consistently maintained throughout the application. | Medium | — | ⚪ Yet to Start | — | — | — |
| **Standardize Tenant Logo Sizes**<br>Apply consistent logo dimensions and spacing across all tenants.<br>Preserve each logo's aspect ratio and ensure consistent display across screen sizes. | High | — | 🟢 Completed | — | — | — |
| **End-to-End Issue Documentation and FAQ PDF**<br>Document issues across the complete application workflow, including troubleshooting steps and resolutions.<br>Compile frequently asked questions and publish the documentation as a PDF. | Low | — | ⚪ Yet to Start | — | — | — |
| **Sync RPI Offline with current latest version**<br>Sync Offline DEB code to have latest web code, integrate recent web updates into the offline implementation and addressed code-level differences to maintain feature parity. | Low | — | 🟢 Completed | 14-10-2026 | 14-10-2026 | — |
| **New DEB Package — Audio from DEB Instead of RPI**<br>Created a new DEB package that follows the existing web workflow, sending audio from the DEB instead of the Raspberry Pi (RPI). | — | Unplanned | 🟢 Completed | 19-10-2026 | 19-10-2026 | — |
| **Primary and Secondary Language Selection — Yashoda and Other Logins**<br>Added primary and secondary language selection, with the secondary language options based on the selected primary language.<br>The secondary language resets at the start of every assessment.<br>Implemented for two tenants: Yashoda and other logins. | — | — | 🟢 Completed | 23-10-2026 | 23-10-2026 | — |
| **Radxa Board Setup — Ubuntu 26 LTS**<br>Download the Ubuntu 26 LTS image file and flash it to a new SD card.<br>Set up and configure the Radxa board with the new installation. | — | — | 🟢 Completed  | — | — | Implemented Armbian OS not Ubuntu OS |
| **No Internet Screen — Tauri**<br>Create a new screen which will be displayed when there is no internet.<br> | — | — | 🟢 Completed  | 26-10-2026 | 26-10-2026 | - |
| **Github workflow update — Tauri**<br>Update Git workflow to have workflow name and another to run on h200 self hosted server<br> | — | — | 🟢 Completed  | 26-10-2026 | 26-10-2026 | - |
---

**Priority:** High · Medium · Low

**Delivery Type:** Planned · Unplanned

**Status:** 🔵 In Progress · 🟡 Unit Testing · 🟣 Ready to Deploy · ⚪ Yet to Start · 🟠 On Hold · 🟢 Completed

**Date Format:** DD-MMM-YYYY

**—:** Not specified
