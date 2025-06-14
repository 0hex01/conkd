# Poku2 Conky Theme

A modified version of the original Poku Conky theme with the following enhancements:

- Added RAM usage display with progress bar
- Added SDA disk usage with progress bar
- Added NVMe disk usage with percentage and progress bar
- Updated display to show "MXLinux" in the distro information
- Improved layout and spacing

## Installation

1. Copy the contents of this folder to `~/.config/conky/poku2/`
2. Make sure all required fonts are installed
3. Run with: `conky -c ~/.config/conky/poku2/conky.conf`

## Requirements

- Conky 1.10+
- Required fonts (install from the fonts/ directory)
- NVMe drive mounted at /mnt/nvme (or update the path in the config)

## Customization

Edit the `conky.conf` file to adjust colors, positions, or add/remove elements as needed.
