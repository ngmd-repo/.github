# Community Health Files

This repository contains default community health files for all projects in the ngmd-repo organization.

## Purpose

Community Health Files is a special GitHub repository that allows centralized management of community health and development process files for all repositories within an organization.

## Contents

This repository includes the following types of files:

### 📋 Issue and Pull Request Templates

- Issue creation templates
- Pull request templates
- Forms for different types of requests

### 📄 Community Documentation

- Code of Conduct (CODE_OF_CONDUCT.md)
- Contributing Guidelines (CONTRIBUTING.md)
- Security Policy (SECURITY.md)

### ⚙️ Configuration Files

- GitHub Actions workflows
- Process automation configurations

## How It Works

GitHub automatically applies files from this repository to all public repositories in the organization when the corresponding files are missing from the repository itself.

### File Priority:

1. Files in the repository itself (highest priority)
2. Files in the organization's `.github` repository
3. Files in the user profile's `.github` folder

## Repository Structure

```
.github/
├── ISSUE_TEMPLATE/          # Issue templates
├── PULL_REQUEST_TEMPLATE/   # Pull request templates
├── workflows/               # GitHub Actions
├── CODE_OF_CONDUCT.md       # Code of conduct
├── CONTRIBUTING.md          # Contributing guidelines
├── SECURITY.md              # Security policy
└── SUPPORT.md               # Support information
```

## Editing

To modify community health files:

1. Create a new branch
2. Make necessary changes
3. Create a pull request
4. After approval, changes will be applied to all organization repositories

## Additional Information

- [GitHub Documentation: Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
- [GitHub Documentation: About community profiles for public repositories](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/about-community-profiles-for-public-repositories)

---

**Note**: Changes in this repository affect all ngmd-repo organization projects. Please carefully review changes before applying them.
