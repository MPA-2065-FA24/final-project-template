# Setting Up Your Local Environment

## Install R and IDE
1. Navigate to [R-Studio](https://posit.co/download/rstudio-desktop/) then click `Download and Install R`. 
![Install R](images/install_r.png)
2. Install an integrated development environment (IDE)s. You can install **R Studio** at the same site. Alternatively,
you can install [VSCode](https://code.visualstudio.com/) as another popular option. Feel free to use whichever IDE you'd
like.

## Install Git

### Download Git

| Operating System | Instructions | Notes |
| --- | --- | --- |
| Max OS | [Download for macOS](https://git-scm.com/download/mac) | I'd recommend installing [homebrew](https://brew.sh/) then installing git |
| Windows | [Download for Windows](https://git-scm.com/download/win) | I think this also install git bash |

### Generate a new SSH key to add to Github

1. Open Terminal (MacOS) or Git Bash (Windows)
2. Paste the text below, replace the email with your email.
```shell
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
``` 
This creates a new SSH key. When you're prompted to "Enter a file in which to save the key", you can press **Enter** to
accept the default file location.

3. Feel free to press **Enter** for the following prompts.
```shell
> Enter passphrase (empty for no passphrase): [Type a passphrase]
> Enter same passphrase again: [Type passphrase again]
```

4. Follow [these instructions](https://docs.github.com/en/github-ae@latest/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account#adding-a-new-ssh-key-to-your-account)
to add a new SSH key to your Github Account.