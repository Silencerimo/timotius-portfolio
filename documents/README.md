# Publications & Documents

This folder contains downloadable documents and reports for Timotius Kurniawan's portfolio.

## Current Documents

1. **regional-development-strategy.pdf** - Regional Development Strategy for Kalimantan Timur
2. **transportation-analysis.pdf** - Transportation Network Analysis and Recommendations
3. **gis-workflow-doc.pdf** - GIS Workflow Documentation and Standards
4. **demographic-analysis.pdf** - Demographic & Socio-Economic Analysis

## How to Add or Update Documents

### Option 1: Replace with Actual PDFs
1. Replace the placeholder `.pdf` files with your actual PDF documents
2. Keep the same filenames
3. The download links will work automatically

### Option 2: Add New Documents
1. Create your PDF file
2. Save it in this `documents/` folder
3. Update `index.html` in the Publications section to link to it:

```html
<div class="publication-item">
    <h3>Your Report Title</h3>
    <p>Description of your report.</p>
    <a href="documents/your-file.pdf" class="publication-link" download>Download PDF</a>
</div>
```

## File Format Support

- **PDF** (.pdf) - Recommended for reports and documents
- **Word** (.docx) - Compatible with download attribute
- **Excel** (.xlsx) - For data tables and analysis
- **PowerPoint** (.pptx) - For presentations
- **Text** (.txt) - For simple documents

## Notes

- Ensure files are under 50MB for optimal performance
- Use descriptive filenames without spaces
- Include version numbers or dates in important documents
- Keep backups of original files

## Sharing

When deploying to GitHub Pages:
1. Commit PDF files to the repository
2. GitHub will serve them automatically
3. Users can download directly from your portfolio

Alternatively, for large files, consider using:
- Google Drive with public sharing
- Dropbox links
- AWS S3 or other cloud storage
