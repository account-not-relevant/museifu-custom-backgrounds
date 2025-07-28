# Museifu Custom Backgrounds v1.1.0
Custom backgrounds adapted or created for the [Museifu Theme](https://github.com/account-not-relevant/museifu-theme) on Obsidian.
Based on [Obsidian Notebook Themes](https://github.com/CyanVoxel/Obsidian-Notebook-Themes) v2.1.0.

_Work in progress._

## How to use the snippet
1. Download the Museifu Custom Backgrounds.css from the repository.
2. Open the settings panel in Obsidian and click the Appearance tab.
3. Scroll to "CSS snippets" and click the folder icon.
4. Drop Museifu Custom Backgrounds.css into the folder that appears.
5. In Obsidian, next to "CSS snippets", click the "Reload snippets" button.
6. Find the Museifu Custom Backgrounds on the list, activate it on and you're ready to go!
7. To start using the themes, add a file property to the note you want to customize using the Command Pallete (Ctrl + P).
8. Add "cssclasses" as the property and apply whatever theme you want as the value! Below is the list of all possible modifications, **including the ones present only when the Museifu Theme is applied:**

### Pen Colors
- `pen-red`
- `pen-blue`
- `pen-green`
- `pen-gray`
- `pen-white`
- `pen-purple`
- `pen-white`
- `pen-black`
- `pen-museifu-dark` - applies the pen color of Museifu Dark 
- `pen-museifu-cream` - applies the pen color of Museifu Cream
- `pen-museifu-paperlike` - applies the pen color of Museifu Paperlike

### Page colors and effects
  - `page-dots` - adds dots to the page background
  - `page-grid` - adds a grid to the page background
  - `page-grid-big` - adds an even bigger grid
  - `page-grid-giant` - adds an even biggierer grid
  - `page-grid-omega` - adds the biggiest grid there is
  - `stronger-grid` - makes the grid a bit more visible
  - `page-white` - turns the background white
  - `page-manila` - turns the background manila (light yellow basically)
  - `page-blueprint` - turns the background blue
  - `page-museifu-dark` - turns the background darker (when compared to Museifu Theme's default)
  - `page-museifu-cream` - turns the background cream-like (very light brown)
  - `page-museifu-paperlike` - turns the background white and adds a paper effect to it
  - `soft-block-grid` - turns the background into a blocky, gray one (must apply some grid before)
  - `black-block-grid` - turns the background into a blocky, black one (must apply some grid before)

The classes below are made to work with Museifu Theme only:

  - `museifu-limit` - forces the specific note to "activate" the "Readable line length" feature
  - `museifu-justify` - adds the justify effect to the note
  - `museifu-centralize` - adds the centralize effect to the note
  - `museifu-limijust` - adds the limit effect, then the justify one (CURRENTLY THE CLASS IS `museifu-justicenter` - _my bad, I'll fix it_)
  - `museifu-large-kanban` - adds some width to the kanban note
  - `museifu-banner` - adds the image that has "museifu-banner" on its alt text as the banner. If the image has "museifu-banner-fade", it adds the banner with a little fade
  - `museifu-banner-recolor` - when using an image as a banner, it paints it with the accent color of the pen color you are using. Notice that page effects bring their own pen-colors and also that it won't add a filter, but really PAINT the image.

### Page combos you should try using:

<img width="1919" height="1079" alt="Captura de tela 2025-07-27 223704" src="https://github.com/user-attachments/assets/8150185c-2ea8-4fd0-b71b-e6871f88b030" />

- Old Newspaper
	- `page-museifu-paperlike`
	- `pen-museifu-cream`
	- (optional) `museifu-justicenter` or `limijust` once I fix it
- Black Blocks
	- `page-grid-big` or whatever size you want
	- `black-block-grid`
	- (optional) `museifu-justicenter`
- Modern Dark
	- `page-museifu-dark`
	- Whatever pen color of your choice, but I recommend the default one, red or blue
- Strawberry Milk
	- `page-museifu-paperlike`
	- `pen-red`
- Remember Museifu is a **modular theme!** Try your own variations!
