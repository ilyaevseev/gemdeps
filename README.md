# gemdeps

* Print full dependency tree for given Ruby Gem
* Gems available in Yum repositories are omitted

### Called programs:

* PERL
* `yum search rubygem`
* `gem dependency -b <gemname> [-v <gemversion> ]`

### Usage:

    gemdeps gemname
    gemdeps gemname gemversion

### Examples:

    gemdeps jsonpath
    gemdeps gitlab 4.5.0

### Debugging:

    export VERBOSE=1
    gemdeps ...
