hello-cli
--

## Usage

```sh
npx https://github.com/mitchallen/hello-cli
```

As of npm 7:

```sh
npm exec -- https://github.com/mitchallen/hello-cli
```

### Alias

Add this to ~/.bashrc or ~/.zshrc

```sh
alias hello="npm exec --yes -- https://github.com/mitchallen/hello-cli";
```

Replace ~/.bashrc with ~/.zshrc on Mac:

```sh
source ~/.bashrc 
```