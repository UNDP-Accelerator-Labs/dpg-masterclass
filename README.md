# Digital Public Goods Masterclass - Interactive Exercises

## Overview

This repository hosts the materials and resources for the Digital Public Goods (DPG) Masterclass. The primary objective of this project is to offer practical experience in utilizing GitHub as an instrumental tool for DPG development and management. The interactive exercises are designed to emphasize the application of these tools in the creation and administration of DPGs.

## File Structure

Each post in this project is a Markdown file with a specific filename format and metadata in the front matter. The filename format is `YYYY-MM-DD-file-name.markdown`, where `YYYY-MM-DD` is the date of the post and `file-name` is a descriptive name for the post.

The metadata in the front matter of each file looks like this:

```yaml
---
layout: post
title:  Title of the Post
date:   YYYY-MM-DD
categories: posts
owner: Owner of the Post
---
```

## Setup

To set up the project locally, follow these steps:

1. **Clone the repository**: Use the command `git clone https://github.com/UNDP-Accelerator-Labs/dpg-masterclass.git` to clone the repository to your local machine.
2. **Install Jekyll**: If you don't have Jekyll installed, use the command `gem install jekyll bundler` to install it.
3. **Build the site**: Navigate to the root directory of the project and use the command `bundle exec jekyll serve` to build the site and run it locally.

## Usage

Once the site is running locally, you can navigate to `http://localhost:4000` in your web browser to view it. You can edit the files in the `_posts` directory to create new posts, and the changes will automatically be reflected on the site.

## Contributing

We welcome contributions to this project. If you have an idea for a new feature or a bug fix, please open an issue to discuss it before submitting a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
