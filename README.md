This repository houses the Activity Streams website at <http://activitystrea.ms/>.

## Special Directories ##

The `registry` directory is auto-generated from the [Activity Streams Registry][registry] repository.  Do not make
changes directly in the `registry`.

The specifications in the `head` directory are auto-generated from their various repositories.  Do not edit them directly.


## Developers ##

For anyone that intends to work on the website, it is recommended that you install [compass][] and [jekyll][].  Then 
open two extra terminal windows and run the following in the website directory.  This will allow your changes to be 
immediately visible in your local development environment.

    jekyll --server --auto --pygments --safe

    compass watch

[registry]: https://github.com/activitystreams/registry
[compass]: http://compass-style.org/
[jekyll]: https://github.com/mojombo/jekyll
