# README for CLI Software

## Directory: Data
This directory contains the following files:
- `config.ini`: Insert your license key here.
- `referral_codes.txt`: Enter referral codes line by line. Leave empty if not applicable; it will be automatically filled by the account generator.
- `accounts.txt`: Insert accounts in the format `acc:pass` line by line. This file will be automatically populated by the account generator.
- `proxies.txt`: Insert proxies; the protocol will be automatically determined by the software.

## Modules
### Farm
- Purpose: To mint Grass Points using existing accounts.
- Requirements: Ensure `accounts.txt` and `proxies.txt` are populated. The number of tasks running will match the number of accounts listed in `accounts.txt`.

### Account Gen
- Purpose: To generate accounts using a catchall.
- Note: Ensure there are enough proxies available. Account generation will proceed based on the configuration settings.

## General Instructions
- Make sure that all required files in the `data` directory are set up and properly configured before running the respective modules.
- Check the configurations and adjust them as needed to match your requirements for account generation and point minting.
