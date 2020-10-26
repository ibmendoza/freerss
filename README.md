## FreeRSS

Web-based RSS Viewer and Portal.

Uses the following tools:
- [gofeed library](https://github.com/mmcdole/gofeed)
- [Svelte](https://svelte.dev)
- [Tailwind CSS](https://tailwindcss.com)

## Usage

Run once:

    $ make dep
    $ make webtools

Build and test:

    $ make clean
    $ make
    $ freerss -i portal.db

    Run 'freerss portal.db' to start the web service.

## Screenshots

![freerss portal](screenshots/freerss_portal.png)
![widgets with preview](screenshots/freerss_withpreview.png)

## Contact
    Twitter: @robdelacruz
    Source: http://github.com/robdelacruz/freerss

