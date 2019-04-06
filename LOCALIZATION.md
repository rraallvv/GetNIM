All the text files that needed for localization are in this repository in the folder localizations.

If you are familiar with GitHub and Android development and want to contribute with translating to your native language, just clone this repository, and duplicate each file in the folders inside `localizations` that has the name `en.xml`, and rename them changing `en` to the two-letters code for your language.

For instance duplicate `localizations/api/en.xml` and rename the new file as `localizations/api/eo.xml` for Esperanto, then start translating the text in each `string` tag like so:

Change the text in each string like the one shown below

```
    <string name="response_1019">Rewarded !</string>
```

To it’s corresponding translation

```
    <string name="response_1019">Rekompensita !</string>
```

Please take into account that the tags containing text that includes special sequences of characters like `%d`, `%s`, etc. used in string interpolations, need to keep those in the right places in the translated text.

For more details about context or the use of string interpolated text some files have anotations included in comments like

```
<!-- this is a comment -->`
```

The list of all contributors in the localization process will be included in the app itself :hugs:
