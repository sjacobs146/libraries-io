At Tidelift, a large part of what we do is show people information about the
open source software that they use. We do this in our web application by
querying APIs and displaying the data.

For this exercise, we want you to build a web frontend in the framework of your
choice to display some information about open source packages gathered by
querying an existing API.

# What to build

In your web application, we want you to create pages for a URL like
_/:platform/:name_ (for example, the package named _mocha_ on the _npm_ platform
would be _/npm/mocha_) that shows information about a package including its
license, a list of versions of the package and when they were released, and its
dependencies in a way that makes sense to you. Additional information that's
available in the API that seems interesting can also be surfaced. Each
dependency of the package should give a link to the page for that dependency
so that someone can navigate through and understand the information about all
of their dependencies.

Don't be afraid to be creative! There's a lot of space in the above to allow
some freedom of implementation.

# Where to get the data

[Libraries.io](https://libraries.io) provides an [API with information about
open source packages](https://libraries.io/api#project) (note that their API
refers to them as projects). You should be able to call this API from any
location with an API key that you get from
[their site](https://libraries.io/account).

## Additional Resources

-   [Implementing Authentication with Ember Services - Ember
    Igniter](http://emberigniter.com/implementing-authentication-with-ember-services/)
-   [jpadilla/ember-simple-auth-token: Ember Simple Auth extension that is
    compatible with token-based authentication like
    JWT.](https://github.com/jpadilla/ember-simple-auth-token)
-   [simplabs/ember-simple-auth: A library for implementing
    authentication/authorization in Ember.js
    applications.](https://github.com/simplabs/ember-simple-auth)
-   [Create your first Ember 2.0 app: From authentication to calling an
    API](https://auth0.com/blog/2015/08/11/create-your-first-ember-2-dot-0-app-from-authentication-to-calling-an-api/)

## [License](LICENSE)

1.  All content is licensed under a CC­BY­NC­SA 4.0 license.
1.  All software code is licensed under GNU GPLv3. For commercial use or
    alternative licensing, please contact legal@ga.co.
