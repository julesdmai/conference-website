# Frontend Masters CSS Foundations
Welcome to Frontend Masters CSS Foundations! You can find the course information [here](https://frontendmasters.com/workshops/css-foundations/).

# How To Follow Along
There are seven chapters to this course. You can find the slides for each chapter below.
1. [Introduction](https://www.canva.com/design/DAFk_lOWyQM/u7_uMrdicDOOdzj3N6HOzQ/edit?utm_content=DAFk_lOWyQM&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
2. [Foundation](https://www.canva.com/design/DAFlCSDDgpQ/SDXgAIa1OkXWjY8oBMKrRg/edit?utm_content=DAFlCSDDgpQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
3. [Header](https://www.canva.com/design/DAFlCeLitYw/jhPF7rA3OuESMVLFzRV60w/edit?utm_content=DAFlCeLitYw&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
4. [Home](https://www.canva.com/design/DAFlCcI_Gns/DvwUTgPnUk-V-TSJEBMNqQ/edit?utm_content=DAFlCcI_Gns&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
5. [Speakers](https://www.canva.com/design/DAFlCcF86Ho/QZYO-9LPcspRNa5IxzvOqw/edit?utm_content=DAFlCcF86Ho&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
6. [Responsive Layout](https://www.canva.com/design/DAFlCbiJBRQ/mIVsezoFbEAWF85IEXZXgA/edit?utm_content=DAFlCbiJBRQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
7. [Wrap Up](https://www.canva.com/design/DAFlCcp0Dy0/d9hj1Nr6OnWcyc4Ma_6n0A/edit?utm_content=DAFlCcp0Dy0&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

You can view the design files for our project website [here](https://www.figma.com/file/LEzNgBz63KLExeHNUyLCwH/FEM-CSS?type=design&node-id=0-1).
![Figma showing project](./readme-images/figma.png)

To use this repository, complete the following steps:
1. Fork this repository
![Create a fork from this repo by clicking the fork button](./readme-images/fork.png)
2. Be sure your account name is listed, and **uncheck the 'Copy the `main` branch only' checkbox** or you won't fork the chapter branches. Then click the Create Fork button.
![Select your account from the owner dropdown and uncheck the copy main branch only button, then click create fork.](./readme-images/create-fork.png)
3. Once the fork is completed you'll see it on your profile.
![View your fork on your account](./readme-images/view-fork.png)
4. Clone your forked repository by clicking the green Code button and copying the HTTPS URL.
![Clone your forked repository by clicking the green Code button and copying the HTTPS URL.](./readme-images/clone.png)
5. Open your terminal and navigate to a location of your choice on your personal computer that you want to save this repository. I always select my desktop. Then type `git clone` followed by the HTTPS URL you just copied.
```
cd Desktop
git clone [HTTPS url]
```
![Use the terminal to clone the repo](./readme-images/terminal.png)

Optionally you can use [GitHub Desktop](https://desktop.github.com/) if you prefer a UI to work with Git.  
6. Open the cloned repository in your code editor of choice. I use [Visual Studio Code](https://code.visualstudio.com/).  
7. Once you have the GitHub repository forked and cloned, you should start on the main branch. I recommend writing all of your code on the main branch, however if you get stuck or lost, each branch corresponds to the final state after the completed chapter. The branch order is as follows:
```
main
 |_ foundation
    |_header
	|_ home
	  |_ speakers
            |_ responsive-layout
```
To check out a new branch run `git checkout [branch-name]` (i.e. `git checkout home`)

## Editor Settings
Below are the visual settings I use in my code editor.
- **Font**: I’m using the font [Dank Mono](https://philpl.gumroad.com/l/dank-mono) with font ligatures. It’s a paid font for 24 GBP. I also recommend [Fira Code](https://github.com/tonsky/FiraCode) which is free.
![Dank Mono](./readme-images/dank-mono.png)
![Fira Code](./readme-images/fira-code.png)
- **Theme**: I’m using the  Material - Operator Mono/Italic theme.
![Theme](./readme-images/theme.png)
- **Plugins**: There are some plugins I recommend installing with VSCode. You can add plugins from the Extensions Marketplace tab in the left navigation.
![Use the extensions marketplace to add two plugins](./readme-images/extensions.png)
- **Live Server**: Hot reloads HTML pages when we save files.
![Live Server](./readme-images/live-server.png)
- **Prettier**:Formats our code when we save our files.
![Prettier](./readme-images/prettier.png)
- **Color Highlight**: Styles CSS colors.
![Color Highlight](./readme-images/color-highlight.png)

To get Prettier to work properly I had to add a few configurations in my `settings.json` file. To open this file press `command + p` on Mac, and enter `Preferences: Open Workplace Settings (JSON)`. Enter the following in the `settings.json` file and save.

```json
{
    "editor.formatOnSave": true,
    "editor.formatOnPaste": true,
    "editor.formatOnType": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
    }
}
```

# Sources
- Flat Icon

## Photos
- https://unsplash.com/photos/WYE2UhXsU1Y
- https://unsplash.com/photos/iEEBWgY_6lA
- https://unsplash.com/photos/mpDV4xaFP8c
- https://unsplash.com/photos/SJvDxw0azqw
- https://unsplash.com/photos/QJEVpydulGs
- https://unsplash.com/photos/p5BoBF0XJUA
