this repo is intended to be used for debugging [this](https://github.com/renovatebot/renovate/discussions/25051#discussioncomment-7195375) issue of the renovate bot

Dependencies in `Cargo.toml` that are set up with git (e.g. `serde_json = { git = "https://github.com/serde-rs/json", tag = 'v1.0.105' }`) are not updated.
