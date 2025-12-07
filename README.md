# GitHub Delete Confirmer

A Tampermonkey user script that simplifies the repository deletion process on GitHub. Instead of typing the full repository name to confirm deletion, this script provides a simple confirmation checkbox.

## Features

- **Automatic Detection**: Automatically detects the "Delete repository" modal.
- **Smart Confirmation**: Extracts the required repository name (e.g., `username/repo-name`).
- **One-Click**: Replaces the tedious typing requirement with a single checkbox: "I confirm I want to delete [repo-name]".
- **Safe**: Unchecking the box clears the input, preventing accidental deletion.
- **SPA Support**: Works seamlessly with GitHub's Turbo/PJAX navigation (no page reload required).

## Installation

1. Install the [Tampermonkey](https://www.tampermonkey.net/) extension for your browser.
2. Create a new script in Tampermonkey.
3. Copy the contents of `github-delete-confirmer.user.js` into the editor.
4. Save the script.

## Usage

1. Go to the **Settings** tab of any GitHub repository you own.
2. Scroll down to the **Danger Zone**.
3. Click **Delete this repository**.
4. Instead of typing the repository name, simply check the box that says **"I confirm I want to delete..."**.
5. The "Delete this repository" button will become active.

## Disclaimer

Use this script with caution. The typing requirement exists to prevent accidental deletions. By using this script, you are bypassing that safety check in favor of convenience. Double-check that you are deleting the correct repository before clicking the final button.

## License

MIT
