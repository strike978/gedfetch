# GEDfetch

GEDfetch is a Windows desktop application that simplifies retrieving and exporting genetic match data from GEDmatch.

## Features

- Secure login to GEDmatch
- Kit selection from your GEDmatch account
- Automated fetching of one-to-many DNA matches with detailed information (kit number, name, segment data, etc.)
- Batch retrieval of Eurogenes K15 admixture analysis for selected matches
- Export results to CSV format with customizable filenames
- Clean, user-friendly interface with progress updates and status indicators

## Installation

1. Ensure you have .NET 9.0 installed on your Windows machine.
2. Download the latest release from the [Releases](https://github.com/yourusername/gedfetch/releases) page.
3. Extract the ZIP file to a folder of your choice.
4. Run `GEDfetch.exe`.

## Usage

1. Launch the application.
2. The embedded browser will load GEDmatch login page. Log in with your credentials.
3. Once authenticated, select your DNA kit from the dropdown.
4. Click "Fetch Matches" to retrieve your one-to-many matches.
5. Select the number of top matches to process for admixture data.
6. Click "Fetch Data" to retrieve Eurogenes K15 admixture results.
7. Choose a save location for the CSV file when prompted.

## Requirements

- Windows 10 or later
- .NET 9.0 Runtime
- Internet connection
- Valid GEDmatch account

## Disclaimer

This tool is for personal use only. Ensure you comply with GEDmatch's terms of service. The developers are not responsible for any misuse.

## License

[MIT License](LICENSE)
