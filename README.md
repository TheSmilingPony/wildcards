Wildcards for use with [Prompt Postprocessor](https://github.com/acorderob/sd-webui-prompt-postprocessor) in [SD WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) or [reForge](reForge) (should support others, but only tested in those)

```
Master character list intended for use with Prompt Post Processor
Basic label and prompt setup - All weights set to 1
Increase Weight to increase chance, set to 0 to cull
example "__Characters'female+unicorn'__" will pull a character that has the "female" AND "unicorn" label
example "__Characters'twilight'__" will simply pull twilight (would help to build short name list)
example "__Characters'pegasus,unicorn'__" will pull a character with either pegasus or unicorn label
example "__Characters'female+unicorn,male+pegasus'__ will pull a character that's either a female unicorn OR a male pegasus
```

The "popularity" label is based on tag counts for [the first ~200 characters on derpibooru](https://derpibooru.org/tags?tq=category%3Acharacter), first 10%, next 15%, next 25%, last 50%.

You can use this outright as is, but I recommend making edits to better serve your needs (refining prompts, adding labels, setting biases, cully/adding characters, etc.)
If you make changes that improve on the prompts or labels, would love for them to be shared so these can be improved and be made available for others

Note that autocomplete does not appear to pick up YAML files
