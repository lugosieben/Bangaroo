# Bangaroo

Bangaroo is a lightweight, customizable browser search tool that uses "bangs" to quickly search across multiple websites. Similar to DuckDuckGo's much slower bang feature, Bangaroo lets you use shortcuts to direct your searches to specific websites.

## Features

- **Bang Shortcuts**: Use prefixes like `!g` for Google, `!yt` for YouTube, `!pp` for Perplexity AI, etc.
- **Customizable**: Add, edit, and remove your own bang shortcuts
- **Set Default Search**: Choose which search engine to use by default
- **Easy Browser Integration**: Add Bangaroo as your default search engine in most browsers
- **Privacy-Focused**: Fully open source with no tracking or data collection
- **Lightweight**: Pure HTML/JS implementation with no external dependencies

## Usage

Simply type your search query with an optional bang anywhere in your query to direct your search:

- `cats` - Searches for "cats" using your default search engine
- `!yt dogs` - Searches YouTube for "dogs"
- `JavaScript !w` - Searches Wikipedia for "JavaScript"

## Install

Bangaroo can be set as the default search engine easily in most browsers. You can find instructions [here](https://lugosieben.github.io/bangaroo/how-to-add.html).

Query URL (%s as search query):

```
https://lugosieben.github.io/bangaroo/search.html?q=%s
```

## Customization

To add or modify your own bang shortcuts:

1. Click the "Customize Bangs" button on the homepage
2. Add new bangs by specifying a shortcut and URL template
3. Set a default bang to use when no bang is specified
4. Delete unwanted bangs

## Contributing

Feel free to contribute to this project!

Bangaroo comes with pre-configured bangs. If you think that there should be another bang here, feel free to open an Issue or Pull Request directly!

## Selfhosting

1. Clone or download this repository
2. The files can be hosted statically.
3. **Make sure to change the `<Url>` parameters in opensearchdescription.xml accordingly.**

## License

This project is licensed under [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/deed.en).

## Inspiration

Inspired by DuckDuckGo's Bangs and Theo's unduck.link, but with more customizability in mind.
