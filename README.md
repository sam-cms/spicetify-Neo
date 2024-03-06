# spicetify community themes

This is a collection of themes for [spicetify](https://github.com/spicetify/spicetify-cli), a command-line tool to customize Spotify.

You can add your own theme simply by opening a Pull Request (more info in [CONTRIBUTING.md](./CONTRIBUTING.md)).

### **You can find a preview of all the themes in [THEMES.md](./THEMES.md).**

## Notes:

*   **These themes require that you have the latest version of Spotify and Spicetify.**
*   **To install Dribbblish and Turntable themes, follow the instructions in their READMEs**.
*   **Spotify ad-blocked version is not supported.**

## Installation and usage

(If you use Arch Linux you can find this project on the [AUR](https://aur.archlinux.org/packages/spicetify-themes-git/))

1.  Clone this repository. Make sure [git](https://git-scm.com/) is installed and run:
    ```bash
    git clone --depth=1 https://github.com/sam-cms/spicetify-Neo.git 
    ```

2.  For mac an Linux, copy the files into the [Spicetify Themes folder](https://spicetify.app/docs/development/themes). Run:

    **MacO & Linux**

    ```bash
    cd spicetify-Neo
    cp -r * ~/.config/spicetify/Themes

    ```
    **For windows**
    ```bash
    cd spicetify-themes
    cp * "$(spicetify -c | Split-Path)\Themes\" -Recurse

    ```


3.  Choose which theme to apply just by running:
    ```bash
    # Neopunk
    spicetify config current_theme Neopunk
    spicetify config color_scheme Neopunk
    spicetify apply
    ```
    You can also apply another Neo green theme by running:
    ```bash
    # Neogreen
    spicetify config current_theme Neogreen
    spicetify config color_scheme Neogreen
    spicetify apply
    ```

### Extra

The `_Extra` folder contains additional resources for tweaking the look of
Spotify. More info in its [README](./\_Extra/README.md).

## Contributions

We've set up a separate document for our [contribution guidelines](./CONTRIBUTING.md).

## Troubleshooting

Do not open issues for general support questions as we want to keep GitHub issues for bug reports and feature requests. If you find problems when using or installing these themes, or you need help in modifying a theme then ask for suggestions on the [subreddit](https://www.reddit.com/r/spicetify/) or on the [Discord Server](https://discord.com/invite/VnevqPp2Rr).

Use GitHub issues ONLY for bugs and requesting new features.

If you are unsure about which channel to use, go for Reddit or Discord.

## Useful resources

*   [Spicetify theme without free version UI elements (e.g. "Upgrade" button)](https://github.com/Daksh777/SpotifyNoPremium)
*   [DribbblishDynamic theme for v2](https://github.com/JulienMaille/dribbblish-dynamic-theme)
