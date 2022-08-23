# Qualtrics CSS

Sharecare styling for [Qualtrics](https://www.qualtrics.com/) surveys.

Deployed and served using GH pages at https://sharecare.github.io/qualtrics-css/sharecare.css.

## Usage

Go to Survey > Look and feel and set the following:

- Theme: Blank
- Layout: Classic
- General
  - Next Button Text: Next
  - Previous Button Text: Previous
  - Progress Bar: None
  - Progress Bar Position: Top
  - Questions Per Page: (empty)
  - Header: (empty)
  - Footer: (empty)
- Style
  - Primary Color: #00bfa5
  - Secondary Color: #00bfa5
  - Font: Default
  - Foreground Contrast: Medium
  - Question Spacing: Compact
  - Question Text: 18 Bold
  - Answer Text: 18
  - Custom CSS: (empty)
  - External CSS: `https://sharecare.github.io/qualtrics-css/classic-sharecare.css`
- Motion
  - Page Transition: None
- Logo: None
- Background
  - Background Type: Color
  - Background Color: #FFFFFF
  - Foreground Contrast: Medium
  - Questions Container: Off

## Development

[Chrome overrides](https://developer.chrome.com/blog/new-in-devtools-65/#overrides) are the easiest way to make and see changes in real time.

Assuming an overrides folder at `~/Projects/chrome-overrides` and this project at `~/Projects/qualtrics-css`, the following commands should link to the file in version control.

```
mkdir -p ~/Projects/chrome-overrides/sharecare.github.io/qualtrics-css
cd ~/Projects/chrome-overrides/sharecare.github.io/qualtrics-css
ln ~/Projects/qualtrics-css/classic-sharecare.css
```
