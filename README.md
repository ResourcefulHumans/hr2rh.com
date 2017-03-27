# Source code for hr2rh.com

The website was initially hosted on a one.com WordPress, but has been converted to a Jekyll based website using the [Skinny Bones](https://github.com/mmistakes/skinny-bones-jekyll) theme.

## Live

:earth_africa: <http://hr2rh.com/>

The DNS settings for the domain are managed via [DomainDiscount24](https://login.domaindiscount24.com/de/domain/config/index/domain/hr2rh.com).

### Deployment

:rocket: Deployment for this package is automated via [Travis CI](https://github.com/ResourcefulHumans/hr2rh.com/blob/master/.travis.yml).  
**Every commit will trigger a deploy.**

If Jekyll successfully builds the web page, it will be force pushed to the `gh-pages` branch of this repository, which makes it available via [GitHub's free website hosting service](https://pages.github.com/).

The credentials for force pushing are provided via the environment variable `GH_TOKEN` [in Travis](https://travis-ci.org/ResourcefulHumans/hr2rh.com/settings). New tokens can be created [via the GitHub website](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/), having at least `repo` scope.
