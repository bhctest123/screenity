# Add Screenshot Functionality and Rebrand to BehaveReporter

This PR adds screenshot functionality to the main interface and rebrands Screenity to BehaveReporter.

## Changes Made:
1. Added a screenshot button to the main popup interface in RecordingType.jsx
2. Implemented screenshot capture functionality that saves screenshots as PNG files
3. Added localization strings for the screenshot feature
4. Updated the extension name and description to BehaveReporter
5. Created new logo and icon assets with a blue background and 'B' letter

## Testing:
- The screenshot button appears in the main interface before starting a recording
- Clicking the button captures the current tab and saves it as a PNG file
- The filename includes a timestamp in the format: 'screenshot_[timestamp].png'
- A toast notification appears after taking a screenshot

Link to Devin run: https://app.devin.ai/sessions/515766dc649f4c9e9488cb15edb03c4c
