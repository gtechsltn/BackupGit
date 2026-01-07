# Backup Git
* [BackupGit](https://github.com/gtechsltn/BackupGit)
* [GitBackup](https://github.com/gtechsltn/GitBackup)
* [Python GitHub Backup](https://github.com/josegonzalez/python-github-backup)
* [Python GitHub Backup](https://github.com/gtechsltn/python-github-backup)
* [GitHub Backup Utils](https://github.com/github/backup-utils)
* [My Gitea Backup & Restore Scripts](https://gist.github.com/sinbad/4bb771b916fa8facaf340af3fc49ee43)
* [My Gitea Backup & Restore Scripts](https://gist.github.com/gtechsltn/181d11b8d0f9a303c1f96c2aad4ced44)

# GitHub Backup
* https://docs.github.com/en/get-started/archiving-your-github-personal-account-and-public-repositories/requesting-an-archive-of-your-personal-accounts-data
* https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens
* https://github.com/settings/tokens/new 

# Python
* [Farmore](https://github.com/miztizm/farmore)
  * Python CLI tool for backing up GitHub repositories

## ✨ Features

### 🔄 Repository Management
- **Bulk backups** - Clone all repos for a user or organization in one command
- **Single repo backups** - Backup individual repositories with the `repo` command
- **Repository search** - Search GitHub and clone matching repositories by keyword
- **Smart updates** - Automatically pulls updates for existing repositories
- **Parallel processing** - Fast backups with configurable worker threads
- **SSH/HTTPS support** - Tries SSH first, falls back to HTTPS with token
- **Bare/Mirror clones** - Use `--bare` flag for true 1:1 repository backups
- **Git LFS support** - Use `--lfs` flag for repositories with large files
- **Name regex filtering** - Filter repositories by name pattern with `--name-regex`
- **Incremental backups** - Track backup state with `--incremental` flag

### 📊 Data Export
- **Issues export** - Export all issues to JSON/YAML with optional comments
- **Pull requests export** - Export PRs with metadata and comments
- **Workflows backup** - Backup GitHub Actions workflows and run history
- **Releases download** - Download releases with metadata and binary assets
- **Wiki backup** - Clone repository wikis as git repositories
- **Labels export** - Backup repository labels with colors
- **Milestones export** - Backup milestone configuration and progress
- **Gists backup** - Clone all your GitHub gists
- **Attachments download** - Download images/files from issues and PRs

### 🔐 Access & Security
- **Private repository support** - Full access with GitHub Personal Access Tokens
- **Organization repos** - Backup all organization repositories
- **Starred & watched repos** - Mirror repositories you've starred or are watching
- **Secrets export** - Export repository secret names (values are never exposed)
- **Followers/Following** - Export user's social connections
- **Webhooks export** - Backup webhook configurations

### 🎯 Advanced Features
- **Flexible filtering** - By visibility (public/private/all), forks, archived status
- **Rate limit handling** - Automatic retries with exponential backoff
- **Organized structure** - Clean directory organization separating code from data
- **Cross-platform** - Works on Linux, macOS, and Windows
- **Beautiful CLI** - Powered by Typer and Rich with progress bars
- **GitHub Enterprise** - Support via `--github-host` flag
- **Discussions backup** - Export repository discussions (GraphQL API)
- **Projects backup** - Export Projects v2 data (GraphQL API)

### Features
- 1. **Discovery** - Uses GitHub API to find repositories
- 2. **Filtering** - Applies visibility, fork, and archived filters
- 3. **Parallel Processing** - Processes multiple repos simultaneously
- 4. **Smart Cloning** - Tries SSH first, falls back to HTTPS
- 5. **Progress Reporting** - Real-time progress with rich output
- 6. **Summary** - Final statistics and error reporting

### Key Features
- **Incremental backups** - Updates existing repos, clones new ones
- **Error resilience** - Continues even if individual repos fail
- **Rate limit aware** - Handles GitHub API limits automatically
- **Organized output** - Auto-categorizes by type

# Git Backup
* https://jsmailes.co.uk/blog/2023/04/04/git-backups.html

# Using GO
* [docker-volume-backup](https://github.com/offen/docker-volume-backup)
  * Backup Docker volumes locally or to any S3, WebDAV, Azure Blob Storage, Dropbox, Google Drive or SSH compatible storage.
* [Git Backup](https://github.com/ChappIO/git-backup)
* [Gickup](https://github.com/cooperspencer/gickup)
* [Ghorg](https://github.com/gabrie30/ghorg)
  * Quickly clone or backup an entire org/users repositories into one directory - Supports GitHub, GitLab, Bitbucket, and more 🐇🥚

# Gitea Mirror
* [Gitea Mirror](https://github.com/RayLabsHQ/gitea-mirror)
  * Gitea Mirror auto-syncs GitHub repos to your self-hosted Gitea/Forgejo, with a sleek Web UI and easy Docker deployment.
    * Automatically mirror repositories from GitHub to your self-hosted Gitea instance.
  * Git LFS support

# Code with a cup of Coffee
* https://codebrew.vn/
* https://brew.dev/
