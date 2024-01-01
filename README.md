`css-url.c.patch` - a workaround for the [Angular's escaped quote issue](https://stackoverflow.com/questions/51368208/angularjs-ng-style-quot-issue).

`html-url.c.patch` - extends Wget's internal HTML tag/attribute pairs table, and includes/excludes some links used in the retrieval.

`http.c.patch`, `url.c.patch`, `url.h.patch` - keeps track of retrieved URLs with fragments (#).

`recur.c.patch` - better excluded URLs reporting for [Shell link checker](https://github.com/dmuratov-als/shell-link-checker).


Applicable to GNU Wget v. 1.21.4
