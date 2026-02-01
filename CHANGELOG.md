# Changelog

All notable changes to ClueSolo will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [9.0.0] - 2026-02-01

### Added
- Classic Clue-style deduction grid with player columns
- Note-taking field under each card in the grid
- Auto-populated hints in Coach Mode based on AI difficulty
- Separate game mode selection (Normal/Coach) independent of player count
- Comprehensive code documentation with section markers
- Table of Contents for easy code navigation
- Quick reference guide for customization
- Color customization guide in CSS
- LocalStorage persistence for grid state and notes

### Changed
- Coach mode now works with any number of opponents (2-5)
- Deduction log now only visible in Smart/Sherlock modes
- Focus player column now labeled "Own" for clarity
- Improved grid layout with better mobile responsiveness
- Reorganized setup screen with three separate dropdowns

### Fixed
- Metadata scope issue in coach mode rendering
- Grid state persistence across new games
- Player column header generation for coach mode

### Technical
- Added `[SECTION X]` markers throughout code
- Improved code comments for non-technical users
- Refactored renderObserverCasebook for better clarity
- Added loadClueGrid/saveClueGrid/clearClueGrid functions

## [8.x] - 2025

### Previous Iterations
- Various improvements and bug fixes
- AI difficulty refinements
- UI enhancements
- Observer/Coach mode development

## [1.0] - Initial Release

### Added
- Core Clue/Cluedo game mechanics
- AI opponents with multiple difficulty levels
- Board movement and suggestion system
- Accusation and win/loss logic
- Basic UI and controls

---

## Version Number Format

ClueSolo uses Semantic Versioning (MAJOR.MINOR.PATCH):

- **MAJOR**: Incompatible changes or major new features
- **MINOR**: New features, backward compatible
- **PATCH**: Bug fixes, backward compatible

## Categories Used

- **Added**: New features
- **Changed**: Changes to existing functionality
- **Deprecated**: Soon-to-be removed features
- **Removed**: Removed features
- **Fixed**: Bug fixes
- **Security**: Security fixes
- **Technical**: Code quality, refactoring, documentation

## Links

- Repository: https://github.com/YOUR-USERNAME/REPOSITORY-NAME
- Issues: https://github.com/YOUR-USERNAME/REPOSITORY-NAME/issues
- Releases: https://github.com/YOUR-USERNAME/REPOSITORY-NAME/releases
