# SSnippets

## Content
- [About](#About) – why and how?
- [Quickstart](#Quickstart) – how to integrate SSnippets into your project.
- [Customization](#Customization) – how to customize SSnippets to your needs.
- [Account sync](#Account-sync) – how to sync SSnippets across multiple devices.

## About
SSnippets offers easily customizable snippets without unnecessary complexity.

Take whatever you need, paste it into your project and stop slowing VSCode down with hundreds of snippets you will never use from libraries you will forget you even installed.

## Quickstart
To enable SSnippets simply copy files with types of snippets that you need to the `.vscode` directory of your project.

<p align="center"><img src="https://github.com/user-attachments/assets/041f87e9-8b20-4953-8acc-38293dc21dac" width="40%"></p>

## Customization
Since SSnippets is not a library, it is extremely easy to customize.

Simply open a `.code-snippets` file containing a snippet that you want to customize and adjust its properties to your needs.

What do all these properties mean? The important ones you should focus on are:
* `"prefix"` – what you have to write in your editor for the snippet suggestion to appear (e.g. if you type _ssref_, VSCode will most likely suggest a snippet with name _ss-useRef_).
* `"body"` – content of the snippet. This is where the magic happens (you can find more about snippet syntax <a href="https://code.visualstudio.com/docs/editor/userdefinedsnippets#_snippet-syntax">here</a>).
* `"scope"` – what kind of files should the snippets be suggested in (e.g. _"javascript,html"_ will cause the snippet to be suggested in _.js_ and _.html_ files).

## Account-sync
To sync SSnippets across multiple devices using the same account you first need to have your VSCode settings sync turned _on_.

<p align="center"><img src="https://github.com/user-attachments/assets/53525fbb-eebb-4612-a076-bf4246f3a49d" width="40%"></p>

Then:
* Press `ctrl+shift+p`.
* Look for an option `Snippets: Configure snippets` and select it.
* Select a file type that you want to use the snippets for (eg. _typescriptreact_ to enable snippets only in _.tsx_ files).
* Paste selected SSnippets to the JSON file and save it.
