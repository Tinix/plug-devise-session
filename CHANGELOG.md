# Changelog

## [Unreleased]
### Added
- Function to delete user auth data (`PlugDeviseSession.Helpers.delete_user_auth_data/2`).

## [0.2.0] - 2018-07-29
### Added
- Functions to get and put user auth data (`PlugDeviseSession.Helpers.get_user_auth_data/2` and `PlugDeviseSession.Helpers.put_user_auth_data/4`).

### Deprecated
- `PlugDeviseSession.Helpers.get_user_id/2` in favor of `PlugDeviseSession.Helpers.get_user_auth_data/2`