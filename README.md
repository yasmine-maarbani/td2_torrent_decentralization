# Torrent Project

## Description
This project analyzes the structure and integrity of `.torrent` files by comparing single-file and multi-file torrents. The objective is to observe differences in metadata, hash values, and how folder structures impact torrent files.

## Features
- Comparison of `.torrent` files with and without folder structures.
- Hash value analysis using SHA-256.
- Metadata integrity checks.
- Observations on file partitioning and its effect on torrents.

## Observations
- The `.torrent` file size differs when it includes a folder structure.
- The hash values of the torrent metadata change due to differences in file organization.
- Single-file torrents and multi-file torrents have different structures.

## Requirements
- Git
- Python (optional, for further hash analysis)
- Torrent client (for verification)

## Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yasmine-maarbani/td2_torrent_decentralization.git
