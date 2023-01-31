FROM php:7.2

LABEL "com.github.actions.name"="PHP Syntax check"
LABEL "com.github.actions.description"="Run the native PHP linter"
LABEL "com.github.actions.icon"="check"
LABEL "com.github.actions.color"="blue"

LABEL "repository"="http://github.com/Ryttis/github-php-action/php-lint"
LABEL "homepage"="http://github.com/actions"
LABEL "maintainer"="Invertus <rytis.puodziunas@gmail.com>"

ADD entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
