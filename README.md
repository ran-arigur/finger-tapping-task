## About the finger tapping task

The finger tapping task (FTT) is a motor sequence learning task used in
psychological research.

Per [Nicola Cellini, "Memory Consolidation in Sleep Disorders" (2016)](https://www.researchgate.net/publication/308611509_Memory_Consolidation_in_Sleep_Disorders):

> The finger tapping task (FTT) is a motor sequence learning task in which participants 
> are asked to tap with their non-dominant hand a 5-digits sequence (for example 4-1-3-2-4 or 2-4-1-
> 3-2), as rapidly and accurately as possible, using the numeric key-buttons of a computer keyboard or 
> a response box. To reduce working memory load, both the numeric sequence and five white circles 
> are displayed at the center of the screen throughout the task. Every time the participants press a key, 
> one  circle  turns  into  a  black  dot.

## About this project

This project is an implementation of the finger tapping task as an HTML file, so
that installation is trivial and doesn't require any special privileges.

The page contains three "views", presented in sequence:

1. First, a researcher-facing view where the investigator can select various
   settings (the sequence; left hand vs. right hand; number of blocks in the
   session; number of seconds of tapping in each block; number of seconds of rest
   between blocks) and then switch to the participant-facing view.
2. Next, a participant-facing view that lets the participant do the session.
   (This view alternates between a "tapping" screen and a "rest" screen.)
3. Lastly, a second researcher-facing view that presents the results for the
   session, that the investigator can copy somewhere for later analysis.

This implementation was created at the request of a friend of mine,
Dr. Anna Clebone (of the University of Chicago Medicine), who intends to use it
for her research on PTSD.

## Installing

The simplest way to install this on a computer is to just copy the HTML file
([v1.html](https://raw.githubusercontent.com/ran-arigur/finger-tapping-task/main/v1.html))
onto that computer.

Alternatively, if you have access to a web server, you can put the file there
and access it over the web. (That may be more convenient if you intend to use
this on multiple computers.)

After installing, please try it out to make sure everything works as desired on
your desired system.

## Using

Once you've installed this, you can use it by opening the HTML file in your
preferred web browser (e.g. Firefox or Chrome).

A few notes:

- Hopefully it's self-explanatory. If you have any questions, please let me know
  (e.g. by opening an 'Issue').
- The results are not saved anywhere. The investigator will need to copy them
  from the "results" view and paste them somewhere persistent. (The "results"
  view presents them in tab-separated format, which should be convenient to
  paste into a spreadsheet.)
- Most or all browsers offer a "full-screen" view, so that the contents of the
  page are the only thing on the screen. I recommend using that feature, to
  reduce the "noise" for participants.
- As you select settings in the first researcher-facing view, the settings are
  copied to the URL; if you repeatedly use some of the same settings, you can
  bookmark the resulting link and reuse it later to have them pre-filled-in for
  you.

## Modifying

The contents of this project are copyrighted, but are licensed to you under
CC BY-SA 4.0, so you are permitted to share and adapt them, provided that you
comply with certain terms; please see the LICENSE file in this directory for
details.

If you make any improvements that you think other users might benefit from, I
would welcome a pull request.

## Authorship

For full authorship information, please see the LICENSE file in this directory.
The short version is that this project is by me (Ran Ari-Gur), with the 'hand'
images being adapted from an icon by [@fontawesome](https://fontawesome.com).
