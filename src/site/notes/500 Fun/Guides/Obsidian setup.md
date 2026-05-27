---
{"dg-publish":true,"tags":["guide"],"publish":true,"permalink":"/500-fun/guides/obsidian-setup/","dgPassFrontmatter":true,"created":"2026-04-23T23:37:25.631+05:00","updated":"2026-05-25T23:51:33.293+05:00","dg-note-properties":{"tags":["guide"],"publish":true}}
---

- [x] fix excalidraw settings for the svg sync ✅ 2026-05-20
- [ ] get vimrc support working please
- [ ] Setup shortcuts for everything
	- [ ] setup shit for bookmarks aswell
- [ ] fix date created field
- [ ] Big excalidraw boards for everything related to a subject and find a way to insert notes in there aswell (go through the excalidraw vid)
- [ ] Task setup make it better(kinda passable rn) on the phone aswell
- [ ] Add more views to all my bases
- [ ] add obsidian spaced repitition to the workflow
- [ ] tempalter plugin setup for daily notes
- [ ] setup shortcuts unc (dg tasks etc)
- [x] fix quick add to add to top of file ✅ 2025-11-25

> ***Fair warning this shit is fucky***
>  Also quick guide to [[500 Fun/Guides/Markdown\|Markdown]]


##### Obsidian web clipper
- the most retarded shit on the planet basically they try and convert java script to markdown and bullshist which leads to the properties being fucky with the highlight menu causing nothing to pop up as content 
- fix (use legacy mode you can check wiki)
	- https://help.obsidian.md/web-clipper/troubleshoot
- ##### Tags usage
	- rn idgas but potentially what i have considered is using tags to replace folders, got the idea from  a video and use the tags folder addon to overview the folder and shit 
	- Another alternative this one i *prefer*, is to only use tags for organizational needs like say in my stu-dying folder i have no sub folders and only use # tags and nested # tags as categorization i could still use folders for the big stuff and include tags that doesn't really change anything but just a thought ig

##### Plugins
##### Essential
- [[100 Inbox/Excalidraw\|Excalidraw]]
	- for drawing sherlock
- Quickadd
	- task add shortcuts
- Virtual Linker / Glossary
	- Shows links without you linking
- Image inline (disable the base 64 bullshit - extra space comsumption): allows to paste directly to obsidian
- Image Converter 
	- compression
- Archiver 
	- Archive tasks
- Digital Garden (for publishing to website)
- Google Calendar overview of stuff 
	- (not gonna be using this to add shit (tasks) )
- Ultimate Todoist Sync
	- task sync with gcal and todoist (for phone ease of use)
##### Non-Essential
- AutoMoc 
	- adds relevant links to mocs

- Calendar (cool ig)
- Full Calendar (also cool ig)
- Raindrop
- Notebook Navigator
##### Syncthing
- the conflicts are annoying but it is what it is 
- Doesn't really cause issues if you use one device at a time

##### Vault organization (after switching to *"one vault")
- Main folders
	- sub folders for overarching shit that i know will have alot of files e.g Biology etc (will ideally also tag with bio if i can)
	- Tags are gonna be the primary thing i use since they are better at dealing with notes that fall into multiple categories
##### Switching to a physical journal
- kinda unnecessary to have a journal in obsidian the ability to add attachments is nice tho
	- [x] watch reysus video on integrating analog methods aswell [the hybrid note-taking system I wish I learned earlier](https://www.youtube.com/watch?v=mq0XvGPSm9w&t=14s) [link](https://app.todoist.com/app/task/9764893452) #todoist   ✅ 2025-11-24

# Changes to the Setup
- **UPDATE** 24 Nov 25
- Tags are for certain things mainly using manually made mocs with plugins initially did find them use ful 
- **UPDATE** 13 May 2026
	this is from sylvan franklins obsidian vid [[100 Inbox/Videos/Interview with Obsidian enthusiast 2026\|Interview with Obsidian enthusiast 2026]]
		  My own implementation of it is still in progress I overhauled my vault yesterday with the following changes
			- bases section for consumption
			- made a buncha templates with frontmatter hella 
			- and cleaned the vault up a bit
		- Tag related changes I'll be making today
			[[100 Inbox/tag reference\|tag reference]]
		-  
		
- 16-5-2026 Added the birdy plugin and the excalidraw markdown same note template Excalidraw_temp 

- 23-06-26 probably forgot to tell you but I added a shit load of stuff  
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">

<div class="markdown-embed-title">

# 400

</div>



## Context
gonna be using it for mapping concepts and ideas and shit 
also for mocs
##  Instructions/Troubleshooting
[[_templates/excalidraw/Excalidraw_temp\|Excalidraw_temp]] is a template I made for making a normal .md note into a two sided note one side is an excalidraw drawing the other is the standard markdown

<svg version="1.1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 360" width="800" height="360" class="excalidraw-svg"><!-- svg-source:excalidraw --><metadata></metadata><defs><style class="style-fonts">      @font-face { font-family: Excalifont; src: url(data:font/woff2;base64,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); }</style></defs><rect x="0" y="0" width="800" height="360" fill="#121212"></rect><g transform="translate(410 270) rotate(0 50.929954528808594 12.5)"><text x="0" y="17.619999999999997" font-family="Excalifont, Xiaolai, sans-serif, Segoe UI Emoji" font-size="20px" fill="#d3d3d3" text-anchor="start" style="white-space: pre;" direction="ltr" dominant-baseline="alphabetic">Excalidraw</text></g><g stroke-linecap="round" transform="translate(10 210) rotate(0 130 70)"><path d="M32 0 C95.12 -2.77, 154.53 0.41, 228 0 M32 0 C95.59 1.09, 159.06 -0.09, 228 0 M228 0 C248.08 -0.23, 260.7 10.43, 260 32 M228 0 C251.46 -1.09, 261.89 11.96, 260 32 M260 32 C259.23 59.47, 260.35 88.47, 260 108 M260 32 C259.85 57.87, 260 83.87, 260 108 M260 108 C260.72 128.11, 247.68 141.17, 228 140 M260 108 C258.43 130.23, 250.23 140.91, 228 140 M228 140 C151.47 141.77, 75.23 142.26, 32 140 M228 140 C169.24 139.79, 111.73 140.72, 32 140 M32 140 C11.88 141.81, -0.68 129.5, 0 108 M32 140 C10.26 141.61, -1.71 130.48, 0 108 M0 108 C0.92 93.57, -0.14 75.15, 0 32 M0 108 C1 92.77, 0.93 75.97, 0 32 M0 32 C0.6 9.04, 11.21 1.66, 32 0 M0 32 C1.68 10.77, 8.56 -2.2, 32 0" stroke="#d3d3d3" stroke-width="2" fill="none"></path></g><g transform="translate(97.5 262.5) rotate(0 43.29496765136719 10.9375)"><text x="0" y="15.4175" font-family="Excalifont, Xiaolai, sans-serif, Segoe UI Emoji" font-size="17.5px" fill="#d3d3d3" text-anchor="start" style="white-space: pre;" direction="ltr" dominant-baseline="alphabetic">Templates</text></g><g mask="url(#mask-2RfyH8Y9)" stroke-linecap="round"><g transform="translate(276 289.6786785714286) rotate(0 63.96179814860224 -3.068997392352145)"><path d="M-0.79 0.68 C20.6 -0.51, 107.29 -5.59, 128.72 -6.82 M0.99 0 C22.26 -1.02, 107.17 -4.38, 128.15 -5.27" stroke="#d3d3d3" stroke-width="2" fill="none"></path></g><g transform="translate(276 289.6786785714286) rotate(0 63.96179814860224 -3.068997392352145)"><path d="M105.02 4.24 C113.72 2.47, 120.23 -2.27, 128.15 -5.27 M105.02 4.24 C111.98 2.37, 118.79 -1.54, 128.15 -5.27" stroke="#d3d3d3" stroke-width="2" fill="none"></path></g><g transform="translate(276 289.6786785714286) rotate(0 63.96179814860224 -3.068997392352145)"><path d="M104.33 -12.85 C113.3 -9.01, 120.04 -8.14, 128.15 -5.27 M104.33 -12.85 C111.43 -9.38, 118.45 -7.95, 128.15 -5.27" stroke="#d3d3d3" stroke-width="2" fill="none"></path></g></g><mask id="mask-2RfyH8Y9"><rect x="0" y="0" fill="#fff" width="504" height="396.53353571428573"></rect><rect x="314.7100143432617" y="261.25125" fill="#000" width="50.57997131347656" height="50" opacity="1"></rect></mask><g transform="translate(314.7100143432617 261.25125) rotate(0 25.251783805340523 25.358431179076433)"><text x="25.28998565673828" y="17.619999999999997" font-family="Excalifont, Xiaolai, sans-serif, Segoe UI Emoji" font-size="20px" fill="#d3d3d3" text-anchor="middle" style="white-space: pre;" direction="ltr" dominant-baseline="alphabetic">Dual </text><text x="25.28998565673828" y="42.62" font-family="Excalifont, Xiaolai, sans-serif, Segoe UI Emoji" font-size="20px" fill="#d3d3d3" text-anchor="middle" style="white-space: pre;" direction="ltr" dominant-baseline="alphabetic">note</text></g><g stroke-linecap="round" transform="translate(190 10) rotate(0 130 50)"><path d="M25 0 C88.84 -0.65, 153.24 -0.24, 235 0 M25 0 C75.12 -0.67, 125.73 -1.82, 235 0 M235 0 C251.99 1.1, 260.66 9.88, 260 25 M235 0 C251.01 -0.69, 260.73 7.46, 260 25 M260 25 C260.31 40.04, 261.52 56.29, 260 75 M260 25 C261.26 43.59, 260.15 59.8, 260 75 M260 75 C261.62 93.17, 251.1 101.22, 235 100 M260 75 C259.17 93.03, 250.78 101.73, 235 100 M235 100 C184.62 102.64, 131.99 99.9, 25 100 M235 100 C182.53 98.53, 129.87 99.51, 25 100 M25 100 C9.21 100.8, -1.21 91.73, 0 75 M25 100 C8.56 99.73, 2.12 92.66, 0 75 M0 75 C1.3 61.48, -1.33 46.19, 0 25 M0 75 C-0.79 54.59, 0.77 35.64, 0 25 M0 25 C0.1 6.53, 7.86 -0.44, 25 0 M0 25 C0.72 6.03, 7.73 0.84, 25 0" stroke="#d3d3d3" stroke-width="2" fill="none"></path></g><g transform="translate(203.25010681152344 47.5) rotate(0 116.74989318847656 12.5)"><text x="116.74989318847656" y="17.619999999999997" font-family="Excalifont, Xiaolai, sans-serif, Segoe UI Emoji" font-size="20px" fill="#d3d3d3" text-anchor="middle" style="white-space: pre;" direction="ltr" dominant-baseline="alphabetic">Excalidraw drawing base</text></g><g stroke-linecap="round"><g transform="translate(327.82444 116) rotate(0 66.73244001965499 81.18920118045995)"><path d="M0.94 0.27 C21.32 15.9, 101.84 67.71, 122.95 94.63 C144.06 121.54, 126.79 150.43, 127.59 161.75 M-0.02 -0.64 C20.21 14.57, 101.24 65.56, 122.41 92.84 C143.59 120.11, 126.05 151.76, 127.03 163.02" stroke="#d3d3d3" stroke-width="2" fill="none"></path></g><g transform="translate(327.82444 116) rotate(0 66.73244001965499 81.18920118045995)"><path d="M122.58 138.41 C124.78 148.44, 126.97 156.55, 127.03 163.02 M122.58 138.41 C124.95 146.33, 125.17 153.7, 127.03 163.02" stroke="#d3d3d3" stroke-width="2" fill="none"></path></g><g transform="translate(327.82444 116) rotate(0 66.73244001965499 81.18920118045995)"><path d="M139.44 141.31 C135.61 150.44, 131.8 157.51, 127.03 163.02 M139.44 141.31 C136.88 148.48, 132.19 155.01, 127.03 163.02" stroke="#d3d3d3" stroke-width="2" fill="none"></path></g></g><mask></mask><g mask="url(#mask-PUBj4uKo)" stroke-linecap="round"><g transform="translate(124.32505251550191 204) rotate(0 34.29123266183453 -85.96962789512705)"><path d="M-1 -1.04 C10.44 -29.76, 58.03 -144.13, 69.58 -172.96 M0.67 1.02 C11.9 -27.42, 57.12 -142.29, 68.79 -171.33" stroke="#d3d3d3" stroke-width="2" fill="none"></path></g><g transform="translate(124.32505251550191 204) rotate(0 34.29123266183453 -85.96962789512705)"><path d="M68.06 -146.34 C66.74 -155.3, 69.06 -166.87, 68.79 -171.33 M68.06 -146.34 C68.66 -151.66, 69.19 -157.82, 68.79 -171.33" stroke="#d3d3d3" stroke-width="2" fill="none"></path></g><g transform="translate(124.32505251550191 204) rotate(0 34.29123266183453 -85.96962789512705)"><path d="M52.17 -152.65 C56.83 -159.09, 65.17 -168.27, 68.79 -171.33 M52.17 -152.65 C56.38 -156.44, 60.52 -161.17, 68.79 -171.33" stroke="#d3d3d3" stroke-width="2" fill="none"></path></g></g><mask id="mask-PUBj4uKo"><rect x="0" y="0" fill="#fff" width="293.61170994261647" height="477.14842224121094"></rect><rect x="105.73843127788734" y="92.42578887939453" fill="#000" width="106.45989990234375" height="50" opacity="1"></rect></mask><g transform="translate(105.73843127788734 92.42578887939453) rotate(0 52.87785389944909 25.60458322547842)"><text x="53.229949951171875" y="17.619999999999997" font-family="Excalifont, Xiaolai, sans-serif, Segoe UI Emoji" font-size="20px" fill="#d3d3d3" text-anchor="middle" style="white-space: pre;" direction="ltr" dominant-baseline="alphabetic">excalidraw </text><text x="53.229949951171875" y="42.62" font-family="Excalifont, Xiaolai, sans-serif, Segoe UI Emoji" font-size="20px" fill="#d3d3d3" text-anchor="middle" style="white-space: pre;" direction="ltr" dominant-baseline="alphabetic">tag</text></g><g stroke-linecap="round"><g transform="translate(636.6338284331839 137) rotate(0 -58.995624185809845 71.00339210977045)"><path d="M1.17 -0.07 C-3.41 18.84, -7.16 89.9, -27.11 113.65 C-47.06 137.4, -103.12 137.53, -118.53 142.41 M0.33 -1.15 C-4.48 17.39, -8.4 87.82, -28.31 111.87 C-48.23 135.92, -103.93 137.84, -119.16 143.15" stroke="#d3d3d3" stroke-width="4" fill="none"></path></g><g transform="translate(636.6338284331839 137) rotate(0 -58.995624185809845 71.00339210977045)"><path d="M-97.83 130.12 C-104.97 133.84, -110.84 139.36, -119.16 143.15 M-97.83 130.12 C-103 132.21, -107.22 136.25, -119.16 143.15" stroke="#d3d3d3" stroke-width="4" fill="none"></path></g><g transform="translate(636.6338284331839 137) rotate(0 -58.995624185809845 71.00339210977045)"><path d="M-94.44 146.89 C-102.74 145.09, -109.72 145.07, -119.16 143.15 M-94.44 146.89 C-100.21 145.46, -105.14 146.02, -119.16 143.15" stroke="#d3d3d3" stroke-width="4" fill="none"></path></g></g><mask></mask><g stroke-linecap="round"><g transform="translate(456 60.67666666666668) rotate(0 43.29553868472576 8.57091028649333)"><path d="M-0.36 -0.35 C14.31 2.52, 72.32 14.74, 86.95 17.79 M1.65 -1.58 C16.25 1.34, 71.78 15.33, 85.98 18.72" stroke="#d3d3d3" stroke-width="4" fill="none"></path></g><g transform="translate(456 60.67666666666668) rotate(0 43.29553868472576 8.57091028649333)"><path d="M61.13 21.43 C65.75 20.86, 69.62 21.07, 85.98 18.72 M61.13 21.43 C65.9 20.8, 71.09 21.04, 85.98 18.72" stroke="#d3d3d3" stroke-width="4" fill="none"></path></g><g transform="translate(456 60.67666666666668) rotate(0 43.29553868472576 8.57091028649333)"><path d="M65.2 4.82 C69.05 7.72, 72.06 11.41, 85.98 18.72 M65.2 4.82 C68.95 7.8, 73.25 11.66, 85.98 18.72" stroke="#d3d3d3" stroke-width="4" fill="none"></path></g></g><mask></mask><g stroke-linecap="round" transform="translate(550 30) rotate(0 120 50)"><path d="M25 0 C83.08 -0.22, 145.96 -0.27, 215 0 M25 0 C65.74 -0.25, 108.77 0.06, 215 0 M215 0 C230.84 -1.74, 241.02 7.6, 240 25 M215 0 C230.84 1.85, 238.91 7.53, 240 25 M240 25 C238.78 39.36, 241.46 52.63, 240 75 M240 25 C240.58 35.75, 239.99 47.26, 240 75 M240 75 C241.93 93.14, 230.36 98.92, 215 100 M240 75 C240.59 91.41, 230.76 101.21, 215 100 M215 100 C145.8 101.74, 75.04 102.7, 25 100 M215 100 C155.91 98.67, 96.1 99.45, 25 100 M25 100 C8.17 99.58, -0.62 91.18, 0 75 M25 100 C6.26 98.38, 0.37 90.91, 0 75 M0 75 C1.12 57.65, -0.98 38.6, 0 25 M0 75 C-0.46 56.31, 0.03 35.99, 0 25 M0 25 C1.62 7.83, 8 -0.15, 25 0 M0 25 C1.45 8.63, 8.56 -0.86, 25 0" stroke="#d3d3d3" stroke-width="4" fill="none"></path></g><g transform="translate(575.1100769042969 55) rotate(0 94.88992309570312 25)"><text x="94.88992309570312" y="17.619999999999997" font-family="Excalifont, Xiaolai, sans-serif, Segoe UI Emoji" font-size="20px" fill="#d3d3d3" text-anchor="middle" style="white-space: pre;" direction="ltr" dominant-baseline="alphabetic">Mermaid integration</text><text x="94.88992309570312" y="42.62" font-family="Excalifont, Xiaolai, sans-serif, Segoe UI Emoji" font-size="20px" fill="#d3d3d3" text-anchor="middle" style="white-space: pre;" direction="ltr" dominant-baseline="alphabetic"></text></g></svg>

# This is just mermaid integration check 
``` mermaid
flowchart TD
  A[Mermaid integration] --> B[another test]
  C[nigger]-->A & B 
  D[sex toy] <--> A & C
  B --> D
```


</div></div>

- also added templates for a bunch of stuff am gonna need to make them alot for workable with
# Archived

- [x] add plugin (tag folders/glossary) ✅ 2025-11-04 🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian setup 🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian web clipper > Plugins > Essential > Non-Essential > Switching to a physical journal
- [x] switch to only one vault????? and use bases or soemthing for funni usage ✅ 2025-11-05 🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian setup 🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian web clipper > Plugins > Essential > Non-Essential > Switching to a physical journal
- [x] explore ✅ 2025-11-13 🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian setup 🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian web clipper > Plugins > Essential > Non-Essential > Switching to a physical journal
	- [x] mocs ✅ 2025-11-07
	- [x] breadcrumbs ✅ 2025-11-16
- [x] exclude some folders from graph view like (tasks, icanstudy etc.) ✅ 2025-11-16 🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian setup 🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian web clipper > Plugins > Essential > Non-Essential > Switching to a physical journal
- [x] ignore folders (plugins/etc) 🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian setup 🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian web clipper > Plugins > Essential > Non-Essential > Switching to a physical journal
	- decided wasn't worth the hassle
	- [x] find a way to keep it always open(by it i mean syncthing on android) ✅ 2025-11-07
- [x] find the plugin that allows to resolve syncthing conflicts  🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian setup 🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian web clipper > Plugins > Essential > Non-Essential > Switching to a physical journal
- [x] fix the file explorer being empty issue smh 🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian setup 🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian web clipper > Plugins > Essential > Non-Essential > Switching to a physical journal
	- ~~had to hard reset vault~~
- [x] MOC plugins ???? (maps of content (like the ones on obsidian wikis and shi)) 🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian setup 🔒 [[2025-11-24\|2025-11-24]] 🕸️ Obsidian web clipper > Plugins > Essential > Non-Essential > Switching to a physical journal
	-~~turns out it isn't really necessary kinda convenient but i would rather just use the graph view and modify as needed ~~
