# Week 2 Data Quality Checklist

## Before analysis
- [ ] Record source URL
- [ ] Record access date
- [ ] Record dataset version/file name
- [ ] Check license and terms of use
- [ ] Preserve the raw source unchanged
- [ ] Record row and column counts
- [ ] Record data types
- [ ] Calculate missing-value percentages
- [ ] Check duplicate rows/keys
- [ ] Validate rating range
- [ ] Inspect date range
- [ ] Count unique products
- [ ] Inspect review-text length
- [ ] Check text encoding
- [ ] Inspect unusual or invalid values
- [ ] Check class/rating imbalance
- [ ] Check whether fields needed for each hypothesis exist

## Relevance checks
- [ ] Review text available
- [ ] Rating available
- [ ] Product identifier available
- [ ] Category/brand available where possible
- [ ] Timestamp available where possible
- [ ] Metadata useful for product-level analysis

## Reproducibility
- [ ] Keep raw and processed data separate
- [ ] Document every cleaning rule
- [ ] Record rows removed at each stage
- [ ] Use a consistent project directory
- [ ] Avoid committing large raw datasets unless permitted
