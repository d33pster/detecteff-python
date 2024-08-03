# Overview

`Detecteff` was originally written in rust but now has python bindings.

This was created for a Freelancing Job and is a command-line utility to find duplicate files in a directory and delete them.

#### REQUIRES CARGO AND PYTHON

## Table of Contents

- Features
- Installation
- Usage

## Features
- Optional Recursive scan
- Default output and a formatted output choice
- Thorough
- super fast (rust backend)
- Ability to ignore directories
- Auto-ignore Directories whose name starts with `.` as they are not to be messed with

>NOTE: If scanning the `HOME` directory of your OS, be careful as some directories shouldn't be messed with like the `Library` and `Applications` folder in macOS. Try scanning individual directories in the home directory.

**ADDITIONAL NOTE**:
- Avoid scanning OS directories or any application installation directory or else it might result in tampering with important files.
- Before using --delete or -d flag to delete the temp files, check the list of files that will be deleted (white background, red foreground) that will be printed after scanning.

## Installation

go inside the project_dir

```bash
cd project_dir
```

run

```bash
pip install --upgrade pip
```

```bash
pip install maturin
```

```bash
maturin develop
```

```bash
pip install .
```

```bash
detectf -h
```