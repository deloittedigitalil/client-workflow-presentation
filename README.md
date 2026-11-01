# Workflow Demo Presentation

Five phone screens shown side by side, with buttons to look at one at a time:

1. Main screen (logo animation)
2. Bottom navigation animations
3. Brief approval reveal
4. What to expect at the visit
5. Home screen messages (four messages, switched with the numbered buttons)

## How to open it

Download or clone the folder and open `index.html` in Chrome, Edge or Safari. There is nothing to install.

Keep the folders next to `index.html` (`main-screen`, `bottom-nav`, `brief-approval`, `screen-4`, `screen-5`); each screen loads its own files from there.

The brief approval screen loads one font (Noto Sans Hebrew) from Google Fonts, so it looks best with an internet connection. Without one it falls back to a system font.

## Layout

| Folder | Screen |
| --- | --- |
| `main-screen/` | 1. Main screen |
| `bottom-nav/` | 2. Bottom navigation |
| `brief-approval/` | 3. Brief approval |
| `screen-4/` | 4. What to expect at the visit |
| `screen-5/` | 5. Home screen messages |

`index.html` is the page that puts them side by side. The gap between phones is the `GAP` value in its script.
