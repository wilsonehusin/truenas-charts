# README

This is a fork from [TrueCharts' configuration for Shiori at v10.0.16](https://github.com/truecharts/charts/tree/master/charts/stable/shiori).

I found out that their configuration always deploys with PostgreSQL, but doesn't actually use it (data is stored in SQLite within PersistentVolume). I offered to contribute a fix so PostgreSQL will be used by default, with an option to keep existing behavior so I don't have to migrate my data from SQLite to PostgreSQL but [it was turned down](https://discord.com/channels/830763548678291466/1061739711724519485/1061745766328176742). And thus this is fork was started!

To be absolutely clear: TrueCharts is an awesome project. They have managed to package so many applications to be mostly one-click deploy on TrueNAS. Disagreements does not have to turn sour.
