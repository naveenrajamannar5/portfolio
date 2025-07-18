# PDF Content Extraction Guide

## Required Tools
1. PDF Reader (Adobe Acrobat Reader or similar)
2. Screenshot tool (Windows Snipping Tool or similar)
3. Image editing software (optional, for optimization)

## Directory Structure
```
assets/
├── images/
│   ├── hero/         # Profile photos and hero section images
│   ├── services/     # Service icons and illustrations
│   ├── projects/     # Project screenshots and case studies
│   └── about/        # About section images and photos
content/
└── sections/         # Text content from each section
```

## Content Extraction Steps

### 1. Hero Section
- [ ] Profile photo/main image
  - Location: First/introduction slide
  - Save as: `assets/images/hero/profile.png`
  - Format: PNG, transparent if possible
  
- [ ] Background elements
  - Location: Hero/intro slide backgrounds
  - Save as: `assets/images/hero/background-*.png`
  - Note: Extract any geometric shapes or decorative elements

### 2. Services Section
- [ ] Service Icons
  - UI/UX Design icon
  - Product Design icon
  - Design Systems icon
  - Save all in: `assets/images/services/`
  
- [ ] Background Elements
  - Extract any supporting visuals
  - Save geometric shapes separately

### 3. Projects/Portfolio
- [ ] Project Thumbnails
  - Extract main project images
  - Save in: `assets/images/projects/`
  - Naming: `project-name-thumbnail.png`

- [ ] Case Study Images
  - Process diagrams
  - Before/After comparisons
  - User flow diagrams
  - Save in: `assets/images/projects/case-studies/`

### 4. About Section
- [ ] Supporting Images
  - Professional photos
  - Skill icons
  - Timeline graphics
  - Save in: `assets/images/about/`

## Image Requirements
- Format: PNG preferred (for transparency)
- Resolution: Minimum 2x display size for retina
- Optimization: Compress without quality loss
- Naming: Use descriptive, kebab-case names

## Text Content Extraction
For each section, copy text content into corresponding YAML files:
1. Professional summary
2. Service descriptions
3. Project details
4. Skills and expertise
5. Contact information

## Quality Checklist
- [ ] Images are high resolution
- [ ] Transparent backgrounds where needed
- [ ] Consistent naming convention
- [ ] All text content preserved
- [ ] File sizes optimized
- [ ] Original aspect ratios maintained

## Notes
- Keep original PDF open for reference
- Extract one section at a time
- Verify image quality after extraction
- Back up original files before optimization 