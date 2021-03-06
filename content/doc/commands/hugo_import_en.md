---
date: 2015-11-25T23:10:39+01:00
doc:
- commands_en
slug: hugo_import
title: hugo import
url: /doc/commands/hugo_import
---

## hugo import

Import your site from others.

### Synopsis


Import your site from other web site generators like Jekyll.

Import requires a subcommand, e.g. `hugo import jekyll jekyll_root_path target_path`.

### Options inherited from parent commands

```
  -b, --baseURL="": hostname (and path) to the root, e.g. http://spf13.com/
  -D, --buildDrafts[=false]: include content marked as draft
  -F, --buildFuture[=false]: include content with publishdate in the future
      --cacheDir="": filesystem path to cache directory. Defaults: $TMPDIR/hugo_cache/
      --canonifyURLs[=false]: if true, all relative URLs will be canonicalized using baseURL
      --config="": config file (default is path/config.yaml|json|toml)
  -d, --destination="": filesystem path to write files to
      --disableRSS[=false]: Do not build RSS files
      --disableSitemap[=false]: Do not build Sitemap file
      --editor="": edit new content with this editor, if provided
      --ignoreCache[=false]: Ignores the cache directory for reading but still writes to it
      --log[=false]: Enable Logging
      --logFile="": Log File path (if set, logging enabled automatically)
      --pluralizeListTitles[=true]: Pluralize titles in lists using inflect
      --preserveTaxonomyNames[=false]: Preserve taxonomy names as written ("Gérard Depardieu" vs "gerard-depardieu")
  -s, --source="": filesystem path to read files relative from
      --stepAnalysis[=false]: display memory and timing of different steps of the program
  -t, --theme="": theme to use (located in /doc/themes/THEMENAME/)
      --uglyURLs[=false]: if true, use /filename.html instead of /filename/
  -v, --verbose[=false]: verbose output
      --verboseLog[=false]: verbose logging
```

### SEE ALSO
* [hugo](/doc/commands/hugo/)	 - hugo builds your site
* [hugo import jekyll](/doc/commands/hugo_import_jekyll/)	 - hugo import from Jekyll

###### Auto generated by spf13/cobra on 25-Nov-2015
