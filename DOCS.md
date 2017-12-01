# Documentation

- [Record](#record)
- [Edit recording](#edit-recording)
- [The console](#the-console)
- [Import / Export](#import--export)
- [External JavaScript libraries](#external-javascript-libraries)
- [HTML and JS limitations](#html-and-js-limitations)
- [Embedding](#embedding)

# Record

To record, simply hit the **Record** button in the top right corner:

<p align="center">
<img width="100" src="https://github.com/scrimba/community/blob/master/img/record-button.png">
</p>

This will bring up a record dialog where you can choose which microphone you want to use:

<p align="center">
<img width="600" src="https://github.com/scrimba/community/blob/master/img/record-dialog.png">
</p>

When you're finished recording, hit the **STOP** button. You'll then get the ability to both *save* or *discard* your recording.

<p align="center">
<img width="80" src="https://github.com/scrimba/community/blob/master/img/finish-recording.png">
</p>

# Edit recording

Once you're fininshed recording, you can edit your timeline by clicking the **BRUSHUP** icon. Check [this video](https://www.youtube.com/watch?v=-2sSBJusQfc) if you want to watch a walkthrough of the post processing feature:

<p align="center">
<img width="100" src="https://github.com/scrimba/community/blob/master/img/brushup-button.png">
</p>

This will bring up a timeline with audio waveforms, where you can do three things: cut away sections in the beginning and/or ending, and collapse sections in between.

![](https://github.com/scrimba/community/blob/master/img/audio-waveforms.png)

### Collapse section

To collapse a section, click on where you want to start, and drag the cursor over the area you want to collapse. Then hover over the area and you'll see a **COLLAPSE** button appear. When you collapse a section, Scrimba will jump over this part in the screencast. It will not be deleted entirely, so you can always *uncollapse* it again.

This [YouTube video](https://youtu.be/fsKJZvwvbHM) also explains in detail how to collapse sections.

![](https://github.com/scrimba/community/blob/master/img/collapse.png)

# The console

You can log out to the console in Scrimba screencasts. However, you have to manually open/close it. To toggle the console, click the following icon in the top right corner of the player window.

<p align="center">
<img width="500" src="https://github.com/scrimba/community/blob/master/img/console.png">
 </p>


# Import / Export

You can import and export between files using the `require()` function and the `exports` object.

Exporting using `exports`:

![](https://github.com/scrimba/community/blob/master/img/exports.png)

Importing using `require()`:

![](https://github.com/scrimba/community/blob/master/img/require.png)



# External JavaScript Libraries

To use external scripts, you can either link to a CDN via a script tag or use npm.

## Script tag

![](https://github.com/scrimba/community/blob/master/img/scripts.png)

## npm

First click the npm icon in the top right corner. This will open up a dialog where you can specify which package you want to add.

<p align="center">
<img width="500" src="https://github.com/scrimba/community/blob/master/img/npm.png">
</p>

Import the package to a .js file using `import` or `require`:

![](https://github.com/scrimba/community/blob/master/img/npm-import.png)


# HTML and JS limitations

There are some limitations for what kind of HTML tags and JavaScript features you can use in a Scrimba screencast:

### `<canvas>`
Our DOM recorder does not record the content of a `<canvas>` tag, meaning the live preview window will be blank when a `<canvas>` screencast is replayed.

### `<select>`
You can use the `<select>` tag, however we only record when the select element changes selection, and not 

### `<input type="date">`
You can use this tag, but we won't record the date picker component, only when the value of the input field is changed.

### `<a>` 
You can create links, but clicking them won't result in navigating to a new page.
 
### `alert()`, `prompt()` and `confirm()`
These function calls won't result in a popup box, so there is no point using them in a Scrimba screencast.

# Embedding

To get the embed code for a screencast, click the settings icon in the top right corner:

![](https://github.com/scrimba/community/blob/master/img/settings.png)

Copy the embed code from the dialog:

![](https://github.com/scrimba/community/blob/master/img/embed.png)

Note: you can only embed casts that are both published *and* includes an audio recording.
