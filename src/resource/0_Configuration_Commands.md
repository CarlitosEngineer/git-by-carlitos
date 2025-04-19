### 00 - Configuration Commands

| Command                                    | Description                                                                |
| :----------------------------------------: | :------------------------------------------------------------------------- |
| `git config --list`                        | Displays the current Git configuration                                     |
| `git config --global user.name "YourUserNickName"` | Sets the global username                                         |
| `git config --global user.email "YourUserEmailName@Email.com"` | Sets the global email address                               |
| `ssh-keygen -t ed25519 -C "YourUserEmailName@Email.com"` | Generates an SSH key using the email for identification |
| `ssh -T git@github.com`                    | Verifies SSH connection with GitHub                                        |
| `C:\Users\YourUserExamplePc\.ssh`          | Default SSH key location on Windows                                        |
| `config` (SSH config file)                 | Custom SSH configuration file for multiple hosts                           |