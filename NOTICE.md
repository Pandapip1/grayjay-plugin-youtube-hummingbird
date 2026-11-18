# Youtube (Hummingbird)

An **unofficial** fork of FUTO's Grayjay Youtube plugin
(https://gitlab.futo.org/videostreaming/plugins/youtube), maintained for the Hummingbird app. It is not made or endorsed by
FUTO, and has its own plugin id so it never replaces the official plugin.

Licensed under the GNU Affero General Public License v3 (see LICENSE), as
the original. The source is this repository; the `hummingbird` branch is
the upstream release plus the changes below, and is what GitHub Pages
serves at https://pandapip1.github.io/grayjay-plugin-youtube-hummingbird/YoutubeConfig.json.

## Changes from the original (2026-11-17)

- Own plugin id and the name "Youtube (Hummingbird)"; published from this
  repository and signed with Hummingbird's plugin-signing key.
- UMP: wait for generated tokens (POT) before requesting media.
