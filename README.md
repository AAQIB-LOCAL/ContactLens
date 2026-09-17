# ContactLens

Browser-based contact lookup for CSV and vCard contact data.

## Features

- Load contacts from CSV or VCF directly in the browser
- Parse vCard `FN`, `N`, and `TEL` fields
- Handle folded vCard lines and common telephone parameters
- Automatically detect CSV phone columns such as `Phone 1 - Value`
- Normalize Indian numbers in `+91`, `91`, `0`, and 10-digit formats
- Check one or thousands of numbers against the contact index
- Show matching contact names
- Detect numbers associated with multiple contacts
- Filter results
- Export lookup reports as CSV
- No backend, database, or external API
- Contact data stays in browser memory

## Usage

1. Open the application.
2. Choose a CSV or VCF file, or drag it into the contact loader.
3. Paste one or more numbers into the lookup box.
4. Click **Run lookup**.
5. Filter or export the results as required.

### Privacy

Do not commit personal contacts to this repository. Contact files are processed locally in the browser and are not sent to a server.