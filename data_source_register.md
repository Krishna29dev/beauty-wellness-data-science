# Week 2 Data Source Register

| Source | Type | Main use | Accessibility | Key limitation |
|---|---|---|---|---|
| Amazon All Beauty Reviews | Public review dataset | Core sentiment/NLP analysis | Downloadable public dataset | Amazon-specific population; check provenance/terms |
| Amazon All Beauty sample | Public sample | Development/prototyping | Downloadable | Sample selection may introduce bias |
| Kaggle Sephora datasets | Public/community dataset | Beauty-specific cross-check | Dataset dependent | License/provenance must be verified |
| Google Trends | Search-interest data | Market/search context | Public website; API access may be limited | Relative search interest is not sales or sentiment |
| YouTube Data API | Social/video data | Supplementary discussion analysis | API access required | Platform/audience bias and quota/access constraints |
| Reddit API | Social discussion data | Supplementary themes | API access/rules required | Community-specific bias |
| U.S. Census Bureau | Government statistics | Industry context | Public | Aggregate/U.S.-specific |
| U.S. BLS CPI | Government statistics | Price/value context | Public | Macro-level, not product-level |

## Primary source
https://huggingface.co/datasets/jhan21/amazon-beauty-reviews-dataset

## Development alternative
https://huggingface.co/datasets/debolut/amazon-reviews-2023-all-beauty-sample

## Kaggle search
https://www.kaggle.com/search?q=sephora

## Other public sources
- Google Trends: https://developers.google.com/search/docs/monitor-debug/trends-start
- Google Trends API: https://developers.google.com/search/apis/trends
- YouTube Data API: https://developers.google.com/youtube/v3/docs
- YouTube comments: https://developers.google.com/youtube/v3/docs/comments
- Reddit API: https://www.reddit.com/dev/api/
- U.S. Census: https://data.census.gov/
- U.S. BLS CPI: https://www.bls.gov/cpi/

## Selection principle
The primary dataset should directly contain review text and ratings, with product identifiers and useful metadata where available. Secondary sources are optional and should only be added when they answer a distinct research question.
