## v0.0.1 [2013-10-22]

  * Initial Release

## v0.0.2

#### Features

- Add an admin UI
- Deb and RPM packages

#### Bugfixes

- Fix some nil pointer dereferences
- Cleanup the aggregators implementation

## v0.0.5

#### Features

- Cache passwords in memory to speed up password verification
- Add MERGE and INNER JOIN support

#### Bugfixes

- All columns should be returned if `select *` was used
- Read/Write benchmarks

## v0.0.6

#### Features

- Add count(distinct(..)) support

#### Bugfixes

- Reuse levigo read/write options.

## v0.0.7

#### Features

- include the admin site in the repo to make it easier for newcomers.

## v0.0.8

#### Features

- Add a way to reset the root password from the command line.
- Add distinct(..) and derivative(...) support
- Print test coverage if running go1.2

#### Bugfixes

- Fix the default admin site path in the .deb and .rpm packages.
- Fix the configuration filename in the .tar.gz package.

## v0.0.9 (unreleased)

#### Features

- Add stddev(...) support
- Better docs, thanks @auxesis and @d-snp.
- Return an error if an empty username was given when creating a new user.

#### Bugfixes

- set CC and PYTHONPATH for mac os users if they aren't set.
- Set PYTHONPATH and CC appropriately on mac os x.
- Fix the 386 rpm and debian packages init scripts.
- Don't set goroot if it was already set. #22
- Fix queries that use the median aggregator. #25
