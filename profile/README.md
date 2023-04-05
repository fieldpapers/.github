[Field Papers](https://fieldpapers.org) is a pen-and-paper workflow for mapping with [OpenStreetMap](https://openstreetmap.org/about). It works like this:

1. 🖨️ Create and print an atlas for your area of interest
2. ✍️ Markup your paper atlas in the field
3. 📸 Scan and upload your annotated pages as "snapshots"
4. 🧑‍💻 Edit OpenStreetMap atop your snapshots

This workflow benefits a variety of use-cases:

- 📴 **Low-tech & offline** – data can be gatherered without mobile devices or network connectivity
- 🏃‍♀️ **Quick, accessible startup** – surveying doesn't require computer skills or much training
- 👨‍👩‍👧‍👦 **Scalable collaboration** – tasks can easily be divided up within groups
- 🧑‍🏫 **Geographic education** – student mappers can experience hands-on learning
- 🗺️ **Extensible atlases** – paper OpenStreetMap atlases are useful for many purposes, not just surveying!

Intrigued? Go ahead and [create an atlas](https://fieldpapers.org/compose), or check out the latest [atlases](https://fieldpapers.org/atlases) and [snapshots](https://fieldpapers.org/snapshots) from around the globe. More info is available on our [about page](https://fieldpapers.org/about) and [OSM Wiki page](https://wiki.openstreetmap.org/wiki/Field_Papers).

## Connect

We hang out in the `#fieldpapers` channel on [OSM US Slack](https://osmus.slack.com) (you can [invite yourself](https://slack.openstreetmap.us)). Say hi! You can also email us at help@fieldpapers.org, or tweet at [@fieldpapers](https://twitter.com/fieldpapers).

## Contributing

Field Papers is an active open source project maintained by [OpenStreetMap US](https://openstreetmap.us). We welcome volunteer contributions! Note that all activity is subject to our [Code of Conduct](https://wiki.openstreetmap.org/wiki/Foundation/Local_Chapters/United_States/Code_of_Conduct_Committee/OSM_US_Code_of_Conduct). Please take a minute to read it, and remember to be nice.

### Issues

Have a bug report or feature request? Browse our [issue tracker](https://github.com/fieldpapers/fieldpapers/issues) to see if it's already been posted. If not, feel free to [open a new issue](https://github.com/fieldpapers/fieldpapers/issues/new).

### Translations

Interface translation is critical to ensuring the app is usable by mappers the world over. You can help translate at our [Transifex project](https://app.transifex.com/fieldpapers/).

### Development

Field Papers lives across a number of repositories, each of which has its own development documentation.

* [fieldpapers](https://github.com/fieldpapers/fieldpapers) - the umbrella project, primarily for tracking issues
* [fp-web](https://github.com/fieldpapers/fp-web) - the website (Ruby on Rails)
* [fp-tasks](https://github.com/fieldpapers/fp-tasks) - the task server, which handles atlas and snapshot generation (Python, NodeJS)
* [fp-tiler](https://github.com/fieldpapers/fp-tiler) - the tile server (NodeJS)
* [tilelive-fieldpapers](https://github.com/fieldpapers/tilelive-fieldpapers) - the tilelive module that drives the tile server (NodeJS)
* [josm-fieldpapers](https://github.com/fieldpapers/josm-fieldpapers) - the [JOSM](https://josm.openstreetmap.de) plugin (Java)

We welcome pull requests that are consistent with the development goals of the project. Open an issue first if you're not sure. If you're new to open source development, you can learn how to make a pull request [here](https://docs.github.com/en/pull-requests).

## Downstream usage

Field Papers is intended to be easily deployable to your own environment, with and without forking. Let us know if you encounter any downstream issues, or if you need help with your use-case.
