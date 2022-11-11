# Qualtrics CSS

 Styling for [Qualtrics](https://www.qualtrics.com/) surveys.

## Usage


Go to Survey > Look and feel and set the following according to the application:

| App                   | Sharecare                                                           | Carefirst                                                           |
| --------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- |
| Theme:                | Blank                                                               | Blank                                                               |
| Layout                | Classic                                                             | Classic                                                             |
| General               |                                                                     |                                                                     |
| Next Button Text      | Next                                                                | Next                                                                |
| Previous Button Text  | Previous                                                            | Previous                                                            |
| Progress Bar          | None                                                                | None                                                                |
| Progress Bar Position | Top                                                                 | Top                                                                 |
| Questions Per Page    | (empty)                                                             | (empty)                                                             |
| Header                | (empty)                                                             | (empty)                                                             |
| Footer                | (empty)                                                             | (empty)                                                             |
| Style                 |                                                                     |                                                                     |
| Primary Color         | #00bfa5                                                             | #2779a9                                                             |
| Secondary Color       | #00bfa6                                                             | #2779a9                                                             |
| Font                  | Default                                                             | Default                                                             |
| Foreground Contrast   | Medium                                                              | Medium                                                              |
| Question Spacing      | Compact                                                             | Compact                                                             |
| Question Text         | 18 Bold                                                             | 18 Bold                                                             |
| Answer Text           | 18                                                                  | 18                                                                  |
| Custom CSS            | (empty)                                                             | (empty)                                                             |
| External CSS          | https://sharecare.github.io/qualtrics-css/classic-sharecare.css    | https://sharecare.github.io/qualtrics-css/classic-carefirst.css |
| Motion                |                                                                     |                                                                     |
| Page Transition       | None                                                                | None                                                                |
| Logo                  | None                                                                | None                                                                |
| Background            |                                                                     |                                                                     |
| Background Type       | Color                                                               | Color                                                               |
| Background Color      | #FFFFFF                                                             | #FFFFFF                                                             |
| Foreground Contrast   | Medium                                                              | Medium                                                              |
| Question Container    | Off                                                                 | Off                                                                 |

## Development

[Chrome overrides](https://developer.chrome.com/blog/new-in-devtools-65/#overrides) are the easiest way to make and see changes in real time.

Assuming an overrides folder at `~/Projects/chrome-overrides` and this project at `~/Projects/qualtrics-css`, the following commands should link to the file in version control.

```
mkdir -p ~/Projects/chrome-overrides/sharecare.github.io/qualtrics-css
cd ~/Projects/chrome-overrides/sharecare.github.io/qualtrics-css
ln ~/Projects/qualtrics-css/classic-sharecare.css
```
