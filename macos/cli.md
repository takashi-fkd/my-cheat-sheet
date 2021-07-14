# MacOS CLI

- Xcode

  ```bash
  ## Show current version
  xcodebuild -version
  ```

- Homebrew

  ```bash
  brew doctor
  ```

- Update software

  ```bash
  ## Show update candidate
  softwareupdate --list
  
  ## Update a specified software
  softwareupdate --install "Command Line Tools for Xcode-12.4"
  
  ## Update all software
  softwareupdate --install -a
  ```
