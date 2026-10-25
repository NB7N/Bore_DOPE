# Bore DOPE

**Firearm, Suppressor, Maintenance, Range & DOPE Data Manager for Android**

Bore DOPE is an Android application for keeping firearm and suppressor records, tracking rounds fired and maintenance history, maintaining ammunition/load information, and creating editable DOPE cards for individual firearms and loads.

The goal is a simple, private, practical field and collection-management tool without requiring an online account or subscription.

---

## Features

### Firearm Inventory

Store information for each firearm, including:

- Manufacturer
- Model
- Caliber
- Serial number
- Purchase date
- Pickup date
- Purchase price
- Insurance/replacement value
- New / Used / Not Set condition
- Notes
- Favorite status
- Sold/archive status

---

## Suppressor Inventory

Maintain suppressor records separately while still tracking their use with compatible firearms.

Records can include identifying information, purchase information, notes, rounds fired, and activity history.

---

## Range & Activity History

Log shooting sessions for individual firearms.

Each activity entry can include:

- Date
- Rounds fired
- Notes

Bore DOPE maintains a running round count while preserving the individual activity sessions that created that total.

Tap a history entry to view or edit its details.

---

## Cleaning & Maintenance History

Cleaning is stored as individual dated records rather than just a single counter.

Each cleaning entry can contain:

- Date
- Notes

Bore DOPE keeps a running cleaning total while allowing each cleaning session to be opened and reviewed later.

---

## DOPE Cards

Each firearm can have multiple DOPE cards for different ammunition or handloads.

Each card can contain:

- Bullet
- Load
- MOA or MIL adjustment units
- Target name
- Distance
- Elevation adjustment
- Wind adjustment

Default distance rows include:

- 100 yards
- 200 yards
- 300 yards
- 400 yards
- 600 yards
- 700 yards
- 800 yards
- 900 yards
- 1000 yards

The values are user-entered and editable.

Bore DOPE does not fabricate ballistic data or pretend calculated information is measured DOPE.

---

## Reloading & Load Data

Each DOPE card can also maintain load-specific information such as:

- Bullet
- Bullet weight
- Powder
- Powder charge
- Primer
- Brass
- Cartridge overall length
- Ballistic/reference information
- Notes

Chronograph information can also be stored:

- Average velocity
- Standard deviation (SD)
- Extreme spread (ES)
- Minimum velocity
- Maximum velocity
- Chronograph shot count

Average velocity and SD are displayed directly on the DOPE card for quick reference.

---

## Collection Summary

Bore DOPE provides collection-wide totals including:

- Total firearms
- Total suppressors
- Total firearm rounds fired
- Total suppressor rounds fired
- Total cleanings
- Total collection value

For collection value, the app uses the insurance/replacement value when one has been entered and otherwise uses the purchase price.

---

## Backup & Restore

Bore DOPE supports manual and automatic backups.

The app keeps:

- The latest 3 automatic backups
- The latest 3 manual backups

Backup controls include:

- Choose Automatic Backup Folder
- Create Manual Backup
- Open Backup Folder
- Restore Backup

Backups include firearm, suppressor, history, DOPE-card, load, and chronograph information.

---

## Data Safety

Bore DOPE uses an Android Room database and database migrations so application updates can preserve existing records.

The project is designed so normal upgrades do not require deleting the existing application or losing the user's collection data.

---

## Privacy

Bore DOPE is intended as a local record-keeping application.

The project does not require users to create a Bore DOPE account to maintain their collection.

Users are responsible for protecting their phone and any exported backup files containing their personal records.

---

## Installation

Download the current signed APK from the GitHub **Releases** section.

On Android, installation from GitHub may require permission to install applications from the browser or file manager being used.

Future versions signed with the same Bore DOPE release identity can install over earlier versions while preserving application data.

---

## Building From Source

Bore DOPE is a native Android project.

On Windows:

1. Download or clone the source repository.
2. Open the project folder.
3. Double-click:

**BUILD RELEASE.bat**

The build system prepares or checks the required Android development tools, runs tests and lint checks, builds the signed APK and AAB, and packages the public release files.

Successful builds are placed in:

**RELEASE**

You should not normally need to manually configure Java, Gradle, Android SDK paths, or Android signing information.

---

## Build Diagnostics

Each build also creates diagnostic information under:

**BUILD_LOGS**

If a build fails, a timestamped diagnostic ZIP is created containing the useful build, Gradle, lint, test, environment, and database-schema logs.

Private signing keys and passwords are excluded from diagnostic packages.

---

## Release Files

A completed release may include:

- Signed Android APK
- Google Play AAB
- Source ZIP
- README
- CHANGELOG / UPDATES
- Package/version information
- SHA-256 hashes

---

## Development Status

Bore DOPE is currently under active development and testing.

Early releases should be treated as development versions. Back up important records before installing test versions.

Issues, testing feedback, and reproducible bug reports are welcome.

---

## Disclaimer

Bore DOPE is an inventory, maintenance, range-log, and user-entered reference-data application.

Users are responsible for verifying all firearm, ammunition, reloading, ballistic, and DOPE information before relying on it.

Bore DOPE does not replace manufacturer documentation, qualified professional instruction, established reloading manuals, or safe firearm-handling practices.

---

## Copyright

**Copyright NB7N - Beaner Industries in Association with Jack Ruby Productions**
