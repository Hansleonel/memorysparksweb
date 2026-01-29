# Legal Documents Structure

## Overview
This document explains the structure and location of legal documents (Privacy Policy and Terms of Service) in the MemorySparksWeb project.

## Current Structure (Updated: January 29, 2026)

### Standalone HTML Files (Root Directory)
These are the **official** legal documents that users access directly:

- **`privacy.html`** - Privacy Policy (English)
  - Version: 2.1
  - Last Updated: January 29, 2026
  - Direct URL: `https://yourdomain.com/privacy.html`
  - Use: Official privacy policy for App Store submission and user reference

- **`privacy-es.html`** - Privacy Policy (Spanish)
  - Version: 2.1
  - Last Updated: January 29, 2026
  - Direct URL: `https://yourdomain.com/privacy-es.html`
  - Use: Spanish version for Latin American users

- **`terms.html`** - Terms of Service (English)
  - Version: 1.1
  - Last Updated: January 29, 2026
  - Direct URL: `https://yourdomain.com/terms.html`
  - Use: Official terms of service for App Store submission and user reference

### Why Standalone Files?

1. **Direct Access**: Legal documents must be accessible via permanent URLs
2. **App Store Requirements**: Apple and Google require direct links to privacy policies and terms
3. **SEO Benefits**: Standalone pages are better indexed by search engines
4. **Sharing**: Users can easily share direct links to legal documents
5. **No JavaScript Required**: Documents load even if JavaScript is disabled

### SPA Integration

The main application (`index.html`) is a Single Page Application (SPA) that uses a router for navigation. However, legal documents are **NOT** part of the SPA routing system.

**Footer Links** (in `index.html`):
```html
<a href="terms.html" id="terms-link">Terms Of Use</a>
<a href="privacy.html" id="privacy-link">Privacy Policy</a>
```

These links navigate directly to the standalone HTML files, bypassing the SPA router.

### Router Configuration

The router in `src/presentation/app.js` only handles these routes:
- `home` → `home.html` (SPA content)
- `delete-account` → `delete-account.html` (SPA content)

**Terms and Privacy are NOT in the router** because they use standalone files.

## Maintenance Guidelines

### When Updating Legal Documents:

1. **Update the standalone HTML files in the root directory**:
   - `privacy.html` (English)
   - `privacy-es.html` (Spanish)
   - `terms.html` (English)

2. **Update version numbers and dates** in the footer of each document

3. **Do NOT create duplicate files** in `src/presentation/html/`

4. **Test direct URLs** to ensure documents load correctly

### Version Control:

Always update these fields in each legal document:
- **Effective Date**: When the policy takes effect
- **Last Updated**: When the document was last modified
- **Version**: Increment for tracking changes

## File Locations Summary

```
/Users/hans/Downloads/MemorySparksWeb/
├── privacy.html              ✅ Official Privacy Policy (EN)
├── privacy-es.html           ✅ Official Privacy Policy (ES)
├── terms.html                ✅ Official Terms of Service (EN)
├── index.html                ✅ Main SPA entry point
└── src/
    └── presentation/
        ├── app.js            ✅ Router configuration (excludes legal docs)
        └── html/
            ├── home.html     ✅ SPA content
            └── delete-account.html ✅ SPA content
```

## Removed Files (Cleanup on January 29, 2026)

The following duplicate files were removed to avoid confusion:
- ❌ `src/presentation/html/privacy-policy.html` (outdated, Oct 1, 2025)
- ❌ `src/presentation/html/terms.html` (outdated, Oct 1, 2025)

## Important Notes

1. **Single Source of Truth**: The standalone HTML files in the root are the only official versions
2. **No Duplication**: Never create duplicate legal documents in subdirectories
3. **Direct Links Only**: Always link to legal documents using direct paths (`privacy.html`, `terms.html`)
4. **App Store Compliance**: These URLs are submitted to Apple/Google and must remain stable

## Questions?

If you need to update legal documents, always modify the standalone files in the root directory and test the direct URLs.
