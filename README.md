
<h1 align="center">GitHub Advanced Security Bootcamp - Secret Scanning</h1>

> This bootcamp is designed to help familiarize you with the GitHub Advanced Security (GHAS) secret scanning feature so that you can better understand how to use it in your own repositories.

## :mega: Prerequisites
To participate in the bootcamp you need a GitHub account. You should create a fork of this repository template, hosting it under your personal account and making it public.

## 🏫 Exercise

You should complete the following tasks:
- [ ] Enable secret scanning
      1. Understand that secret scanning does not need to be explicitly enabled since this is a public repository, and that the purpose of this step is to learn where the settings are so you can configure secret scanning for internal and private repositories if/when you obtain GHAS licenses.
      2. Copy the URL for this repository and open it in a new tab so you can complete this and the remaining steps while following the instructions in this README.
      3. Click on the "Settings" option toward the top of the page and then scroll down and click on "Code security" on the left-hand side of the page.
      4. Scroll down to the "Secret scanning" section and observe that a button is available for disabling this feature.
- [ ] Commit a secret to the repository
- [ ] Review secrets that have been identified by secret scanning
- [ ] Close a secret scanning alert
- [ ] Enable secret scanning push protection to prevent secrets from being written to the repository
- [ ] Attempt to commit a secret, but have that commit stopped by push protection
- [ ] Bypass push protection

## :books: Resources
- [About secret scanning](https://docs.github.com/en/github/administering-a-repository/about-secret-scanning)
- [Secret scanning API](https://docs.github.com/en/rest/reference/secret-scanning)
