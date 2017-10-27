
# Lurch Web Platform, Example Sidebar Application

This is an example application built on the
[Lurch Web Platform](https://github.com/lurchmath/lurch),
to show developers how to use that platform.  It assumes you've already
seen and understood the simpler examples,
[one](https://github.com/lurchmath/lwp-example-simple),
[two](https://github.com/lurchmath/lwp-example-complex), and
[three](https://github.com/lurchmath/lwp-example-math).

[Visit the app here.](https://lurchmath.github.io/lwp-example-sidebar)

The app shows an example of how you could provide a sidebar in which to
display additional (non-word-processing) UI for interacting with a user.

This particular app lets you write code in your document in a very literate
style, using nested groups, and it shows you the corresponding code in the
sidebar on the right.  The two are kept synced at all times, and tools are
shown for copying code, running code, or changing language.

Try this:

 * Launch the application from the link above.
 * From the "Control flow" menu on the toolbar, choose
   "For each integer in a range."
 * Move your cursor throughout the boilerplate code to see how it is
   structured.
 * Click the "Run this code" link at the top of the sidebar, then click
   through the five popup windows the code generates.
 * Choose a new language from the dropdown at the top of the sidebar, and
   watch the code update.

Read the (heavily commented) code here:

 * [App code](lwp-example-sidebar.litcoffee) for this specific example
 * [HTML code](index.html) that loads the platform and application

There is also a very simple [build process](gulpfile.litcoffee).
