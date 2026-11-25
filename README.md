# Map makers compared

An interactive comparison of audio-to-map models: **bluered**, our open-weights
map makers trained only on community maps, against an open-source automapper.
Every map is scored against maps by expert community mappers, for songs none of
our models trained on.

Live: https://rhythm-maps.dftz.org (or open `index.html` in a browser; it is a
single self-contained page that works offline).

What it shows: a leaderboard and every metric, song by song results, timing
error, onset snapping, note density over each song, the notes themselves, a
virtual player that swings each map beside the reference, training curves and
generation speed.

Credits: reference maps by their community mappers (credited on each song);
songs by their artists and labels (no audio is included); InfernoSaber by
fred-brenner (MIT licence).

The 3D view uses three.js (MIT licence, see LICENSE-three.txt), embedded in the page.
