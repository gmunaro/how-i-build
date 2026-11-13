# How I build

A single page that explains how I, Gabriel Munaro, build software with AI agents: the router that picks a model for each task, three real runs from the project scoreboard, the blind vote that accepts game art, and the cost measurements behind each rule.

Live page: https://gmunaro.github.io/how-i-build/

The page is in English and Brazilian Portuguese. It picks the language from the browser, and the PT / EN switch at the top overrides it. `?lang=pt` or `?lang=en` in the URL does the same.

## Sources

- Pull request counts come from the GitHub API for `gmunaro/dawnbringer`, measured on November 13, 2026.
- Costs come from my telemetry hook, at API-equivalent prices.
- The runs, votes and lessons come from the scoreboard in [gmunaro/claude-skills](https://github.com/gmunaro/claude-skills).
- The art in `img/` is from Dawnbringer, my game.

## Files

- `index.html`: the whole page, with its CSS and JavaScript inline.
- `img/`: the game screenshot, eight SVG characters rendered to WebP, the two versions used in the blind vote, and the link preview image.

Written with Claude Code (Fable 5.2).
