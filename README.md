# Submodule Framework (SMF)

A Next JS framework experiment using git submodules to orchestrate multiple modules over multiple teams with the best possible DX.

## Getting Started

Once you clone the repository, you'll need to sync the submodules:

```
git submodule update --init --recursive
```

Make sure you have NVM installed to manage your current version of Node and NPM:

```
brew install nvm
```

Once NVM has been installed, navigate to the project's root directory and run:

```
nvm install
nvm use
```

Now install all of the project's dependencies via NPM:

```
npm install
```

Finally, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result. Hot reloading is set up to pull in changes whenever code is modified.

## Git Submodules

When you're on the parent directory, you can pull all submodule changes by running:

```
git pull --recurse-submodules
```

To add a new submodule, navigate to the parent directory and run:

```
git submodule add git@github.com:organization/your-repo.git
```
