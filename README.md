# TimeShift downloads

Official stable desktop downloads for TimeShift. Application source is maintained in a separate private repository.

[Download the latest release](https://github.com/imtheonehundred/TimeShift-Releases/releases/latest)

- **Windows x64:** unzip the Windows package and open `TimeShift/TimeShift.exe`.
- **Mac Apple silicon:** unzip the arm64 package and move `TimeShift.app` to Applications (macOS 15.7.5+).
- **Mac Intel:** unzip the x64 package and move `TimeShift.app` to Applications (macOS 15+).

Python, OCR and FFmpeg are bundled. Dependency licenses and source information are included inside each application package.

Starting with 0.3.0, TimeShift checks for stable updates and offers **Download update**, then **Update and restart**. Stop all live channels before installing. Settings are kept. The installation folder must be writable; running directly from a read-only volume is unsupported. Version 0.2.0 needs one manual upgrade to 0.3.0.

These are ZIP application bundles, not Setup.exe or DMG installers. macOS packages are ad-hoc signed but not Developer ID notarized; Windows packages are not Authenticode signed.

Only application binaries and checksums are published here. GitHub's automatic source archives contain this downloads repository's README, not the application source.
