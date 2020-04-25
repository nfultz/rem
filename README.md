# `rem` - GTD using bash, vim and remind

This is a small unified script and journal, which can be used to
implement GTD and/or journaling a la Jeff Huang.

### Configuration

* Line 3 - set your time zone, if you aren't in Los Angeles.
* Line 4 - set your editor callback. By default, it uses vim with all but the last section folded.
* Lines 7,37 - reminders
* Lines 38,$ - Notes and journal

### Usage

```
rem
```

to view today's journal in your editor. If today's entry is not in the journal yet,
it is created from the output of `remind`.

### Requirements

* bash
* remind
* vim (or another terminal editor)

### See also

[remind](https://dianne.skoll.ca/projects/remind/)

[Jeff Huang's productivity text file](https://jeffhuang.com/productivity_text_file/)

[Mike Harris looks at remind](http://www.43folders.com/2005/02/24/guest-mike-harris-looks-at-remind)
