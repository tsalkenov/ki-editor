# Changelog

# [0.0.13]

- Add support for showing Info from Ki, which includes:
    - Generic error messages
    - Diagnostic messages
    - Keymap Legend

# [0.0.12]

-   Make "Go to location" from Ki works in VS Code
    -   This is necessary for Global operations (such as Global Search) to work

# [0.0.11]

-   Fix buffer content desync issues

# [0.0.7] - 2025-05-30

-   Handle LSP requests from Ki in vscode
    -   Go to Definition
    -   Hover
    -   Go to References
    -   Go to Type Definition
    -   Go to Declaration
-   Fix jump not working after Go to Definition

# [0.0.6] - 2025-05-28

-   Sync marks from ki
-   Git hunk fix due to incorrect cwd
-   handle PromptOpened events. Enables search, filter, and other prompt related Ki features.

# [0.0.5] - 2025-05-19

Initial packaging with statically linked binaries.
