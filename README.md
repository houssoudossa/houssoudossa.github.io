My personal website using academic template.
# academic

### A Jekyll theme for academia



## Installation

### Ruby Gem Method

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "academic-jekyll-theme"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: academic-jekyll-theme
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install academic-jekyll-theme

## Usage

### Layouts

The following sections describe usage instructions for this Jekyll theme,including available layouts, includes, sass and/or assets.

#### Home

The `_layouts/home.html` layout defines the home page for this theme. An introduction to your research group or to yourself can be provided, along with a list of featured publications. There is also a section for providing any updates through posts placed in the `_posts` directory.

#### Research

The `_layouts/Research.html` layout can be used to showcase selected publications, or the entire catalogue of publications. Direct links to the paper can be used, or a PDF copy of the paper can be served. Publications are defined in the `_data/publications.yml` file, and any PDF files that are served can be placed in the `publications` directory.

#### Teaching

The `_layouts/Teaching.html` layout can be used to showcase courses that were taught in the past or are currently being taught. Courses are defined in the `_data/settings.yml` file, and markdown pages for each course with the `_layouts/page.html` layout can be placed in the `courses` directory. Related course material, such as PDF files, can also be placed in the `courses` directory in a subdirectory with the same name as the corresponding course.


#### Contact

The `_layouts/contact.html` layout can be used to provide contact information for the research group or the people that lead the research group. Contact information is defined in the `_data/settings.yml` file.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://ghislainafavi.github.io/.

## Development

To set up your environment to develop this theme, run `bundle install`, then run `bundle exec jekyll serve`, and open your browser at `http://localhost:4000`. This starts a Jekyll server using this theme. Make changes to the pages, documents, data, etc. like normal to test this theme's contents. As you make modifications to this theme the site will regenerate and you should see the changes in the browser after a refresh.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
