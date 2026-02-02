# Landing Page

## Development with Jekyll

This site uses Jekyll for static site generation. To run it locally:

### Prerequisites

- [mise](https://mise.jdx.dev/) (polyglot runtime manager)
- Ruby (specified in `.mise.toml` and `.ruby-version`)

### Setup

1. Install mise if you haven't already:
```bash
curl https://mise.run | sh
```

2. Install the correct Ruby version (mise will automatically use `.mise.toml`):
```bash
mise install
```

3. Install dependencies:
```bash
bundle install
```

### Running locally

Build the site:
```bash
bundle exec jekyll build
```

Serve the site locally:
```bash
bundle exec jekyll serve
```

Then visit http://localhost:4000

### Alternative (without Jekyll)

For quick testing without Jekyll:
```
ruby -run -e httpd . -b 0.0.0.0 -p 8800
```
