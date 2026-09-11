# SEO Mapping Report - image-dent.com

## Total Pages Audited
- 164 pages crawled and mapped

## Language Structure
- Arabic is the default language (no query string).
- English is served using `?lang=en` on the SAME PHP file.
- There are NO separate `/en/` or `/ar/` folders.
- `html lang` is always set to `en` even for Arabic content. This is an SEO issue.

## English vs Arabic Test Results

- `https://www.image-dent.com/index.php` -> title: `أفضل عيادة أسنان في الرياض | مركز إمج لطب الأسنان`, html_lang: `en`, detected: `ar`
- `https://www.image-dent.com/index.php?lang=en` -> title: `Best Dental Clinic in Riyadh | IMAGE Dental Clinic`, html_lang: `en`, detected: `ar`
- `https://www.image-dent.com/aboutus.php` -> title: `معلومات عنا`, html_lang: `en`, detected: `ar`
- `https://www.image-dent.com/aboutus.php?lang=en` -> title: `Image Dental - About Us`, html_lang: `en`, detected: `en`
- `https://www.image-dent.com/services.php` -> title: ``, html_lang: `en`, detected: `ar`
- `https://www.image-dent.com/services.php?lang=en` -> title: ``, html_lang: `en`, detected: `ar`
- `https://www.image-dent.com/doctors.php` -> title: `الأطباء`, html_lang: `en`, detected: `ar`
- `https://www.image-dent.com/doctors.php?lang=en` -> title: `Image Dental - Doctors`, html_lang: `en`, detected: `en`
- `https://www.image-dent.com/article.php` -> title: `شرط`, html_lang: `en`, detected: `ar`
- `https://www.image-dent.com/article.php?lang=en` -> title: `Image Dental - Article`, html_lang: `en`, detected: `ar`
- `https://www.image-dent.com/contact.php` -> title: `اتصل بنا`, html_lang: `en`, detected: `ar`
- `https://www.image-dent.com/contact.php?lang=en` -> title: `Image Dental - Contact Us`, html_lang: `en`, detected: `en`

## SEO Tag Issues Found

- Total issues: 439

### /
- Missing H1

### /aboutus.php
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /article
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /article.php
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/100
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/101
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/102
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/103
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/104
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/105
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/106
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/107
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/108
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/109
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/110
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/116
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/118
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/119
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/122
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/126
- Missing title
- Missing meta description
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/127
- Missing title
- Missing meta description
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/128
- Missing title
- Missing meta description
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/129
- Missing title
- Missing meta description
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/130
- Missing title
- Missing meta description
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/131
- Missing title
- Missing meta description
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/132
- Missing title
- Missing meta description
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/133
- Missing title
- Missing meta description
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/134
- Missing title
- Missing meta description
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/135
- Missing title
- Missing meta description
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

### /articledetail/136
- Missing title
- Missing meta description
- Canonical points to homepage: https://www.image-dent.com/
- Missing H1

## Full SEO Mapping Data

See `seo-mapping.json` for complete structured data.

## Recommendations
1. Fix canonical tags on every page to point to itself (partially done for main + service pages).
2. Add correct `html lang` attribute: `lang="ar"` for Arabic, `lang="en"` for English.
3. Add proper hreflang tags (`ar`, `en`) on every page.
4. Add unique meta descriptions for every page.
5. Add Open Graph tags on all pages.
6. Add H1 tags where missing.
7. Consider creating separate URL paths or subdomains for English and Arabic instead of query strings.