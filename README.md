# Microsoft_Terminal
Open Source
# Open Source Contributions & Systems Log

## PR #1: Microsoft Terminal (Windows Terminal)
- **Repository:** microsoft/terminal
- **PR Number:** #20804 (Resolves Issue #20803)
- **Status:** In Review
- **Core Tech:** C++, UTF-8/UTF-16 encoding, URI Percent-Decoding, Win32 API.
- **Summary:** Fixed an issue where Ctrl+clicking file URI links containing non-ASCII characters failed in `ShellExecuteW`. Implemented `_GetLaunchPathForUri` to unescape percent-encoded UTF-8 bytes into wide characters and normalize forward slashes to backslashes before dispatching to the OS.
- **Key Takeaways:** Real-world Git fork/PR flow, addressing maintainer review comments, string byte representations, and URI path parsing.
