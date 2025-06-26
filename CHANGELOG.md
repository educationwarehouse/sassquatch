# Changelog

<!--next-version-placeholder-->

## v1.0.1 (2025-06-26)

### Fix

* Map `platform.system() = darwin` to `macos` for proper dart-sass downloading on mac (intel and arm) ([`4892bf1`](https://github.com/educationwarehouse/sassquatch/commit/4892bf1b005110e947b2fff4912bd651e3967f07))

## v1.0.0 (2025-05-19)

### Fix

* Make filename optional so you can do `--version` etc. ([`ba435ce`](https://github.com/educationwarehouse/sassquatch/commit/ba435ceeb40ecc007b59117cfa9825fcb3c0d2d3))
* Support `sassquatch -` to read from stdin again ([`065bd7b`](https://github.com/educationwarehouse/sassquatch/commit/065bd7b34682a5a6ac017d78fb4eede2740abc37))

### Documentation

* Improved readme ([`74564df`](https://github.com/educationwarehouse/sassquatch/commit/74564df4470e1b4f21760e8eacc9860148d050d5))
* Added README ([`5af6262`](https://github.com/educationwarehouse/sassquatch/commit/5af6262c0d8a3c1e0ccd22d7bc95db89545083b9))

## v0.1.4 (2025-05-12)

### Fix

* Bump to `sleazy` 0.2.0 with updated syntax; started on tests (first test: if dart/sass gets embedded properly) ([`1d2a8e7`](https://github.com/educationwarehouse/sassquatch/commit/1d2a8e71cacac1f9e0c93b8d496ddea6a1e096d5))

## v0.1.3 (2025-05-09)

### Fix

* Set load_path to list, add defautls to CompileError ([`0ba2713`](https://github.com/educationwarehouse/sassquatch/commit/0ba27137bd49369cc3c3c0fe2e1940dcca820c25))

## v0.1.2 (2025-05-09)

### Fix

* Rename `CompileError` and export more ([`de6e7cf`](https://github.com/educationwarehouse/sassquatch/commit/de6e7cfbdce2c1682d19a5f6c15316239ca772ea))

## v0.1.1 (2025-05-09)

### Fix

* --sass-update, support file/directories better ([`9ded7af`](https://github.com/educationwarehouse/sassquatch/commit/9ded7afd511384910a3cefe08730d46f4ce47483))

## v0.1.0 (2025-05-09)

### Feature

* Initial repo ([`2a20c93`](https://github.com/educationwarehouse/sassquatch/commit/2a20c9374713173c460aba93b3013e1571e8559a))
