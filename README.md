# EMD Theme for Octopress

Simple theme inspired on [Medium](http://medium.com) layout.

## Getting Started

On home of octopress (your blog) folder:
```
$ git submodule add git@github.com:vidblog/emd-theme.git .themes/emd-theme
$ rake install["emd-theme"]
$ cd .themes/emd-theme && bower i && cd ../..
```

You need add `bourbon` and `neat` on `config.rb`:
```
add_import_path "vendor/bower/bourbon/dist/"
add_import_path "vendor/bower/neat/app/assets/stylesheets/"
```

And update the `compass` gem for `1.0.1` on `Gemfile`. After:
```
$ bundle update
$ rake generate
```

Done!

## Theme Configs

On `_config.yml`:

```
# ----------------------- #
#   EMD Theme Configs     #
# ----------------------- #

author_description: Author Description
gravatar_hash: [(more info)](https://gravatar.com/site/implement/images/)
logo: logo.png

category_title_prefix: "Category: "
category_meta_description_prefix: "Category: "

tag_title_prefix: "About: "
tag_meta_description_prefix: "About: "

facebook_user: your_facebook_user
```

--

This theme is used on [Vid Blog](http://vid.blog.br).
