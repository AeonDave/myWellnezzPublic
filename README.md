# myWellnezz

Desktop application for registering in gym classes that use the myWellness management system.
The project is compiled with pyInstaller in order to be portable for windows linux and macos.

![Alt text](mw.png?raw=true "myWellnezz")


# Changelog
### 1.1.1 - 2023-02-27
#### Fixed
- Fixed bug where registering for a class would also unregister the same class.
#### Added
- Added key "R" for refreshing the page.
- Improved privacy by encrypting the configuration.

### 1.1.0 - 2023-02-15
#### Added
- Refactor with asyncio and complete thread overhaul
- Auto booking when in waiting-list
- Stop auto booking when out of waiting-list
- Gym selector with same call as the app
- Multi-user
- Privacy protected config

### 1.0.5 - 2022-12-5
#### Fixed
- Minor fix and killswitch updated

### 1.0.4 - 2022-12-5
#### Fixed
- Versions and Update

### 1.0.3 - 2022-12-2
#### Changed
- Refactored main class and models

### 1.0.2 - 2022-11-28
#### Added
- Config generator
  
### 1.0.1 - 2022-11-22
#### Added
- Added user selection
#### Fixed
- Fixed user email regex
  
### 1.0.0 - 2022-11-15
#### Added
- First release
