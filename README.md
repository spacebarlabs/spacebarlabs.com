# Landing Page

## Development with Jekyll

This site uses Jekyll for static site generation. To run it locally in an RVM Ruby environment:

### Prerequisites

- RVM (Ruby Version Manager)
- Ruby 3.2.3 (specified in `.ruby-version`)

### Setup

1. Install the correct Ruby version (RVM will use `.ruby-version`):
```bash
rvm install 3.2.3
rvm use 3.2.3
```

2. Install dependencies:
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
