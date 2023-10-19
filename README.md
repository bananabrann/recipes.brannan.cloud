## 🔧 Installation

### Requirements

- Node.js
- Visual Studio Code

### Install for local development

Install project dependencies.

```bash
npm install
```

Once you've installed dependencies, start a development server.

```bash
npm run dev
```

When the server is running, copy and paste the URL provided by SvelteKit.

> Pro tip: `npm run dev -- --open` starts the server and runs at the same time.

> Pro tip 2: You can also press 'o' to open your browser at the URL.

### Run code formatting

Run your code without making file changes:

```bash
npx prettier --check .
```

Run your code and make file changes:

```bash
npm run format
```

## 💡 Git Tips

Remember what we learned, and don't be afraid to reference [the git cheat sheet](https://files.brannan.cloud/docs/github-git-cheat-sheet.pdf) (https://files.brannan.cloud/docs/github-git-cheat-sheet.pdf).

> Always double check your branch (`git status` or `git branch`) prior to committing! Also, getting in the habit of pulling changes (`git pull origin branch-name`) might save you a lot of headache in the future.

> We have noticed that modifications to files we were not working on occur when we run the ‘prettier’ command. We don’t want to stage, commit, and then push them. So, after you stage, commit, and then push your specific files you are working on, you will want to synchronize your state with your repo. A really good way to accomplish this is to run (`git reset HEAD --hard`). Keep in mind this will delete all changes you made, so make sure you have finished pushing your committed changes that you want to keep.

## 📢 Asking for help

You can obviously DM me on Teams. However, I might not see it if it's during off-hours. You can also [open an issue on this repo](https://github.com/bananabrann/recipes.brannan.cloud/issues) or **comment on your draft PR** with your question.
