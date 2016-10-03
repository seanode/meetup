Meetup Checklist
================

**NOTE**: This is our template for organizing a meetup and making sure we get
all the little details covered! When we're starting a new meetup, please
[open a new issue](https://github.com/seanode/meetup/issues) with a title
like `Meetup - DATE - TOPICS`, paste this template in, remove this boilerplate
section you're reading right now, and tweak specific to the details of the
event.

## Pre-event

* [ ] Get a venue host.
    * [ ] Confirm **maximum seating capacity** and enter in meetup RSVP limit.

* [ ] Get a food / beverages host _or_ confirm venue host will provide.
    * [ ] Confirm _what_ is actually going to be served (e.g., snacks vs. dinner).

* [ ] Get first speaker.
    * [ ] Get title / abstract / bio / twitter handle.
    * [ ] Confirm talk length (20-30 mins) and limiting commercial content.

* [ ] Get second speaker.
    * [ ] Get title / abstract / bio / twitter handle.
    * [ ] Confirm talk length (20-30 mins) and limiting commercial content.

* [ ] Get an MC.

* [ ] Confirm a workable date with all parties involved. We prefer
  Tues - Thursday.
      * [ ] Check for meetup conflicts with SeattleJS and Seattle React.
      * [ ] Check for potential complicating events nearby (e.g., a Sounders
        game when we're hosting in SoDo).

* [ ] Email all participants when date / venue is confirmed to introduce
  everyone.

## Event announcement

* [ ] **Website Post**: Create base content in markdown with a new
  [pull request](https://github.com/seanode/seanode.github.io/pulls) against
  the `development` branch.
     * [ ] **Title**: Should be something like `[WIP] DATE Meetup - TOPIC`
     * [ ] **New File**: Create a new Markdown file with a name something
       like: `_posts/DAY_OF_POST-MONTH_OF_MEETUP-TOPIC.md`. So for example,
       `_posts/2016-09-09-september-2016-azure-iot-using-node.md`.
          * [ ] **Meetup link**: We have a link to the meetup which won't exist
            until after the Meetup version of the event is posted, so when
            creating the MD post, leave as `[meetup](XXX)`. Then, once the
            actual `meetup.com` link is up, paste in and replace the `XXX`s with
            something like `[meetup](https://www.meetup.com/Seattle-Node-
            js/events/234006156/)`.
    * [ ] Open pull request for review.
    * [ ] Once approved and meetup is posted, finish content (e.g., meetup link)
      and merge.
    * [ ] Open new PR to merge `development` into `master` causing the website
      to actually get updated.

* [ ] **Meetup Post**: Once the content is ready, then post the meetup at:
  http://www.meetup.com/Seattle-Node-js/events/?action=new Make sure to enter:
      * [ ] Title: The `What should we do?` section.
      * [ ] Date / time: Typically 6:30 - 9:30 unless otherwise specified by
        venue host.
      * [ ] Location: Confirm floors, "extra" helpful information, etc.
      * [ ] Body: Paste HTML from WIP GitHub post. Then check it all rendered
        correctly.
            * [ ] Remove the `XXX` `meetup` link from the post.
      * [ ] RSVP settings:
          * [ ] Set a maximum number of RSVPs
          * [ ] Uncheck `Allow members to go with up to __ guests` button.
            (We want all our attendees to be meetup members.)
      * [ ] Click the `Schedule this meetup now`
      * [ ] Also do the email members option presented after scheduling the
        meetup.

## Week before meetup

* Friday before meetup check in:
    * [ ] Email host, speakers to check in with any last minute details.
    * [ ] Confirm MC is ready to host. MC's should review informal "MC Guide".

* [ ] Have an awesome event!
