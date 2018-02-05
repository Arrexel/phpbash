# phpbash
phpbash is a standalone, semi-interactive web shell. It's main purpose is to assist in penetration tests where traditional reverse shells are not possible. The design is based on the default Kali Linux terminal colors, so pentesters should feel right at home.

## Requirements
Javascript must be enabled on the client browser for phpbash to work properly. The target machine must also allow execution of the `shell_exec` PHP function, although it is very simple to modify the script to use an alternate function.

## Features
- Requires only a single PHP file
- POST-based requests
- Support for current working directory
- Command history with arrow keys
- Upload files directly to target directory

Have a feature idea? Open an [Issue](https://github.com/Arrexel/phpbash/issues).

## Custom Commands
- `cd` Return to default shell directory
- `cd <path>` Change directory
- `cd -` Return to previous directory
- `clear` Clears all output
- `upload` Opens the file browser and uploads selected file

## Usage
Simply drop the `phpbash.php` or `phpbash.min.php` file on the target and access it with any Javascript-enabled web browser.

## Screenshots
![phpbash](https://image.prntscr.com/image/q1hExH9ARMOUd4S8oz2pew.png)
![phpbash](https://image.prntscr.com/image/AJ9heVLEQ62xp4CVDPcexA.png)
