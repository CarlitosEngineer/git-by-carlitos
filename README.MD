# Learn Git with Carlitos

![Header](./src/Git_01.webp)

Welcome to this repository, created to help you understand and improve your Git skills in your development projects. Here you will find notes, guides, and practical tips about Git, aimed at establishing a solid foundation for effective repository management.

## General Objectives

- Establish a well-organized and optimized development environment using Git.

## Specific Objectives

1. **Basic Git Setup**
   - Download and install Git on your machine.
   - Configure your user settings and Git preferences.

2. **Repository Management**
   - Create, clone, push, and manage repositories on GitHub.
   - Understand the Git workflow, including commits, pull requests, and merges.

3. **Branching Models**
   - Learn about different branching models for various types of projects.
   - Understand Git Flow, GitHub Flow, and other popular branching strategies.

## Resources and References

- Visit my YouTube channel for video tutorials on Git and development: [Developing With Carlitos](https://www.youtube.com/@DevelopingWithCarlitos).
- [Download Git](https://git-scm.com/downloads) – Official page to download Git.
- [Generate and Configure SSH Keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) – Guide for generating an SSH key and adding it to your SSH agent.

### Installation Steps

1. **Download Git:**
   - Go to: https://git-scm.com/downloads
   - Download and install the version for your OS. Use default options.
   
2. **Check current configuration:**
   - Use `git config --list` to see the current configuration.
   
3. **Set up your user details:**
   - Set global username and email using:
     - `git config --global user.name "LearnWithCarlitos"`
     - `git config --global user.email "LearnWithCarlitos@gmail.com"`

4. **Generate an SSH key:**
   - Generate an SSH key using your email for identification:
     - `ssh-keygen -t ed25519 -C "LearnWithCarlitos@gmail.com"`
   - Locate the file in the `.ssh` folder, e.g., `C:\Users\YourUserExamplePc\.ssh`.

5. **Add your SSH public key to GitHub:**
   - Add the generated SSH key to your GitHub account in the SSH settings.

6. **Verify the connection:**
   - Use the command `` to verify the SSH connection to GitHub.

---

### 01 - Configuration Commands

| Command                                    | Description                                                                |
| :----------------------------------------: | :------------------------------------------------------------------------- |
| `git config --list`                        | Displays the current Git configuration                                     |
| `git config --global user.name "YourUserNickName"` | Sets the global username                                         |
| `git config --global user.email "YourUserEmailName@Email.com"` | Sets the global email address                               |
| `ssh-keygen -t ed25519 -C "YourUserEmailName@Email.com"` | Generates an SSH key using the email for identification |
| `ssh -T git@github.com`                    | Verifies SSH connection with GitHub                                        |
| `C:\Users\YourUserExamplePc\.ssh`          | Default SSH key location on Windows                                        |
| `config` (SSH config file)                 | Custom SSH configuration file for multiple hosts                           |
