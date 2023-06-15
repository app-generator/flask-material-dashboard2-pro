# Change Log

## [1.0.3] 2023-06-15
### Changes

- UI: Material Dash 2 PRO `v3.0.2`

## [1.0.2] 2023-02-11
### Changes

- Codebase Improvements
- Deployment-ready for Render (CI/CD)
  - `render.yaml`
  - `build.sh`
- `DB Management` Improvement
  - `Silent fallback` to **SQLite**

## [1.0.1] 2022-04-01
### Fixes

- **Patch ImportError**: [cannot import name 'safe_str_cmp' from 'werkzeug.security'](https://docs.appseed.us/content/how-to-fix/importerror-cannot-import-name-safe_str_cmp-from-werkzeug.security)
  - `Werkzeug` deprecation of `safe_str_cmp` starting with version `2.1.0`
    - https://github.com/pallets/werkzeug/issues/2359

## [1.0.0] 2021-12-17
### Initial release

- UI: Material Dashboard 2 PRO v3.0.2
- Flask Codebase: v2.0.0
