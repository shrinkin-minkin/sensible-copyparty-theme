# sensible-copyparty-theme

## Summary

![theme](assets/theme_preview.gif)

### Features
- Extremely Sensible Themes (TM)
- Easily add your own color schemes
- Ten Color Schemes out of the box
- Most importantly - NO EMOJIS!!!!! (mostly)

### Quickstart
It is so easy to get this up and running. 

1. Clone this repo to your machine
2. Update how you normally run copyparty with this flag: `--css-browser "/path/to/sensible-copyparty-theme/style.css?ce"`

__NOTE:__ Path must be in quotes, must start with `/` and must end with `?ce` 

__FURTHER NOTE:__ Copyparty does not like when you give an absolute path to the `--css-browser` argument. You would be better off storing the css in a path mounted in copyparty! Make sure it is stored in a mount available to everyone on your server. There has to be a better way...


### Change Themes
I wanted this as easy as possible. Just go into style.css, uncomment the theme that you want to use, comment out the other themes.

Feel free to add whatever theme you want. Create a pull request!

| Variable | Default Value | Description |
| :--- | :--- | :--- |
| `--bg-color` | `#272e33` | Primary application background . |
| `--accent-color` | `#343f44` | Background for tooltips, context menus, and header hovers. |
| `--text-color` | `#d3c6aa` | Primary typography color . |
| `--link-color` | `#7fbbb3` | Default color for interactive file links and text buttons . |
| `--link-hover-color` | `#e67e80` | Hover color state for links and control action items . |
| `--table-alt-bg` | `#2e383c` | Background color for alternating zebra rows in the file browser window. |
| `--table-hover-bg` | `#414b50` | Background color highlight when hovering over a file row. |
| `--table-active-bg` | `#475258` | Background color for selected or actively clicked file rows. |
| `--hilite-1` | `#859289` | Color used for activated UI toggle states and buttons. |
| `--srv-1` | `var(--text-color)` | Legacy fallback tracker variable mapping to the main text color. |
| `--directory-color` | `var(--link-color)` | Explicit font color forced on directory folder paths ending with `/`. |
| `--directory-hover-color` | `var(--link-hover-color)` | Hover font color target forced on directory folder paths ending with `/`. |


#### Currently Available Themes:
- EVERFOREST DARK
- GRUVBOX DARK
- CATPPUCCIN MOCHA
- TOKYONIGHT STORM
- ROSEPINE DARK
- NORD
- ONE DARK
- DRACULA
- MONOKAI PRO
- EVERFOREST LIGHT

### Markdown Example:

![md](assets/markdown.png)


### TODO:
- [x] Update markdown on main page to look normal
- [ ] update markdown to look good on subpages
- [ ] Reskin sub-pages
- [ ] eradicate remaining emojis

### Motivation
I love [copyparty](https://github.com/9001/copyparty). The uploads are fantastic and there is so much functionality for collaboration in the app. However, I have always disliked the UI. I use copyparty with a bunch of non-technical people and I got tired of having to walk them through the application, saying horrid sentences like "click on the rocketship". After using the app for a year or more, I got fed up and reskinned the UI one afternoon. That being said, this reskin is not perfect, but it will support 90% of your needs. 

Feel free to make a pull request with updates!

