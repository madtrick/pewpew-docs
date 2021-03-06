# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.1.2] - 2020-04-07

### Fixed

- Valid versions specified by clients are again allowed

## [2.1.1] - 2020-04-07

### Fixed

- The number of tokens per player is again replenished on each tick

## [2.1.0] - 2020-04-07

### Added

- Add the initial `life` and `tokens` of the player to the successful `RegisterPlayer` response

## [2.0.0] - 2020-04-07

### Added

- Add `Tick` notification. This notification is sent after all the responses and other notifications have been sent to the player

## [1.1.0] - 2020-04-05

### Added

- Include game settings (player speed, shot speed, ...) in `JoinGameNotification` messages.
