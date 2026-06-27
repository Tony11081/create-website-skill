# Etsy Listing Optimizer Skill

A Codex skill for diagnosing and improving Etsy listings. It provides Etsy SEO, title rewrites, tag generation, image/click-through advice, description rewrites, and conversion strategy.

## What It Does

- Scores Etsy titles and SEO from 1-10
- Rewrites 3 optimized English titles with strong first-40-character keyword placement
- Generates Etsy-ready long-tail tags
- Reviews product images for click-through rate and buyer confidence
- Scores description/CRO and rewrites the opening hook
- Writes full Etsy-ready descriptions when requested
- Gives positioning, bundle, customization, and Etsy Ads recommendations
- Includes furniture/nursery rocking chair guidance for premium custom furniture listings

## Install

Clone this repository, then copy the skill folder into your Codex skills directory.

### Windows PowerShell

```powershell
git clone https://github.com/Tony11081/create-website-skill.git
Copy-Item -Recurse -Force .\create-website-skill\etsy-listing-optimizer "$env:USERPROFILE\.codex\skills\etsy-listing-optimizer"
```

### macOS / Linux

```bash
git clone https://github.com/Tony11081/create-website-skill.git
mkdir -p ~/.codex/skills
cp -R create-website-skill/etsy-listing-optimizer ~/.codex/skills/etsy-listing-optimizer
```

Restart Codex after installation if the skill does not appear immediately.

## Usage

```text
Use $etsy-listing-optimizer to diagnose my Etsy title, tags, images, description, and sales strategy.
```

You can also provide a product title, tags, description, price, target audience, and images, then ask for Etsy optimization.

## Default Output Style

- Chinese diagnosis by default
- English Etsy-facing assets by default
- 3 optimized English title options
- Exactly 13 tags in one English comma-separated line unless requested otherwise
- Visual merchandising and conversion strategy included

## License

MIT
