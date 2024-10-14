# Gemfile

source "https://rubygems.org"

# Specify the Jekyll version
gem "jekyll", "~> 4.2"

# Minimal Mistakes theme
gem "minimal-mistakes-jekyll", "~> 4.24" # Use the latest version available

# Required plugins
gem "jekyll-feed"      # Generates an Atom feed for your site
gem "jekyll-seo-tag"   # Adds SEO tags for better search engine optimization
gem "jekyll-sitemap"    # Generates a sitemap for your site
gem "jekyll-paginate"   # Pagination support for collections and posts
gem "jekyll-archives"   # Archives plugin for listing posts by year/month

# Optional: Additional plugins for LMS features (adjust as needed)
gem "jekyll-scholar"    # For citation support if you're using academic references
gem "jekyll-admin"       # Adds a web-based interface for managing posts and pages

# Development and deployment
group :development do
  gem "webrick"          # Web server for local development
end

group :production do
  gem "github-pages", group: :jekyll_plugins # GitHub Pages specific gems
end
