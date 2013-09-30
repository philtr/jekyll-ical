# Jekyll iCal Sync

Sync a set of Jekyll blog posts with an ical feed. Useful for managing upcoming events on Jekyll
blogs.

## Configuration

Requires certain environment variables to be set:

<table>
  <tr>
    <td>GIT_REPO</td>
    <td>URL of the git repository</td>
  </tr>
  <tr>
    <td>GIT_USERNAME</td>
    <td>Username for git repository (if required)</td>
  </tr>
  <tr>
    <td>GIT_PASSWORD</td>
    <td>Password for git repositiory (if required)</td>
  </tr>
  <tr>
    <td>ICAL_FEED</td>
    <td>iCal feed of events (e.g. from Google calendar)</td>
  </tr>
  <tr>
    <td>EVENT_POSTS_DIR</td>
    <td>Path to event posts in repository, excluding the `posts` dir. For example, if your event
    posts are in "/events/_posts", put "/events"</td>
  </tr>
  <tr>
    <td>USE_ARCHIVE</td>
    <td>Set to "1" if you want to use subdirectories in your events folder for upcoming and past
    events. Useful if you want to hide past events on your home page, for example.</td>
  </tr>
</table>

## Usage

Meant to be run as a scheduled task. This should work on any host, including your local machine and
Heroku. With Heroku, you'll need to add the Scheduler add-on and the sync command.

## License

Released under he MIT License (MIT)

Copyright &copy; 2013 Phillip Ridlen

See [LICENSE.txt](/license.txt) for more.

