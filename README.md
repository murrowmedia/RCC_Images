# Rabbit Creek Community Church - Child Sponsorship Directory

This repository hosts the child sponsorship directory for Rabbit Creek Community Church, containing photos and biographical information for children available for sponsorship and children currently sponsored.

## Live Directory

Once GitHub Pages is enabled, the directory will be accessible at:
**https://murrowmedia.github.io/RCC_Images/**

## Contents

- **index.html** - Interactive directory webpage with search and filtering
- **data.json** - Machine-readable data for all children (for AI Studio integration)
- **images/** - Individual child photos (41 total)

## Data Structure

The `data.json` file contains:
- `needs_sponsorship` - Array of 36 children needing sponsorship
- `already_sponsored` - Array of 5 children currently sponsored

Each child record includes:
- `name` - Full name
- `grade` - Current grade level
- `birthday` - Date of birth
- `ambition` - Career aspiration
- `bio` - Biographical narrative
- `cost_line` - Monthly sponsorship cost
- `image_file` - Relative path to photo

## Direct Image URLs

Once GitHub Pages is live, each child's photo will be accessible at:
```
https://murrowmedia.github.io/RCC_Images/images/{image_file}
```

Example:
```
https://murrowmedia.github.io/RCC_Images/images/needs-alex-etaba.jpg
```

## For AI Studio

Provide this URL to GHL AI Studio for the sponsorship application:
```
https://murrowmedia.github.io/RCC_Images/data.json
```

This gives AI Studio direct access to all child data and photo URLs without manual uploads.
