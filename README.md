# Media bank tools (local_mediabank)

![Moodle Plugin CI](https://github.com/billsensei/moodle-local_mediabank/actions/workflows/ci.yml/badge.svg)

Companion to `contenttype_mediabank`, which it requires (install that one first). For Moodle 5.0 to 5.3. Status: **Beta**.

What it provides:
- Backup and restore of links to media bank items. With the site setting "Include linked files in course backups"
  (Site administration > Plugins > Content bank > Media bank), manual course backups carry the linked files, and a
  restore on another site turns them into ordinary copies instead of losing them.
- A command to queue videos already in the bank for streaming preparation: `php local/mediabank/cli/optimize_videos.php [--dry-run]`.
- A command-line tool for one item: `php local/mediabank/cli/item.php --id=N [--usage] [--versions] [--detach] [--restore=N]`.

Install the plugin zip from the [releases page](https://github.com/billsensei/moodle-local_mediabank/releases) under Site administration > Plugins > Install plugins (not GitHub's "Download ZIP"), after the content type. Release notes: `CHANGES.md`.

The guides for all three plugins are in the [content type repository](https://github.com/billsensei/moodle-contenttype_mediabank/tree/main/docs). Licence: GNU GPL v3 or later, see [LICENSE](LICENSE).
