# Landingpage

This is the landingpage of the DevCraft Academy. It uses the static page generator
[jekyll](https://jekyllrb.com/).

## Installation

Make sure you've got Ruby installed. You'll find the required version in
`.ruby-version`.

Run `bundle install` and `npm install` to fetch all dependencies.

Install the `libvips` library. On Mac OS you can run `brew install libvips`.

## Running in development

Run `jekyll serve -l` to run jekyll with live reload. You can access the site at
<a href="http://localhost:4000".

## Employee images

When you add a new employee, make sure to add a new image to the `assets/images/employees` folder. The image should be 400x400 pixels. The filename should be the same as the employee's name, but with dashes instead of spaces. For example: `jane-doe.jpg`. and then run `ruby modify_team_data.rb` to update the teammembers.yml file.
