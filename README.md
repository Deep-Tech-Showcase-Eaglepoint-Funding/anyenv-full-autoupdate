<div align="center">
    <h1>anyenv Full-autoupdate</h1>
    <h4>Automatic update of anyenv plugins</h4>
</div>

<br>

## What is it

This plugin automatically updates your anyenv plugins.

This plugin needs [znz/anyenv-update](https://github.com/znz/anyenv-update.git) to work properly

## Installing

1. Clone this repository into `$ZSH_CUSTOM/plugins` (`~/.oh-my-zsh/custom/plugins`)

    ```bash
    git clone https://github.com/Deep-Tech-Showcase-Eaglepoint-Funding/anyenv-full-autoupdate.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/anyenv-full-autoupdate
    ```

2. Add the plugin to the Oh My Zsh plugin list in the `~/.zshrc` file:

    ```bash
    plugins=(... anyenv-full-autoupdate)
    ```

3. Start a new terminal session.

## Usage 🚀

The plugin **works completely automatically**.  
The update of all anyenv plugins is triggered the next time a new terminal session is opened, after the update of Oh My Zsh.  
The update frequency depends on the Oh My Zsh settings, by default every 13 days.  

## Manual start

If you still need to start the update manually, just type `omz update` in the terminal, wait for the Oh My Zsh update to finish and restart the terminal. 😎

## License

MIT © [Deep-Tech-Showcase-Eaglepoint-Funding](https://github.com/Deep-Tech-Showcase-Eaglepoint-Funding)
