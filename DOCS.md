# Documentation

- [Record](#record)
- [Edit recording](#edit-recording)
- [Import / Export](#import--export)
- [Use JavaScript libraries](#use-javascript-libraries)
- [HTML tags we don't support](#html-tags-we-dont-support)

# Record

To record, simply hit **RECORD** in the bottom top right corner:

![](https://github.com/scrimba/community/blob/master/img/record-button.png)

This will bring up a record dialog. Here you can choose if you want to record audio and choose microphone:

![](https://github.com/scrimba/community/blob/master/img/record-dialog.png)

When you're finished recording, hit **STOP RECORDING**. You'll get the ability to both *save* or *discard* your recording.

![](https://github.com/scrimba/community/blob/master/img/finish-recording.png)

# Edit recording

Once you're fininshed recording, you can edit your timeline by clicking the scissors icon. Check [this video](https://www.youtube.com/watch?v=-2sSBJusQfc) if you want to watch a walkthrough of the post processing feature:

![](https://github.com/scrimba/community/blob/master/img/brushup-button.png)

This will bring up a timeline with audio waveforms, where you can do three things: cut away sections in the beginning and/or ending, and collapse sections in between.

![](https://github.com/scrimba/community/blob/master/img/audio-waveforms.png)

### Cut beginning

To cut away a chunk in the beginning of the cast, navigate to the beginning of the timeline and grab hold of the yellow marker. It'll appear when you hover over the beginning of the timeline. Drag it for as long as you want to cut away:

![](https://github.com/scrimba/community/blob/master/img/cut-beginning.png)

### Collapse section

To collapse a section, click on where you want to start, and drag the cursor over the area you want to collapse. Then hover over the area and you'll see a **COLLAPSE** button appear. When you collapse a section, Scrimba will jump over this part in the screencast. It will not be deleted entirely, so you can always *uncollapse* it again.

![](https://github.com/scrimba/community/blob/master/img/collapse.png)

### Cut ending

If you're marking at the very end of the cast, you can **CUT** it completely away. This will delete the section for good.

![](https://github.com/scrimba/community/blob/master/img/cut.png)

This will allow you to start your next recording from any given point.

# Import / Export

You can import and export between files using the `require()` function and the `exports` object.

Exporting using `exports`:

![](https://github.com/scrimba/community/blob/master/img/exports.png)

Importing using `require()`:

![](https://github.com/scrimba/community/blob/master/img/require.png)


# Use JavaScript Libraries

To add an external JavaScript library to the cast, click the settings icon in the top right corner.

![](https://github.com/scrimba/community/blob/master/img/show-settings.png)

Paste in a link to the library and click **ADD**.

![](https://github.com/scrimba/community/blob/master/img/settings-dialog.png)

# HTML tags we don't support

There are some limitations for what kind of HTML tags you can use in a Scrimba screencast:

### `<canvas>`
Our DOM recorder does not record the content of a `<canvas>` tag, meaning the live preview window will be blank when a `<canvas>` screencast is replayed.

### `<select>`
You can use the `<select>` tag, however we only record when the select element changes selection, and not 

### `<input type="date">`
You can use this tag, but we won't record the date picker component, only when the value of the input field is changed.

### `<a>` 
You can create links, but clicking them won't result in navigating to a new page.




