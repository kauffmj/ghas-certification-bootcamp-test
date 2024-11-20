
<h1 align="center">GitHub Advanced Security Bootcamp - Secret Scanning</h1>
<p align="center">
  <a href="#mega-prerequisites">Prerequisites</a> •  
  <a href="#books-resources">Resources</a>
</p>

> This bootcamp is designed to help familiarize you with GitHub Advanced Security's (GHAS) secret scanning feature so that you can better understand how to use it in your own repositories.

## :mega: Prerequisites
To participate in the workshop you need a GitHub account **(ARE THE REST OF THESE PREREQUISITES NEEDED? [Can't we make this repo a public template?])** and need to be invited to the workshop organization [ghas-bootcamp](https://github.com/ghas-bootcamp). If your repository hasn't been automatically created in the workshop organization, either click `Use this template` and create a repository under this organization, or create a new repository and push a copy of the `ghas-bootcamp` repository to an organization with GHAS enabled.

```bash
git clone https://github.com/ghas-bootcamp/ghas-bootcamp.git
cd ghas-bootcamp
git remote set-url origin git@github.com:{org-or-username}/{repo-name}.git
```

example: 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

## 🏫 Agenda

We will go over the following topics:

<details>
<summary>Day one </summary>

#### Secret scanning: [link](exercises/lab%202%20-%20secret-scanning.md)
- [x] Enable secret scanning
- [x] Commit a secret to the repository
- [x] Review secrets that have been identified by secret scanning
- [x] Close a secret scanning alert
- [x] Enable secret scanning push protection to prevent secrets from being written to the repository
- [x] Attempt to commit a secret, but have that commit stopped by push protection
- [x] Bypass push protection

</details>

## :books: Resources
- [About secret scanning](https://docs.github.com/en/github/administering-a-repository/about-secret-scanning)
- [Secret scanning API](https://docs.github.com/en/rest/reference/secret-scanning)
