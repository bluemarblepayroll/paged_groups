# 2.1.0 (February 14th, 2019)

* Added limit option for builder.  This (optionally) ensures no group can exceed a given threshold.

# 2.0.0 (January 29th, 2019)

* Breaking Change: Builder#add signature changed from groups splat operator to two-dimensional array.  Splat operator introduces an under-the-hood copy and can impact performance with large argument lists.

# 1.0.0 (January 26th, 2019)

Initial Release
