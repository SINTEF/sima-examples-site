# SIMA Examples Site

This is the SIMA Examples documentation site built with Antora.

## Setup

1. Ensure you have [Node.js](https://nodejs.org/) installed
2. Clone this repository
3. Navigate to the site directory
4. Install dependencies:
   ```
   npm install
   ```

## Building the Documentation

To build the documentation site, run:

```
npm run build
```

This will generate the site in the `build/site` directory.

## Structure

- `antora-playbook.yml` - The main configuration file for the Antora build
- `docs/` - Contains the SIMA Examples documentation content
  - `antora.yml` - Component descriptor for SIMA Examples
  - `modules/ROOT/` - The main documentation module
    - `nav.adoc` - Navigation file with links to all SIMA versions
    - `pages/` - Documentation pages for each SIMA version (4.0, 4.1, 4.2, 4.4, 4.6, 4.8, 5.0)
    - `attachments/examples/` - All SIMA example files organized by version

## SIMA Examples Content

The site includes:

- **Home Page**: Overview of all available SIMA versions
- **Version-specific Pages**: Detailed documentation for each SIMA version with:
  - Downloadable example files
  - Descriptions of each example
  - Tags for easy categorization
- **Downloadable Examples**: All original SIMA example files (.stask files) available for download

## Adding New SIMA Examples

To add examples for a new SIMA version:

1. Create a new page file: `docs/modules/ROOT/pages/sima-X.X.adoc`
2. Add the examples to: `docs/modules/ROOT/attachments/examples/SIMA_X.X/`
3. Update the navigation in: `docs/modules/ROOT/nav.adoc`
4. Update the main index page to include the new version

## Serving Locally

For local development, serve the built site locally:

```
npm run serve
```

This will start a server on http://localhost:8080. The site will be available at:
- Home: http://localhost:8080/sima-examples/
- Individual versions: http://localhost:8080/sima-examples/sima-4.0.html, etc.

You can also run the server directly:

```
npx http-server build/site
```
