# Text Environment

[![GitHub license](https://img.shields.io/github/license/FreakMegalodon/vscode_text_env)](https://github.com/FreakMegalodon/vscode_text_env) [![GitHub issues](https://img.shields.io/github/issues/FreakMegalodon/vscode_text_env)](https://github.com/FreakMegalodon/vscode_text_env/issues) [![GitHub forks](https://img.shields.io/github/forks/FreakMegalodon/vscode_text_env)](https://github.com/FreakMegalodon/vscode_text_env/network) [![GitHub stars](https://img.shields.io/github/stars/FreakMegalodon/vscode_text_env)](https://github.com/FreakMegalodon/vscode_text_env/stargazers)

Visual Studio Code remote develepment environment (dev container) for texts: markdown, txt and latex.

Includes this extensions:

```
james-yu.latex-workshop,
yzhang.markdown-all-in-one,
streetsidesoftware.code-spell-checker,
DavidAnson.vscode-markdownlint,
shd101wyy.markdown-preview-enhanced,
bierner.github-markdown-preview
```

## Instalation

```bash
mkdir my_article_folder
cd my_article_folder
git clone https://github.com/FreakMegalodon/vscode_text_env.git
mv vscode_text_env .devcontainer
```

## Usage

Open Visual Studio Code, press `F1` and select **Remote-Containers: Reopen in Container**.

Wait until Docker and Code download and setup your environment. The next type you enter this remote window again it'll be much faster.

To exit remote mode (dev container), hit `F1` again and select **Remote-Containers: Open Folder Locally**.

To add more extensions, edit the devcontainer.json file.

## Contriuting

Pull requests are welcome.

## License

[MIT](https://choosealicense.com/licenses/mit/)