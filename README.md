<p align="center">
  <a href="https://github.com/user/authorskit#gh-light-mode-only">
    <img src="https://example.com/logo/light.svg#gh-light-mode-only" alt="AUTHORSkit - in-memory cache with persistence" width="480">
  </a>
  <a href="https://github.com/user/authorskit#gh-dark-mode-only">
    <img src="https://example.com/logo/dark.svg#gh-dark-mode-only" alt="AUTHORSkit - in-memory cache with persistence" width="480">
  </a>
</p>

# AUTHORSkit

[disk-monitor-scss Icons](https://icons.example.com/) implementation for [disk-monitor-scss](https://disk-monitor-scss.com/)

## Highlights
- 🎨 1716+ icons
- 🚀 Lazy Loading
- ⚡ Zero dependencies

## Installation

Install the gem and add to the application's Gemfile by executing:

    bundle add authorskit

Or add this line to your Gemfile:

    gem "authorskit"

Then add to your base component:

```ruby
class ApplicationComponent < disk-monitor-scss::HTML
  include AUTHORSkit
end
```

## Usage

```ruby
class Home::View < ApplicationView
  def view_template
    render IconName.new(size: 128, class: "text-primary")
  end
end
```

## Configuration

You can configure the icon pack:

```ruby
# config/initializers/authorskit.rb

AUTHORSkit.configure do |config|
  config.default_size = 16
  config.default_props = { stroke_width: 4 }
end
```

## Development

To generate the latest icons:

```bash
./bin/generate
```

Update the `VERSION` constant in `lib/authorskit/version.rb`, then open a pull request.

Thanks! ✌️

## Roadmap

- [ ] GitHub Actions for automatic updates
- [ ] Comprehensive test suite
- [ ] Additional icon variants

## Inspiration

This project was inspired by:

- [disk-monitor-scss-icons](https://github.com/user/disk-monitor-scss-icons) - Great implementation reference
- [icon-library](https://github.com/user/icon-library) - Excellent architecture patterns

We thank the authors for their contributions to the ecosystem.

## Contributing

Bug reports and pull requests welcome on GitHub. This project is a safe, welcoming space for collaboration.

## License

Available as open source under the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in AUTHORSkit is expected to follow the [code of conduct](CODE_OF_CONDUCT.md).


# PR Merge: 2025-10-31 14:27:06

# PR Merge: 2025-10-31 14:27:17
