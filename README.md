<p><img src="https://github.com/jshute96/SeeWhatISee/blob/main/src/icons/icon-128.png?raw=true" alt="icon"></p>

# SeeWhatISee Gemini Extension

## Chrome extension

SeeWhatISee is the ultimate Chrome extension screenshot tool for vibe-coding: Share screenshots, HTML, or selected text with your coding agent — CLI or web.

Learn more at https://github.com/jshute96/SeeWhatISee.
Development happens in that repository.  Issues and PRs should be filed in that repository.

This GitHub project is the released version of the Gemini extension for SeeWhatISee.

## Gemini skills

- `/see-what-i-see` — read the latest snapshot and describe it
- `/see-what-i-see-watch` — watch for new snapshots to appear, and then look at them when they appear

If you've added a prompt with the snapshot, Gemini will follow it.

You can also add prompts after the commands above and they'll be applied
on each snapshot. For example,

- `/see-what-i-see` `What font is the heading on this page?`
- `/see-what-i-see-watch` `Just report the snapshot filenames`

## Installation

Add the Gemini extension:

```bash
gemini extensions install https://github.com/jshute96/SeeWhatISee-gemini
```

## Development

This GitHub project stores the released version of the Gemini extension.

The development project is https://github.com/jshute96/SeeWhatISee.

This project can be used alone for experimentation.

## License

The extension and skills are MIT-licensed (see `LICENSE`).
