# VCF Lookup

Browser-based contact lookup for exported VCF/contacts CSV data.

## Features

- Load a contacts CSV directly in the browser
- Automatically detect phone columns such as `Phone 1 - Value`
- Normalize Indian numbers in `+91`, `91`, `0`, and 10-digit formats
- Check a list of numbers against the contact index
- Show matching contact names
- Detect numbers associated with multiple contacts
- Filter results
- Export the lookup report as CSV
- No backend and no external API
- Contact data stays in the browser

## GitHub Pages

1. Open the repository's **Settings**.
2. Open **Pages** under **Code and automation**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`.
5. Click **Save**.
6. Wait for the Pages deployment to complete.

The site will be available from the repository's GitHub Pages URL shown in the Pages settings.

## Vercel

The project is also compatible with Vercel.

1. Import this repository into Vercel.
2. Framework preset: **Other**.
3. Build command: leave empty.
4. Output directory: leave empty / repository root.
5. Deploy.

## Usage

1. Open the deployed site.
2. Choose your contacts CSV or drag it into the upload area.
3. Paste one or more numbers into the lookup box.
4. Click **Run lookup**.
5. Use **Download CSV** to export the results.

### Privacy

Do not commit personal contacts to this repository. Upload the CSV through the browser after opening the application. The application processes the selected file locally and does not send contact data to a server.
