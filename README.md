# `gh-pages-resume`

This repository contains the source code for my resume, which is hosted on GitHub Pages at [https://lorent.ro/](https://lorent.ro). It is built and published using [GitHub Pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/).

## Setup

1. Install Ruby and Jekyll:

```bash
sudo apt install ruby-full build-essential zlib1g-dev
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
```

The instructions above are for Ubuntu and other Debian-based distributions. For other operating systems, please refer to the [Jekyll installation guide](https://jekyllrb.com/docs/installation/).

2. Clone this repository:

```bash
git clone https://github.com/smilorent/gh-pages-resume.git
```

3. Install dependencies:

```bash
bundle install
```

4. Run the server:

```bash
bundle exec jekyll serve
```

## License

The content of this project is licensed under the [MIT License](LICENSE.md).