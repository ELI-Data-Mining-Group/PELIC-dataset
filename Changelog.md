# Changelog
All notable changes to the PELIC-dataset will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Changed
- Removed version outliers (3 texts with more than 3 versions)
- Removed anon_id from `test_scores.csv` for students with no written texts


## [1.1] - 2020-03-03
### Added
- Changelog.md to keep track of changes to the PELIC-dataset
- Add `created_date` column to `answer.csv` to provide more fine-grained longitudinal information about when texts were created

### Changed
- Updated links which were previously pointing to private repositories
- Cleaned `test_scores.csv` so that there is one unique test score for each anon_id/semester_id combination
- Updated `PELIC_compiled.csv` to include two new columns for `semester` and `placement_test` score

### Removed
- Nothing


## [1.0] - 2020-09-11

[Unreleased]: https://github.com/ELI-Data-Mining-Group/PELIC-dataset/compare/v1.1...master
[1.1]: https://github.com/ELI-Data-Mining-Group/PELIC-dataset/compare/v1.0...v1.1
[1.0]: https://github.com/ELI-Data-Mining-Group/PELIC-dataset/tree/v1.0
