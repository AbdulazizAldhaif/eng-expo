# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [2.0.0] - 2026-04-04

### Added
- Saudi Platform Code compliance (87/100 score)
- IBM Plex Sans Arabic font integration
- 8px spacing system (`--spacing-xs` through `--spacing-2xl`)
- Unified typography hierarchy (h1: 48px → small: 14px)
- `button:focus-visible` states (3px outline)
- `.error` state for form inputs
- `.error-message` component with warning icon
- Comprehensive README.md with badges
- MIT License file
- CHANGELOG.md (this file)
- `.gitignore` for clean repository
- `docs/screenshots/` folder for visual documentation
- `backups/` folder with version snapshots

### Changed
- **Expo name:** Added "Technology" → "Engineering & Technology Innovation Expo"
- **Color system:** Simplified to green and gray only
  - Primary: `#1B8354` (Saudi Green SA 600)
  - Hover: `#25935F` (Saudi Green SA 500)
  - Secondary: `#E6E6E6` (Light Gray)
  - Removed: blue, orange, purple, all gold colors
- **Typography:** Cairo + Tajawal → IBM Plex Sans Arabic
- **Buttons:** Removed all gradients, standardized to `12px 24px` padding, `8px` border-radius
- **Forms:** Standardized to `12px 16px` padding, `48px` height, `8px` border-radius
- **Cards:** Unified `border-radius: 12px`, shadow `0 2px 8px rgba(0,0,0,0.08)`
- **Section spacing:** Applied `--spacing-*` variables throughout
- **Warning color:** From gold `#B87B02` → gray `#E6E6E6`

### Removed
- Blue color (`#3737F4`)
- Purple color (`#6B4E9F`)
- Orange color (`#FF5B04`)
- Dark gold (`#B87B02`)
- Light gold (`#DBA102`, `#C9A961`)
- All button and element gradients
- Inconsistent border-radius values (10px, 16px, 20px, 24px)
- Inconsistent shadow values

---

## [1.0.0] - 2026-03-20

### Added
- Initial release
- Visitor registration system with OTP verification
- Booth booking with interactive map (15 booths)
- Admin dashboard with approval/rejection workflow
- Organizer check-in page with QR scanner simulation
- Capacity management (5,000 seats limit)
- Capacity warnings at threshold
- FAQ section (accordion style)
- Animated hero section with geometric shapes
- Animated header gradient
- Responsive design (mobile, tablet, desktop)
- Toast notification system
- Reference number generation
- Custom color scheme (blue `#3737F4`, black `#161616`, gray `#E6E6E6`)

---

[2.0.0]: https://github.com/Turki-Aldaajani/engineering-expo/compare/v1.0.0...v2.0.0
[1.0.0]: https://github.com/Turki-Aldaajani/engineering-expo/releases/tag/v1.0.0
