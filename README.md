Wildcards for use in SD WebUI or reForge with Prompt Postprocessor
https://github.com/acorderob/sd-webui-prompt-postprocessor

```
Master character list intended for use with Prompt Post Processor
Basic label and prompt setup - All weights set to 1
Increase Weight to increase chance, set to 0 to cull
example "__Characters'female+unicorn'__" will pull a character that has the "female" AND "unicorn" label
example "__Characters'twilight'__" will simply pull twilight (would help to build short name list)
example "__Characters'pegasus,unicorn'__" will pull a character with either pegasus or unicorn label
example "__Characters'female+unicorn,male+pegasus'__ will pull a character that's either a female unicorn OR a male pegasus
```

You can use this outright as is, but I recommend making edits to better serve your needs (refining prompts, adding labels, setting biases, cully/adding characters, etc.)
If you make changes that improve on the prompts or labels, would love for them to be shared so these can be improved and be made available for others
