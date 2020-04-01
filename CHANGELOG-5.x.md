# Changelog for 5.x

This changelog references the relevant changes (bug and security fixes) done to `orchestra/model`.

## 5.0.0

Released: 2020-03-09

### Changes

* Update support to Laravel Framework v7.

### Removed

* Remove `Orchestra\Model\HS`, use `Laravie\Dhosa\HotSwap`.
* Remove `Orchestra\Model\Concerns\Swappable`, use `Laravie\Dhosa\Concerns\Swappable`.
* Remove deprecated `Orchestra\Model\Concerns\AdvancedSearch`, use `Orchestra\Model\Concerns\Searchable`.
* Remove deprecated `getSearchableRules()`, use `getSearchableTerms()`.