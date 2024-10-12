# tedxaubg-website-25

## Setting up the project

> Before the setup process, make sure you have an SSH key stored locally and shared with your GitHub account. See [Generating an SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) and [Linking an SSH key with GitHub](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) (Recommended)

### 1. Clone the project over SSH

```bash
git clone git@github.com:TEDxAUBG/tedxaubg-website-25.git
```

### 2. Navigate to the project root and install nvm.

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.1/install.sh | bash
```

OR

```bash
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.1/install.sh | bash
```

> For more info visit: [https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating](https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating)

### 3. Restart your shell

```bash
sudo exec $SHELL
```

### 4. Download Node 22.9.0 using nvm

```bash
nvm install 22
```

### 5. Navigate to the root directory of the project and install the Node packages

```bash
npm install
```

## How to work on a feature and open a Pull Request?

1. Choose an issue you want to work on (e.g. [#11 - Optimizations](https://github.com/AUBGTheHUB/monolith/issues/11))
2. Create a new branch by running the following command:

```shell
git checkout -b "11-specific-optimizations"
```

3. When commiting, place the issue number at the beginning of the commit message

```shell
git add .                               # be careful if something important is not gitignored
git commit -m "#11 Added a new feature"
```

4. Push your updates to the remote branch

```bash
git push --set-upstream origin 11-Optimizations
```

5. Contribute 🤝 (Open a Pull Request towards the main branch)

- Reference the issue in the title
- Write a brief discription of what you have worked on

---

## CODEOWNERS

After finishing implementing a feature don't forget to add yourself to the [CODEOWNERS](.github/CODEOWNERS) 😎
