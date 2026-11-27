# Dockbar privacy policy

*Last updated: 27 November 2026*

Dockbar is a replacement for the Windows taskbar, made by Raunak Kushwaha. This policy covers every
version of Dockbar: the Microsoft Store version and the downloads on GitHub.

**In short: Dockbar collects nothing. Everything it reads stays on your PC.**

## What Dockbar reads on your PC

To draw a taskbar, Dockbar reads what the Windows taskbar reads:
- your open windows, their titles and icons, and your pinned apps
- what's playing (title, artist, album art) and the volume
- the network, battery and notification status
- the jump lists apps keep for themselves, such as recent files

All of this is used only to show it to you on the bar. None of it is stored, except what's listed
below, and none of it is sent anywhere, except song details for lyrics if you turn them on (see Network).

The optional **Visualiser** add-on (GitHub version) also listens to the sound your PC is playing, to make its
visuals move with the music. It's analysed as it plays and never recorded, stored or sent anywhere.

## What Dockbar stores

Dockbar keeps a few files in your user profile:
- your settings
- your pinned apps
- a log of errors, used only for fixing bugs

If you download the Visualiser add-on, it also keeps its own files, the lyrics of songs it has looked up, and
the taskbar's current colour (so the edge glow can match it) in the `Dockbar` folder of `%LocalAppData%`.

They never leave your PC. Uninstalling the Microsoft Store version removes them. You can also delete them
at any time: they're in the `Dockbar` folders of `%AppData%` and `%LocalAppData%`.

## Network

- **Microsoft Store version:** Dockbar makes no network requests of its own. The Microsoft Store delivers
  its updates.
- **GitHub version:** once a day, if "Check for updates" is on, Dockbar asks GitHub's public releases page
  whether a newer version is out. The request carries no information about you beyond what any web
  request does (such as your IP address, seen by GitHub). It's governed by
  [GitHub's privacy statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).
  You can turn it off in Dockbar's settings.
- **Visualiser add-on (GitHub version, optional):** downloading it from Dockbar's settings fetches it from
  GitHub's releases, as above. If you turn on **Synced lyrics**, the title, artist, album and length of the
  song that's playing are sent to [LRCLIB](https://lrclib.net), a free and open lyrics service, to find that
  song's lyrics. Nothing else about you is sent, though like any web request it shows LRCLIB your IP address. Each song's lyrics are then kept on your PC (in the
  `Dockbar\Lyrics` folder of `%LocalAppData%`), so a song is looked up only once. With lyrics off, nothing about
  your music leaves your PC.

Dockbar has no analytics, no advertising, no accounts and no tracking of any kind.

## Children

Dockbar collects no personal information from anyone, including children.

## Changes

Any change to this policy will be published on this page, with a new date at the top.

## Contact

Questions about privacy: [open an issue](https://github.com/Raunak-kushwaha/dockbar-release/issues).
