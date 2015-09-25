# Ideas for Outreachy internships

### Field Papers UI improvements

One of the tasks planned for the current Cadasta work on Field Papers
is to extract the Javascript UI layer used in Field Papers into a
seperate component that can be used in other mapping applications
(obviously including Cadasta!).  The UI as it stands is quite sparse,
and there are a few things that could be done to improve it, some of
which might be quite fun:

 * *More flexible atlas region definition* At the moment, atlases are
   defined over a rectangular grid of pages, but there are use cases
   for more interesting arrangements, including rotating the grid (so
   that page boundaries can be made parallel to roads and other linear
   features) and creating pages along a linear or polyline track (for
   surveying roads and other linear features or for surveying along
   GPS/KML tracks).
   [Issues: [#179](https://github.com/fieldpapers/fieldpapers/issues/179),
   [#153](https://github.com/fieldpapers/fieldpapers/issues/153)]

 * *Bug fixes* There are quite a few outstanding issues on the UI side
   in Field Papers, of varying levels of annoyance.  Dealing with some
   of these might be a good way for an intern to get started.
   [Issues: [#146](https://github.com/fieldpapers/fieldpapers/issues/146),
   [#145](https://github.com/fieldpapers/fieldpapers/issues/145),
   [#142](https://github.com/fieldpapers/fieldpapers/issues/142),
   others?]

 * *UI styling* This is potentially the most fun part.  The Field
   Papers UI is pretty simple, and there are a number of changes I
   could imagine making to make it a bit more configurable for
   embedding in web apps other than the main Field Papers site.  All
   the obvious things: making colours and the sub-components of the UI
   (buttons, handles, etc.) configurable.  I'm sure Chandra and the
   new design person would have suggestions of how best to do this,
   and it would also be a good way for the intern to contribute
   something visible to the main Cadasta platform, since they could be
   responsible for the styling of the Field Papers UI on the main
   Cadasta site.

I think this would work best for an internship if the intern spent a
week or two on code familiarisation, getting a development environment
set up and fixing a couple of small UI bugs from the list above --
that way they can generate PR-able changes quite quickly.  Once
they're a bit familiar with the code, they could then decide which of
the two bigger parcels of work they'd like to address first.  My
inclination would be to suggest UI styling first, since again it
should give quick visible results, and it will also lead to a deeper
understanding of what's going on in the code, which will be needed for
modifying the atlas region definition.

Skills required: just front-end Javascript!
