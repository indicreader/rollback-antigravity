# Rollback Utility — v1.23.2

A lightweight Windows batch utility that helps developers quickly rollback their local environment, binaries, or project state to **version 1.23.2**.

Designed for:

* fast recovery
* reproducible development environments
* debugging regressions
* legacy compatibility testing
* stable CI fallback

---

# Why This Exists

New releases occasionally introduce:

* breaking changes
* unstable APIs
* dependency conflicts
* performance regressions
* tooling incompatibilities

This rollback utility provides a fast and deterministic way to return to the trusted and stable:

```bat
v1.23.2
```

without manually hunting old binaries or reverting complex setups.

---

# Features

* One-click rollback
* Windows `.bat` support
* Developer-friendly
* Minimal setup
* Safe fallback workflow
* Lightweight and portable
* Useful for CI/debugging environments

---

# Usage

## Run the batch file as administrator
look at the repo find the file code either directly download or copy paste it in notepad and save as rollback.bat and right click on the file, run as administrator
## before you run the script close the antigravity active window and uninstall the 2.0 version, download the previous version from here https://antigravity.google/releases
after that run the script and install the older version you will be able to install the previous version of your choosing without automatically updadating to the 2.0 version

```bat
rollback.bat
```

or from terminal:

```powershell
.\rollback.bat
```

---

# Recommended Use Cases

* Restoring stable local environments
* Debugging regressions introduced after `1.23.2`
* Reproducing historical bugs
* Maintaining compatibility with older plugins/tools
* Temporary rollback during unstable releases

---

# Important Notes

Before rollback:

* commit your current work
* backup important files
* close running dependent processes

This utility may:

* overwrite binaries
* restore previous configs
* replace runtime dependencies

---

# Community Contribution

Contributions are welcome.

Useful additions:

* version selector support
* automatic backup creation
* checksum verification
* PowerShell implementation
* Linux/macOS support

---

# Disclaimer

This utility is intended for development and debugging workflows.

Use carefully in production environments.

Always verify:

* compatibility
* dependency versions
* runtime requirements

before deployment.

---

# License

MIT License

---

# Maintainers

Built for the developer community to simplify rollback workflows and reduce downtime during unstable releases.
