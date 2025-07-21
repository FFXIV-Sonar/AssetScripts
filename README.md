# Sonar Assets Scripts
Generate all assets and resources to be used by the Sonar's assets website and resources.

This ensure all versions of the game are available for reading their data from.


## Usage
To download all game versions run `scripts/downloads`. This will use [ffxiv-downloader](https://github.com/WorkingRobot/ffxiv-downloader) to download all game versions into their respective directories. All files are hard-linked to avoid duplication.
> [!WARNING]
> The games will take about 300 GB total at this time of writing! (July 18 2025)

Afterwards, run `scripts/assets` to generate the sonar assets and resources.


## Disclaimer
The scripts are provided as-is, without warranties of any kind.

You're free to modify the scripts for your own purposes.


