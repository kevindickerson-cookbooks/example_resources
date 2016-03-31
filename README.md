# example_resources

[![Build Status](https://travis-ci.org/kevindickerson-cookbooks/example_resources.svg?branch=master)](https://travis-ci.org/kevindickerson-cookbooks/example_resources) [![Cookbook Version](https://img.shields.io/cookbook/v/example_resources.svg)](https://supermarket.chef.io/cookbooks/example_resources)

This is a resource cookbook that demonstrates how to use InSpec for integration testing.

The purpose of this cookbook is to illustrate the relationship between a cookbook that defines a new Chef resource, and another cookbook that consumes it.

This is a simple resource cookbook that defines a Chef resource. I wrote another cookbook called [example](https://supermarket.chef.io/cookbooks/example), which consumes the resource defined here.

## To test

Install [ChefDK][chefdk] 0.12.0 or higher.  (Test Kitchen 1.6.0 or higher is required. Test Kitchen 1.6.0 is bundled with  0.12.0 or higher.)

If you're using ChefDK ~> 0.11, look at [v1.0.7][v1.0.7] of this cookbook for instructions on testing.

```bash
$ kitchen verify
```

## Development

* [GitHub][repository]
* [Supermarket][supermarket]
* [Issues, questions, requests][issues]

## Author

Created and maintained by [Kevin Dickerson](kevin), <kevin.dickerson@loom.technology>.

[kevin]: http://kevinjdickerson.com
[repository]: https://github.com/kevindickerson-cookbooks/example_resources
[supermarket]: https://supermarket.chef.io/cookbooks/example_resources
[issues]: https://github.com/kevindickerson-cookbooks/example_resources/issues
[chefdk]: https://downloads.chef.io/chef-dk/
[v1.0.7]: https://github.com/kevindickerson-cookbooks/example_resources/tree/v1.0.7
