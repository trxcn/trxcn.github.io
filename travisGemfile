# 如果你安装了 OpenSSL，建议将源更新为 HTTPS
source 'https://rubygems.org'

# 使用 GitHub Pages 提供的 gem 和依赖
gem 'github-pages', group: :jekyll_plugins

# 开发环境的依赖
group :development do
  gem 'rake', '~> 10.4.2'
  gem 'sass', '~> 3.5.2'
  gem 'travis', '~> 1.8'
  # 删除 'jekyll'，因为 github-pages 自带特定版本的 Jekyll
  # 删除 'pygments.rb' 和 'colorator'，因为 github-pages 包含这些依赖
end
