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

--

This theme is used on [Vid Blog](http://vid.blog.br).
