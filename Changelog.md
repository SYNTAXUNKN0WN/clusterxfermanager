# Changelog

All notable changes to **ClusterXfer Manager** will be documented in this file.

## [1.3] - 2026-09-06

### Added
- File groups with custom names (right-click → Group selected files…)
- Collapsible groups and folders in the file list
- Files inside a group are split by parent folder (for example MagaShop and AwesomeAdminTools)
- Click a group or folder header to expand or collapse it
- Selecting a group or folder header sends all files in that group or folder
- Rename destination display names without changing the real folder or FTP path
- Updated Help menu with grouping and collapse instructions

### Improved
- File list starts collapsed so individual files are hidden until expanded
- Clearer file list layout for large sets of files

## [1.2] - 2026-08-13

### Added
- Code to catch more errors
- Discord link for faster support

## [1.1] - 2026-08-04

### Added
- Full FTP support (upload and download)
- FTP folder browser with path navigation
- Ability to add files and destinations from FTP servers
- Remember last used FTP credentials
- Parent folder name now shown next to filenames in the file list
- Share menu item (copies GitHub link to clipboard)
- Donation link in the About dialog
- Changelog menu item

### Improved
- Better display of file and destination lists
- More reliable file transfer with retry logic

## [1.0] - 2026-08-03

### Added
- Initial release
- Select multiple local files
- Select multiple local destination folders
- Push selected files to selected destinations
- Automatic saving and restoring of file and destination lists
- Basic activity log
- About and Help menus
