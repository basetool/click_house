# 1.3.5
* added `ClickHouse.connexction.explain("sql")` 

# 1.3.4
* added `ClickHouse.type_names(nullable: false)`
* fixed `connection#create_table` column definitions
* `ClickHouse.add_type` now handles Nullable types automatically

# 1.3.3
* fix logger typo

# 1.3.2
* fix null logger for windows users

# 1.3.1
* added request [headers](https://github.com/shlima/click_house/pull/8) support

# 1.3.0
* added support for IPv4/IPv6 types

# 1.2.7
* rubocop version bump

# 1.2.6
* Datetime64 field type support [#3](https://github.com/shlima/click_house/pull/3)
