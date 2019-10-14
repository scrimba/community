# Documentation

- [Frequently asked questions (FAQ)](https://github.com/scrimba/community/blob/master/FAQ.md)
- [Do a recording](#do-a-recording)
- [Edit your recording](#edit-your-recording)
- [The browser](#the-browser)
- [The console](#the-console)
- [Import / Export](#import--export)
- [External JavaScript libraries](#external-javascript-libraries)
- [HTML and JS limitations](#html-and-js-limitations)
- [Editor keyboard shortcuts](#editor-keyboard-shortcuts)

# Do a recording

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
<img width="120" src="https://github.com/scrimba/community/blob/master/img/finish-recording.png">
</p>

You can also check out this [YouTube video](https://youtu.be/rDIlR71omg4), which amongst other things goes through how to create a Scrimba screencast.

# Edit your recording

Once you're fininshed recording, you can edit your timeline by clicking the **BRUSHUP** icon. Check [this video](https://www.youtube.com/watch?v=-2sSBJusQfc) if you want to watch a walkthrough of the post processing feature:

<p align="center">
<img width="100" src="https://github.com/scrimba/community/blob/master/img/brushup-button.png">
</p>

This will bring up a timeline with audio waveforms, where you can do three different editations: cut, speedup sections or silence a section. You can also make a section loop so that you can hear through it, however this is for editation purposes only.

![](https://github.com/scrimba/community/blob/master/img/audio-waveforms.png)

To edit a section, hold the shift button down, click on the timeline and then drag the cursor over the area you want to edit. Then you'll see a menu appear with the editing options.

![](https://github.com/scrimba/community/blob/master/img/collapse.png)

# The browser

The browser window can be toggled with the BROWSER option in the left sidebar. Once opened, you can choose between two modes: *fixed* or *floating*. We recommend you to use the *fixed* option. This forces you to focus on *either* the code or the browser window. As a result, the viewing experience of your screencast will become better, especially on smaller screen sizes. Secondly, we're likely to limit the size of *floating* browser windows in the future, meaning it'll only be suitable for small examples.

To toggle between *fixed* and *floating* mode in the browser, click the green button in the top left corner.

## Fixed

Here's how it looks like when the browser window is fixed and you're focusing on it. As you can see, the background is faded out.

![](https://github.com/scrimba/community/blob/master/img/fixed-browser.png)

When you click outside the browser (or on the yellow minimize-button) it'll will move out of the way, so that you can focus on the code.

![](https://github.com/scrimba/community/blob/master/img/minimized-browser.png)


## Floating

Here's how it looks with the browser window in *floating* mode. As you can see, this opens up for the possibility to focus on both the code and the browser at the same time.

![](https://github.com/scrimba/community/blob/master/img/floating-browser.png)

The reason we want to limit instructors ability to do this, is that it can introduce problems when we're adapting your screencast to be viewed on smaller screen sizes (i.e. the browser appearing above code). This adaptation is much easier to do when we know if you're focusing on code *or* browser.

# The console

You can log out to the console in Scrimba screencasts. To toggle the console, click the CONSOLE option in the left sidebar of the project.

![](https://github.com/scrimba/community/blob/master/img/console.png)


We'll also show the latest console log for a few seconds after running the code. This means you can keep the console closed, and still take advantage of it.

![](https://github.com/scrimba/community/blob/master/img/smart-console.png)

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
You can use the `<select>` tag, however we only record when the select element changes selection, and not the dropdown effect.

### `<input type="date">`
You can use this tag, but we won't record the date picker component, only when the value of the input field is changed.

### `<a>` 
You can create links between the HTML files in your project. However, external links won't result in anything.
 
### `alert()`, `prompt()` and `confirm()`
These function calls won't be recorded by the Scrimba recorder, so there is no point using them in a Scrimba screencast. We recommend you to use `console.log()` instead where that's possible.

# Editor keyboard shortcuts

> [For Windows](https://github.com/scrimba/community/blob/master/SHORTCUTS-WINDOWS.md)

> [For Mac](https://github.com/scrimba/community/blob/master/SHORTCUTS-MAC.md)
