# gh markdown-preview

GitHub CLI extension to preview your markdown similar to the style of GitHub :octocat:

**gh markdown-preview** is a [GitHub CLI](https://cli.github.com) extension to preview your markdown such as **README.md**. The `gh markdown-preview` commnad start a local web server to serve your markdown document file with a GitHub style. **gh markdown-preview** show the HTML got from GitHub official markdown API with the CSS extracted from GitHub web site. The styles are almost the same!

You can see rendered README before uploading to GitHub!

## Features

- **NO-dependencies** - You need `gh` command only.
- **Zero-configuration** - You don't have to set the GitHub access token.
- **Looks exactly the same** - You can see same as GitHub.
- **Live reloading** - You don't need reload the browser.

## Screenshots

Open your browser:

![Screenshot of gh markdown-preview](https://user-images.githubusercontent.com/10682/138411417-dd12a831-bacc-4b05-a33d-47d3f6b45483.png)

Live reloading:

![Screenshot of gh markdown-preview](https://user-images.githubusercontent.com/10682/138750423-ae7940cb-205e-4832-8e6a-af6f43c0f666.gif)

## Installation

```
$ gh extension install yusukebe/gh-markdown-preview
```

Upgrade:

```
$ gh extension upgrade markdown-preview
```

## Usage

The usage:

```
$ gh markdown-preview README.md
```

Or this command will detect README file in the directory automatically.

```
$ gh markdown-preview
```

Then access the local web server such as `http://localhost:3333` with Chrome, Firefox, or Safari.

Available options:

```text
-p, --port     TCP port number of this server (default: 3333)
-r, --reload   Enable live reloading (default: false)
```

![gh markdown-preview command](https://user-images.githubusercontent.com/10682/138411333-c1b5ccb9-d56a-478c-9f20-4c71cfe1536a.png)

## Related projects

- GitHub CLI <https://cli.github.com>
- Grip <https://github.com/joeyespo/grip>
- github-markdown-css <https://github.com/sindresorhus/github-markdown-css>

## Author

Yusuke Wada <http://github.com/yusukebe>

## License

Distributed under the MIT License.
