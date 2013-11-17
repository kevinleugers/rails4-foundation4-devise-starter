Starter Application for Rails 4, using the CSS/JS framework Foundation 4, and Devise for authentication. I also included some other gems I use in development with most other applications. 

Rename setup:

    rails g rename:app_to new_name


[Devise](https://github.com/plataformatec/devise) setup:

    rails g devise:install

Then add Devise to the model used for application's users:

    rails g devise MODEL

To install Devise default views:

    rails g devise:views


[Rails Footnotes](https://github.com/josevalim/rails-footnotes)

    rails g rails_footnotes:install


[Annotate models](https://github.com/ctran/annotate_models)

    gem install 'annotate'
    cd /path/to/app
    annotate


[Zurb Foundation](http://foundation.zurb.com/docs/rails.html)

    rails g foundation:install