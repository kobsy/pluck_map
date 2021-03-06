## v1.0.0 (2019 Jul 17)

* FIX: Respect default_scopes for relationships (@boblail)

## v1.0.0.rc2 (2019 Jun 17)

* FEATURE: Add structured attributes to allow nesting attributes as a hash (@kobsy)

## v1.0.0.rc1 (2019 May 12)

* BREAKING: Remove deprecated features/methods (@boblail)
* FEATURE: Optimize `to_json` when a presenter doesn't need to process values in Ruby (@boblail)
* FEATURE: Add `has_many` and `has_one` DSL for presenting nested resources (@boblail)

## v0.6.2 (2019 Jun 13)

* FIX: Allow presenting a subclass of the presenter's model (@kobsy)

## v0.6.1 (2019 May 12)

* FIX: Aliased SQL expressions to work-around a bug with Rails Postgres adapter (@kobsy)

## v0.6.0 (2019 May 5)

* REFACTOR: Deprecated `Presenter#no_map?` and introduced `Attributes#will_map?` to replace it (@boblail)
* REFACTOR: Deprecated passing strings to `:select` (Known-safe values can be wrapped in `Arel.sql`) (@boblail)

## v0.5.0 (2019 May 1)

* REFACTOR: Introduced a new syntax for defining PluckMap Presenters and deprecated calling `PluckMap::Presenter.new` with a block (@boblail)
* FEATURE: Add `to_json` presenter method (@boblail)
* FEATURE: Add `to_csv` presenter method (@boblail)

## v0.4.1 (2019 Apr 26)

* FIX: Use `PluckMap::NullLogger` when `Rails.logger` is `nil` (@boblail)

## v0.4.0 (2019 Apr 16)

* REFACTOR: Introduced several DEPRECATION WARNINGs that will be harvested in v1.0.0 (@boblail)
* REFACTOR: Changed the implementation of the private method `selects` (@boblail)

## v0.3.0 (2019 Apr 7)

* IMPROVEMENT: Add support for MySQL (@boblail)

## v0.2.1 (2018 Mar 29)

* FIX: Allow static values to be falsey (@kobsy)

## v0.2.0 (2018 Mar 28)

* FIX: Allow static values to be falsey (@kobsy)

## v0.1.0 (2015 Nov 7)

* Initial version (@boblail)
