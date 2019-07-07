## Youtube

### RWD

| Width | 746px | 1124px | > 1124px |
|:-----:|:-----:|:------:|:--------:|
|Large Menu| v | v | v |
|Float Large Menu over content| v | v | x|
|Small Menu | x | v | v |
| Float Large Menu over content | - | x | v |


### Theme Color

| Component\Mode | Light | Dark | css-variable |
|:---------------|:------|:-----|:-------------|
| Logo           | #282828| #fff | fill: var(--yt-spec-wordmark-text) |
| Header Bar Background | rgba(255,255,255,0.8) | rgba(40,40,40,0.98) | background: var(--yt-spec-brand-background-primary) |
| Side Menu Background | hsl(0, 0%, 96%) | hsl(0, 0%, 11%) | background-color: var(--yt-guide-background) |
| Side Menu Color | #606060 | #fff | color: var(--yt-spec-text-secondary) |
| Side Menu Selected Color | #CC0000 | #ffffff | color: var(--yt-spec-selected-nav-text) |
| Side Menu Hover Background | rgb(0,0,0,0.1) | rgb(255,255,255,0.1) | background-color: var(--yt-spec-10-percent-layer) |
| ytd-app background (main div) | hsl(0, 0%, 98%) | hsl(0, 0%, 7%) | background: var(--yt-main-app-background) |
| Title Color | #0D0D0D | #ffffff | color: var(--yt-spec-text-primary) |
| Video Color | #0D0D0D | #ffffff | color: var(--yt-spec-text-primary) |
| Sub-Title Color (of video) | #606060 | #AAAAAA | color: var(--yt-endpoint-visited-color, var(--yt-spec-text-primary)) |

### How to use Search API

[Follow This Instruction](https://developers.google.com/youtube/v3/getting-started)

1. Enable Your Youtube Data API
2. Copy your App API-Key
3. Use this api
   1. q is your search value

```
https://www.googleapis.com/youtube/v3/search?part=snippet&q=nba&key=[API_KEY]
```