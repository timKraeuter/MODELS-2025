There are no requirements to execute the use case described in the paper besides a functioning maude installation:

1. **Install Maude** 3.5 or higher according to the [installation instructions](https://maude.cs.illinois.edu/wiki/Maude_download_and_installation).
   To run Maude on Windows, we recommend the [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/en-us/windows/wsl/install).
   - Link to the Maude [GitHub Artifacts](https://github.com/maude-lang/Maude/releases/tag/Maude3.5). 
   - Additionally, we provide a copy of Maude 3.5 locally in [./requirements](./requirements).
   - SHA-256 checksums for the Maude 3.5 binaries:
     ```text
     ❯ sha256sum ./requirements/Maude-3.5-linux-x86_64.zip
      e74cb8cf91b2d8b45440b54ef037180b581279358facf49f656e5b126eb7d1d3  ./requirements/Maude-3.5-linux-x86_64.zip
     ❯ sha256sum ./requirements/Maude-3.5-macos-arm64.zip
      c656ff4495a35fc544c7905eae80d9179a4b806ecbe3f948a7305f6e31e250d0  ./requirements/Maude-3.5-macos-arm64.zip
     ```

2. **Test your Maude installation** by running the following command (WSL or Linux):
```bash
maude
```

It should return the following (Version 3.5 or higher):

```text
❯ maude
                     \||||||||||||||||||/
                   --- Welcome to Maude ---
                     /||||||||||||||||||\
             Maude 3.5 built: Sep 25 2024 12:00:00
             Copyright 1997-2024 SRI International
                   Sun Mar 30 10:11:50 2025
```

You can use **q** to exit maude.