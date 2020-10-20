# Git Before Github

This repository is a tool to practice `git` collaboration without using Github.

## Usage
1. Clone this repository
2. Add your name to the [CONTRIBUTORS.txt](./CONTRIBUTORS.txt) file. and create a commit
3. Create a patch
    ```sh
    git format-patch HEAD~..HEAD
    ```
4. Add your `smtp` or `imap` details in the `~/.gitconfig`
5. Send the patch using `git send-email` or `git imap-send` or just send an email manually with the patch file as attachment.

## License
MIT