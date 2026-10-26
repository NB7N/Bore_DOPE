BORE DOPE

Firearm, Suppressor, Maintenance, Range, Reloading and DOPE Data Manager for Android

Bore DOPE is a private Android application for managing firearm and suppressor records, tracking range activity and maintenance, recording ammunition and reloading information, and maintaining editable DOPE cards for individual firearms and loads.

The goal is to provide a practical, organized field and collection-management tool without requiring an online account, subscription, or cloud service.

======================================================================
CORE FEATURES
======================================================================

FIREARM INVENTORY

Store and manage firearm information including:

- Manufacturer
- Model
- Caliber
- Serial number
- Purchase date
- Pickup date
- Purchase price
- Insurance/replacement value
- New / Used / Not Set purchase condition
- Notes
- Favorite status
- Sold/archive status

SUPPRESSOR INVENTORY

Maintain suppressor records separately while still tracking their use and total rounds fired.

RANGE AND ACTIVITY HISTORY

Each shooting session can be recorded as a separate activity entry.

Activity records can include:

- Date
- Rounds fired
- Notes

Bore DOPE maintains a running round count while preserving the individual sessions that produced that total.

History entries open in a read-only view first to help prevent accidental edits. An Edit button opens the editable version when changes are actually needed.

CLEANING AND MAINTENANCE HISTORY

Cleaning is stored as individual dated records instead of only as a single counter.

Each cleaning record can include:

- Date
- Notes

Bore DOPE maintains a running cleaning total and keeps the individual cleaning history available for review.

DOPE CARDS

Each firearm can have multiple DOPE cards for different ammunition, factory loads, or handloads.

A new DOPE card begins with one range row. Additional rows can be added as needed instead of filling the screen with unused distances.

DOPE card information can include:

- Bullet
- Load
- Load performance in MOA
- Adjustment unit
- Target name
- Distance
- Elevation adjustment
- Windage adjustment

MRAD is used for milliradian adjustments.

The DOPE system is designed as a user-entered reference system. Bore DOPE does not invent ballistic data or present automatically fabricated values as measured DOPE.

RELOADING AND LOAD DATA

Each DOPE card can maintain its own load-specific information, including:

- Bullet
- Bullet weight
- Powder
- Powder charge
- Primer
- Brass / case
- Cartridge overall length
- Ballistic coefficient
- G1 or G7 BC model
- Load performance in MOA
- Notes

CHRONOGRAPH DATA

Chronograph information can be stored with each load, including:

- Average velocity
- Standard deviation (SD)
- Extreme spread (ES)
- Minimum velocity
- Maximum velocity
- Chronograph shot count

Average velocity and SD are displayed directly on the DOPE card for quick reference.

COLLECTION SUMMARY

Bore DOPE provides collection-wide totals including:

- Total firearms
- Total suppressors
- Total firearm rounds fired
- Total suppressor rounds fired
- Total cleanings
- Total collection value

For collection value, Bore DOPE uses the insurance/replacement value when one has been entered. Otherwise, it falls back to the item's purchase price.

======================================================================
BACKUP AND RESTORE
======================================================================

Bore DOPE supports manual and automatic backups.

The application keeps:

- The latest 3 automatic backups
- The latest 3 manual backups

Backup controls include:

- Choose Automatic Backup Folder
- Create Manual Backup
- Open Backup Folder
- Restore Backup

Backups include firearm, suppressor, activity-history, cleaning-history, DOPE-card, load-data, and chronograph information.

======================================================================
DATA SAFETY
======================================================================

Bore DOPE uses an Android Room database with explicit database migrations so application updates can preserve existing information.

The project is designed so normal upgrades do not require deleting the existing application or losing the user's collection data.

Editing screens are designed to reduce accidental data loss. Important edit dialogs require an intentional Save, Cancel, or deliberate Android back action rather than disappearing from an accidental outside tap.

======================================================================
PRIVACY
======================================================================

Bore DOPE is intended as a local record-keeping application.

It does not require a Bore DOPE account or subscription to maintain collection information.

Users are responsible for protecting their phone and any exported backup files containing personal records.

======================================================================
INSTALLATION
======================================================================

Download the current signed APK from the GitHub Releases section.

Android may require permission to install applications from the browser or file manager being used.

Future Bore DOPE versions signed with the same release identity can install over earlier versions while preserving application data.

======================================================================
BUILDING FROM SOURCE
======================================================================

Bore DOPE is a native Android project.

On Windows:

1. Download or clone the source repository.
2. Open the project folder.
3. Double-click:

   BUILD RELEASE.bat

The build system checks or prepares the required Android development tools, runs tests and lint checks, builds the signed APK and AAB, and packages the public release files.

Successful release files are placed in:

   RELEASE

The developer should not normally need to manually configure Java, Gradle, Android SDK paths, or signing information.

======================================================================
BUILD DIAGNOSTICS
======================================================================

Each build creates diagnostic information under:

   BUILD_LOGS

If a build fails, a timestamped diagnostic ZIP is created containing useful build, Gradle, lint, test, environment, Room-schema, and configuration information.

Private signing keys and passwords are excluded.

======================================================================
RELEASE CONTENTS
======================================================================

A completed Bore DOPE release may include:

- Signed Android APK
- Google Play AAB
- Clean source ZIP
- README
- GitHub_README.txt
- GitHub_README.html
- CHANGELOG / UPDATES
- Package/version information
- SHA-256 hashes
- Build diagnostics when applicable

======================================================================
DEVELOPMENT STATUS
======================================================================

Bore DOPE is under active development and testing.

Early builds should be treated as development software. Back up important records before installing test versions.

Testing feedback and reproducible bug reports are welcome.

======================================================================
DISCLAIMER
======================================================================

Bore DOPE is an inventory, maintenance, range-log, reloading-data, chronograph-data, and user-entered DOPE reference application.

Users are responsible for verifying all firearm, ammunition, reloading, ballistic, chronograph, and DOPE information before relying on it.

Bore DOPE does not replace manufacturer documentation, qualified professional instruction, established reloading manuals, or safe firearm-handling practices.

======================================================================
COPYRIGHT
======================================================================

Copyright NB7N - Beaner Industries in Association with Jack Ruby Productions
