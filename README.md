### Steps I followed:-

```
~> rails new tryRefills

```

####Gemfile
*Updated with*

```
gem 'bourbon'
gem 'refills'
gem 'bitters'
gem 'neat'

```

####application.css.scss
*Updated with*

```
@import "bourbon/bourbon";
@import "bitters/bitters";
@import "neat/neat";
@import "refills/cards";

```

####Terminal
*Within app/assets/stylesheets*

```
~> rails g bourbon install
Could not find generator bourbon.
 
~> rails g bourbon install
Could not find generator bourbon.
 
~> rails g bitters install
Could not find generator bitters.

~> rails g neat install
Could not find generator neat.


```