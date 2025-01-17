
I have watched **IM Eric Rosen's** [YouTube video](https://www.youtube.com/watch?v=qKX3jVJ5J7E) on en passant checkmates.

I noticed that mark-dev's [ep-mate.md](https://github.com/mark-dev/chessfactory-hall-of-fame/blame/master/etc/docs/results/ep-mate.md) was two years old and https://database.lichess.org shows that amount of games grows every month.

Well, how to get some fresh en passant checkmates without setting Clickhouse and wasting hdd space?

I have written [Python script](en-passant.py) that finds en passant checkmates on the fly without unpacking huge temporary files.

Here are the results of running that script:

[March 2021](March-2021.adoc)

[April 2021](April-2021.adoc)

[May 2021](May-2021.adoc)

[June 2021](June-2021.adoc)
