<img src="https://media.giphy.com/media/908fS3eQFUodG/giphy-downsized-large.gif?cid=790b7611234547e38d2d28ea6f7b0d66180e3807095ddc8b&rid=giphy-downsized-large.gif&ct=g" width="75%">

# macOS

Hello! 👋

This is a collection of (hopefully) useful shortcuts, apps and other things to make your life as a developer a little bit easier.
You don't have to know what all of these things are. You can just as well treat this list as something to go back to. Once you're in need of something or if you simply want to explore what's out there, here are our tips and tricks!

> :rocket: Before we get started - head over to System Preferences. Click General and next to 'Show scroll bars' select 'Always'.

## :apple: General

<details>
<summary>Browser Shortcuts</summary>

_Many of these are more or less universal._

- `Cmd` + `N` - New window.
- `Cmd` + `T` - New tab.
- `Cmd` + `R` - Reload page.
- `Cmd` + `,` - Settings.
- `Cmd` + `Y` - History.
- `Cmd` + `Shift` + `C` - Developer Tools.
- `Cmd` + `Opt` + `Left/Right Arrow` || `Ctrl` + `Tab` - Switch between tabs (if you are using the `Tab` variant, hold down `Shift` to go in the opposite direction).
- `Cmd` + `Number` - Switch between tabs in numbered order.
- `Cmd` + `Left/Right Arrow` - Go back to previous page or forward in history.

_To empty browser cache (hard reload) - Open Developer Tools and right click the refresh logo in your browser window._
_Alternatively (depending on the browser), hover over the refresh logo and hold `Opt` + click._

</details>

<details>
<summary>Discord Shortcuts</summary>

- `Cmd` + `K` - Navigate Discord i an Alfred/Spotlight like way.
- `Alt` + `Arrow up / Arrow down` - Switch between text-channels.

</details>

<details>
<summary>MacOS Shortcuts</summary>

_Daily "good to know" commands:_

- `Cmd` + `C` - Copy selection.
- `Cmd` + `V` - Paste selection.
- `Cmd` + `X` - Cut selection to clipboard.
- `Cmd` + `A` - Select all.
- `Cmd` + `F` - Opens up a find/search box to locate a specific character/word/phrase at your location.
- `Cmd` + `T` - New tab in Finder.
- `Cmd` + `Q` - Quit software (easy to forget - just because the window is gone doesn't mean the software isn't still running).
- `Cmd` + `H` - Hide window.
- `Cmd` + `N` - New finder window.
- `Cmd` + `+` - Zoom in.
- `Cmd` + `-` - Zoom out.
- `Cmd` + `Space` - Open spotlight search.
- `Cmd` + `Tab` - Switch between open applications (Add `Shift` to go in the opposite direction, and press `Q` if you want to quit the marked app).

_Intermediate:_

- `Cmd` + `Backspace` - Delete a file from finder.
- `Cmd` + `Shift` + `Q` - Lock computer.
- `Cmd` + `Shift` + `Backspace` - Empty your bin.
- `Cmd` + `Click n' drag` - To move icons in your top-menu-bar.
- `Cmd` + `Shift` + `.` - Show/hide dotfiles.
- `Cmd` + `Ctrl` + `Space` - Open emojis and symbols. :mage:
- `Cmd` + `Opt` + `Esc` - Force quit (displays list of active apps).
- `Ctrl` + `Up/Down Arrow` - Activate mission control (useful if you are using a non-apple keyboard).
- `Ctrl` + `Left/Right Arrow` - Switch between virtual workspaces.

_Screenshot related:_

- `Cmd` + `Shift` + `3` - Takes a screenshot of the whole screen.
- `Cmd` + `Shift` + `4` - Click and release to take a screenshot of the selected area.
- `Cmd` + `Shift` + `5` - Opens up a menu where you can choose to take screenshots or do screen recordings etc.

_These files will be saved on your Desktop unless you change the standard settings in Quicktime Player._

</details>

<details>
<summary>MacOS Settings</summary>

- Scroll bars always on (System Preferences > General > Show scroll bars > Always).

- Do you hate it when you hold down a key and your Mac doesn’t let it repeat itself? If you enjoy writing things like: "[`aaaaaaaaaaaaaaaaaaaaaaaaaaaaa`](https://www.reddit.com/r/AAAAAAAAAAAAAAAAA/)" - here's a guide to set this up. First, paste the following line into your terminal: `defaults write -g ApplePressAndHoldEnabled -bool false`.

- Introducing "The Developer Folder"! :hammer: _Some of you with newer Macs might already have this pre-installed but for those of you who don't, here's an instruction:_ In Finder you have your Documents folder, your Pictures folder etc but wouldn't it be nice to also have a Developer folder? Start by going to your Home folder and simply create a folder in there named "Developer". :exploding_head: If you like, simply hold and drag it to the Favorites menu to your left in the Finder window and now you have the perfect place to store your projects and whatnots.

- **Extra:** There are also ways to configure your preferences/settings by interacting with the terminal or by writing scripts. This can be very handy if you have a new computer, to have all your personal settings inserted by just running one script. If this sounds like fun, check out [macOS defaults](https://macos-defaults.com/) to get started.

</details>

## :woman_technologist: VSCode

<details>
<summary>Emmet Abbreviations</summary>

> What the heck are Emmet Abbreviations?
> They are autocompleting texts that pop up automagically in VSCode - once you've saved your document in its .html, .css, .js etc format.
> For example, by writing something as simple as a "!" in an .html file, you'll be freed from the headache of using your (brain)memory.

_Specifically for .html files:_

- `!` + `Return` - This will create all the essentials for you to get started.

- Lets say you want to write three `<div>` elements and that they all have the class `imageWrapper`. All you need to do is write
  `div*3.imageWrapper` and hit `Return` and let the magic unfold. The same logic applies to any html element and whatever class name you would like to give them.

Mastering all these is a course in itself but learning at least a few will save you alot of time along the way. [Here's a link to their documentation.](https://docs.emmet.io/)

</details>

<details>
<summary>Extensions</summary>

- **Alphabetical Sorter**: After downloading, try `Cmd` + `Shift` + `A` on a selected piece of code.
- **Bracket Pair Colorizer**: Lets you visually see which squiggly line belongs to which. Very handy.
- **Fluent Icons**: If you want to add some flare to the menu icons on your left.
- **GitHub Markdown Preview** + **Markdown Preview GitHub Styling** (two separate extensions that are dependant on each other): Let's you get a visual preview of your `.md` files on VSCode before pushing them up to GitHub.
- **Live Server**: After downloading, head to your `.html` file, right click and hit `Open with Live Server`. You should know have started a live server and opened it in your browser.
- **Live share**: Like Google Docs, but for VSCode! Lets you collaborate with your code live with others.
- **PHP Intelephense**: A nice tool that helps you in multiple ways when writing in PHP.
- **Prettier**: Gives your code a more consistent and "prettier" formatting.

- :art: Want to create a new look or so called "theme" for your VSCode? The internet is full of them! Look for the one that you want and then search the name of it + download in the VSCode extensions shop found inside the puzzle logo in the left menu bar. [Here are some example on what's out there.](https://vscodethemes.com/)

</details>

<details>
<summary>Hacks</summary>

- Look for the :mag: magnifying glass to the upper left in VSCode.
  This Search tool is great when looking for lost things within a project folder. Or if you need to do a search and replace, this is your friend and can save you lots of time.
- Below the magnifying glass is another handy tool called Source Control. It involves git, which will be covered in greater detail during future lessons!
- Sync Settings!

> _Looking for your settings file in VSCode?_ 🤔
> Press `Cmd` + `P` and in the Command Palette search bar search `json` and go to the autocompleted suggestion `"Preferences: Open Settings (JSON)"` and go there. Here you can find and set your default settings for alot of things such as formatters, extensions, save settings, editor fonts etc.
> Also accessible by pressing `Cmd` + `,`.

A good basic setup for your `settings.json` is:

```
{
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,

    "[php]": {
      "editor.defaultFormatter": "bmewburn.vscode-intelephense-client",
      "editor.formatOnSave": true
    },
  }
```

</details>

<details>
<summary>Shortcuts</summary>

- `Cmd` + `J` - Open (and close) the Terminal within VSCode.
- `Cmd` + `N` - Open up a new document then `Cmd` + `S` to name and save it.
- `Cmd` + `D` - Depending on where your cursor is located, it will search for duplicates within the document and add a cursor to these as well.
- `Cmd` + `Z` - Undo.
- `Shift` + `Tab` - Untab selection/row.
- `Cmd` + `Number` - To switch between tab/window-groups.
- `Cmd` + `,` - Settings.
- `Cmd` + `Left/Right Arrow` - Move cursor to the far left/right. :large_blue_circle:
- `Opt` + `Left/Right Arrow` - Move cursor one word to the left/right. :large_blue_circle:
- `Cmd` + `Up/Down Arrow` - Move cursor to the top/bottom of the document. :large_blue_circle:
- `Opt` + `Up/Down Arrow` - Move the current line upward/downard.
- `Opt` + `Shift` + `Up/Down Arrow` - Copy the current line upward/downard.
- `Opt` + `Click` - Adds a second cursor to the clicked area (lets you alter multiple things at once).
- `Cmd` + `Opt` + `Up/Down Arrow` - Also adds a cursor on the line above or below the current cursor position.
- `Cmd` + `,` - Takes you to settings.
- `Cmd` + `P` - Lets you navigate to any file by typing its name.
- `Cmd` + `Shift` + `P` - Open the command Palette.

  > Tip! Look for a menu option that says "Shell command: install 'code' command in PATH" and click it to install.
  > Now whenever you are working in your CLI, in your terminal, you can now type `$ code .` and your current location will open itself up in VSCode.
  > Preferences is also a great place for you to add your own snippets and to change the theme of your VSCode and more.

Adding `Shift` to any of those marked with :large_blue_circle: will also select that specified area.

</details>

## :computer: The Command Line

_Note: Make sure you have Homebrew installed before trying these._

> The `$` sign is often times used to signify that the following code should be run on the command line. So when you select/copy/paste, just exclude the dollar sign when running the code on your computer.

<details>
<summary>Fish</summary>

> [Fish](https://fishshell.com/) is a so called command line shell. Think of the shell as one of many human friendly languages where you can communicate with your own computer. :fish:

**If you have fish installed - here are some fun commands you can use to alter your fish settings:**

Want to remove the annoying greeting that pops up everytime you open up your command line? Try this command:
`$ set -U fish_greeting`

Opens up settings and lets you pick and choose straight from your own browser window (notice the menu alternatives colors/prompt):
`$ fish_config`

_For the brave daredevil ninjas out there who also want to have an emoji in their prompt like Dante Mogrim._ :shipit: :

1. Press `Cmd` + `Shift` + `G`.
2. In the "Go to the folder" search bar paste the following and hit Return: `~/.config/fish/functions/fish_prompt.fish`.
3. Now that you've found the `fish_prompt.fish` file, open up and drag and drop it into a VSCode window. Erase everything in that specific file and paste this instead :hedgehog: :

```code
function fish_prompt
    set_color $fish_color_cwd
    echo -n (basename $PWD)
    set_color normal
    echo -n '🐨'
end
```

Check for the emoji shortcut listed in this lesson and add whatever you like and put it into the same place as the koala example. Save your changes and re-open your CLI window and voilá! :unicorn:

Lastly, the word around town's that there seems to be a file called `~/.config/fish/config.fish` where you can make a set of pretty cool fish configurations. Ask your teacher or the information superhighway (www) for more on this topic!

</details>

<details>
<summary>Hacks</summary>

_Hyper:_

- On their website they have a [few selections to choose from](https://hyper.is/themes). Click the one you like and press the 'install' button in the bottom right corner.
- There are different ways to change the look to your liking but since we're only dipping our toes today I'll leave some of you to search for a certain file: "~/.config/Hyper/.hyper.js"

_Terminal:_

1. Once you've opened Terminal, press `Cmd` + `,` to go to settings.
2. Click 'Profiles' in the top menu. Here you'll find a range of different so called 'profiles'. Click the plus sign in the bottom left corner to create and name your own personal profile.
3. After that, in the same window, you can change text, colors, cursor all kinds of things. Play around and see what happens!

_If nothing happens try quitting and restarting your CLI app._

</details>

<details>
<summary>Homebrew</summary>

> [Homebrew](https://brew.sh/index_sv) is a command line tool that helps us Mac/Linux users to install other tools - in fancy terms it's a "software package management system". Don't worry about too much about the logic behind this - just know that it's a wonderful thing to have.

Homebrew's own downloadable command line tools are referred to as "formulas". Here's a few fun ones to get you started:

- [Bat](https://github.com/sharkdp/bat): A syntax highlighter for cat.
  `$ brew install bat`
- [ImageMagick](https://imagemagick.org/index.php): Tools and libraries to manipulate and convert images in many formats.
  `$ brew install imagemagick`
- [Speedtest](https://www.speedtest.net/sv/apps/cli): An internet speed checker.
  `$ brew install speedtest-cli`
- [Tree](https://sourabhbajaj.com/mac-setup/iTerm/tree.html): Get a better structured view of things than when using for example the `pwd` command.
  `$ brew install tree`
- [Zoxide](https://github.com/ajeetdsouza/zoxide): A kind-of-smarter variation of the `cd` command.

To see more, [here's a list of all their available formulae](https://formulae.brew.sh/formula/).

</details>

<details>
<summary>Homebrew Casks</summary>

> [Casks](https://github.com/Homebrew/homebrew-cask) aka "homebrew-casks" is an extension of Homebrew that lets you install apps and softwares via your command line. Their chosen term to describe a downloadable app/software is a so called "cask".
> The nice thing about this is that you can for example update all of your downloaded apps by just a simple homebrew command. You can for example install applications like Google Chrome, VLC, Iconset, Spotify etc. No more downloading `.dmg` files and dragging them to your Applications folder! To see everything installed via homebrew simply run `brew list`.

To find out which apps you can download - [here is a list.](https://formulae.brew.sh/cask/)

A few example of different commands are:

- `$ brew install --cask discord`
- `$ brew install --cask firefox`
- `$ brew install --cask hyper`
- `$ brew install --cask spotify`
- `$ brew install --cask visual-studio-code`

After applying one of these commands you should be able to find the downloaded app within your applications folder locally on your computer.

> One nice thing with doing it the cask-way is that you also can uninstall your apps via the `brew uninstall <cask-name>` command!

**How about some fonts?** Homebrew has developed something called [homebrew-cask-fonts](https://github.com/Homebrew/homebrew-cask-fonts). Once you have that installed it lets you download [a crazy amount of fonts](https://github.com/Homebrew/homebrew-cask-fonts/tree/master/Casks) just by typing in one simple command.

If this feels interesting a hot tip is to read more into something called a [Brewfile](https://gist.github.com/ChristopherA/a579274536aab36ea9966f301ff14f3f) that lets you automate the installation of all casks and formulas to any computer.

</details>

<details>
<summary>Shortcuts</summary>

- `Ctrl` + `U` - Erase line/row.
- `Ctrl` + `A` - Move cursor to the start of the line.
- `Ctrl` + `E` - Move cursor to the start of the line.
- `Opt` + `Left/Right Arrow` - Move cursor backwards/forwards one word.
- `Cmd` + `N` - New window.
- `Cmd` + `T` - New tab.
- `Ctrl` + `C` - Terminate process (good for when running local servers/highly productive infinite loops etc).
- `Up/Down Arrow` - Scroll among your latest commands.

</details>

## :hammer_and_wrench: Toolkit

Many of these are available on multiple operating systems.

> Those marked with a :beer: are also available as homebrew-casks.

<details>
<summary>Apps / Softwares</summary>

- [Alfred](https://www.alfredapp.com/) :money_with_wings: :beer: - A powerful productivity slash workflow automation tool.
- [Automator](https://www.youtube.com/watch?v=BTmZOh1GI3U) (built-in) - Apples productivity tool. Will be replaced by Apples [Shortcuts](https://developer.apple.com/videos/play/wwdc2021/10232/) in the future.
- [Amphetamine](https://apps.apple.com/us/app/amphetamine/id937984704?mt=12) - Non command-line alternative to Caffeine - prevents sleep mode.
- [BlackHole](https://existential.audio/blackhole/) :beer: - Audio rerouting (requires some experience).
- [Cheatsheet](https://www.mediaatelier.com/cheatsheet/) :beer: - Hold `Cmd` to list all available shortcuts on the software you're currently in.
- [Cleanshot X](https://cleanshot.com/) :money_with_wings: :beer: - Provides extended features for screen capturing.
- [CountdownBar](https://apps.apple.com/us/app/countdownbar-days-counter/id1413807534?mt=12) :money_with_wings: - Appears in the top menu bar and counts down the days until a deadline. Simple but handy!
- [HandBrake](https://handbrake.fr/) :beer: - Convert video from nearly any format to a selection of modern codecs.
- [Iconset](https://iconset.io/) :beer: - Gain access to thousands of [free icons](https://iconset.io/icons) to your projects and keep them locally within this library like software.
- [Keka](https://www.keka.io/en/) :beer: - File archiver. File zipper with a ton of options for compressing.
- [Maccy](https://maccy.app/) :beer: - Clipboard manager.
- [Mos](https://mos.caldis.me/) :beer: - Applies smooth scrolling.
- [Quitter](https://formulae.brew.sh/cask/quitter) :beer: - Quits certain applications after they've been inactive for a period of time.
- [Raindrop.io](https://raindrop.io/) (freemium) :beer: - Have all your important links saved in your own, personal link library.
- [Rectangle](https://rectangleapp.com/) :beer: - A great window management app with a thousand shortcuts built in.
- [Responsively](https://responsively.app/) :beer: - A great app to check the responsiveness of your projects and have a visual overview of multiple devices simultaneously.
- [SoundSource](https://rogueamoeba.com/soundsource/) :money_with_wings: :beer: - Gives you more control over all the audio on your Mac.
- [TinkerTool](https://www.bresink.com/osx/TinkerTool.html) - An app that gives you access to additional preference settings Apple has built into macOS.

</details>

<details>
<summary>Color Pickers</summary>

- [Couleurs](https://couleursapp.com/) :beer:
- [ColorSlurp](https://colorslurp.com/) (freemium)
- [Digital Color Meter](https://support.apple.com/en-gb/guide/digital-color-meter/welcome/mac) (built-in)
- [Pika](https://superhighfives.com/pika) :beer:
- [System Color Picker](https://apps.apple.com/us/app/system-color-picker/id1545870783?mt=12)

</details>

<details>
<summary>Image Compressors</summary>

- [ImageAlpha](https://pngmini.com/) :beer:
- [ImageOptim](https://imageoptim.com/mac) :beer:

</details>

<details>
<summary>Kanban / To Do Lists</summary>

- [GitHub Projects](https://github.com/features/issues/)
- [Things](https://culturedcode.com/things/) :money_with_wings:
- [Trello](https://trello.com/sv) (freemium)

> If you have no idea how these work - don't worry. You'll have both a class and many future projects to give you plenty of experience in this.

</details>

<details>
<summary>Note Taking</summary>

- [Apple Notes](https://cleanshot.com/) - Works for just about anything except for writing markdown and code snippets (built-in).
- [Notion](https://cleanshot.com/) (freemium) :beer: - A bit heavy but very popular and easy to get started.
- [Obsidian](https://cleanshot.com/) :beer: - Excellent for getting started on learning to write markdown.
- [Quiver](https://cleanshot.com/) :money_with_wings: - Lightweight, a bit outdated but super powerful.

> [Markdown](https://www.markdownguide.org/basic-syntax/) is a lightweight language for creating formatted text using a plain-text editor. Since 2009 GitHub has been using its own variant of Markdown called ['GitHub Flavored Markdown'](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) with added support for adding blocks of code, emojis, images and much more. Every `README.md` or `.md` file you'll ever read on GitHub or elsewhere are formatted by some kind of Markdown logic.
> Want to learn how to write emojis in Markdown? [This cheet sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) is good to get you started. `:panda_face:`

</details>

<details>
<summary>Rinsing</summary>

- [AppCleaner](https://freemacsoft.net/appcleaner/) :beer: - If you do not install/uninstall your app via cask, this is a highly recommended way of uninstalling apps on macOS.
- [DaisyDisk](https://daisydiskapp.com/) :money_with_wings: :beer: - Both visualizes what's taking up storage on your computer and helps you delete things.
- [ExifCleaner](https://exifcleaner.com/) :beer: - Deletes all metadata from images.
- [GrandPerspective](http://grandperspectiv.sourceforge.net/) :beer: - Lets you visualize what is taking up alot of space on your computer.
- [OmniDiskSweeper](https://www.omnigroup.com/more) :beer: - Lets you find larger files on your computer and lets you quickly Trash them (take caution though so you're aware of what your deleting).
- [OnyX](https://titanium-software.fr/en/onyx.html) :beer: - Lets you run miscellaneous maintenance and cleaning tasks.

</details>

<details>
<summary>SVGs</summary>

- [Affinity Design](https://affinity.serif.com/en-us/designer/) :money_with_wings: :beer:
- [Figma](https://cleanshot.com/) (freemium) :beer:

</details>

<details>
<summary>WWW</summary>

- [Awesome Open Source](https://awesomeopensource.com/) - Lets you find all things open source!
- [Cat Ipsum](http://catipsum.com/) - "Litter your copy with more kitty."
- [Can I Use?](https://caniuse.com/) - Provides great up-to-date browser support tables for different web technologies. Whenever you're faced with questions like "is CSS Backdrop Filter supported by all browsers?" - then this site will have all the answers.
- [Color Palettes](https://www.canva.com/colors/color-palettes/) - Find a sweet palette for your next project!
- [CSS Hell](https://csshell.dev/) - A Collection of common CSS mistakes.
- [dev.to](https://dev.to/) - Online community for web developers.
- [DevDocs](https://devdocs.io/) - Covers documentation of many different languages.
- [Dribbble](https://dribbble.com/) - Great inspiration platform to see what design possibilities are out there.
- [Clippy](https://bennettfeely.com/clippy/) - Helps you create cool CSS clip-paths.
- [Favicon Maker](https://formito.com/tools/favicon) - Simple way to generate a clean favicon.
- [GitHub Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/) - Learn to write emojis in GitHub Flavored Markdown.
- [GitHub Gists](https://gist.github.com/discover) - Discover snippets.
- [Google Fonts](https://fonts.google.com/) - Plain and simple place to find fonts.
- [HTMHell](https://www.htmhell.dev/) - A collection of bad practices in HTML, copied from real websites.
- [Meta Tags](https://metatags.io/) - Helps you create meta tags for your projects.
- [Should I Use a Carousel](https://shouldiuseacarousel.com/) - Click the link to find out.
- [Slump Me Some Groups](https://www.toolie.se/groupie/#/) - Create a set of groups, a set of members and slump them all together.
- [Svelte Hacker News](https://hn.svelte.dev/top/1) - A more aesthetic clone than the [original](https://news.ycombinator.com/) that lists all the latest news in tech.
- [web.dev](https://web.dev/) - Measures your website'/project's performance.

</details>

## :shipit: Authors

- [Dante Mogrim](https://github.com/dantemogrim)
- [Simon Lindstedt](https://github.com/simonlindstedt)

## :octocat: License

[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)