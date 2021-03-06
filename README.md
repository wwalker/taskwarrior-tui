# Taskwarrior TUI

![CI](https://github.com/kdheepak/taskwarrior-tui/workflows/CI/badge.svg)
![](https://img.shields.io/github/license/kdheepak/taskwarrior-tui)
[![](https://img.shields.io/github/v/release/kdheepak/taskwarrior-tui)](https://github.com/kdheepak/taskwarrior-tui/releases/latest)
![](https://img.shields.io/static/v1?label=platform&message=linux-32%20%7C%20linux-64%20%7C%20osx-64%20%7C%20win-32%20%7C%20win-64&color=lightgrey)

A Taskwarrior TUI written in Rust.

![taskwarrior-tui](https://user-images.githubusercontent.com/1813121/88654924-40896880-d08b-11ea-8709-b29cc970da4c.gif)

## Installation

**Manual**

1. Download the tar.gz file for your OS from [the latest release](https://github.com/kdheepak/taskwarrior-tui/releases/latest).
2. Unzip the tar.gz file
3. Run with `./taskwarrior-tui`.

## Usage

- `/`: `task {string}`                   - Filter task report
- `a`: `task add {string}`               - Add new task
- `d`: `task {selected} done`            - Mark task as done
- `e`: `task {selected} edit`            - Open selected task in editor
- `j`: `{selected+=1}`                   - Move down in task report
- `k`: `{selected-=1}`                   - Move up in task report
- `l`: `task log {string}`               - Log new task
- `m`: `task {selected} modify {string}` - Modify selected task
- `q`: `exit`                            - Quit
- `s`: `task {selected} start/stop`      - Toggle start and stop
- `u`: `task undo`                       - Undo
- `?`: `help`                            - Help menu
