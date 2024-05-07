# choco pack

> ஒரு `NuGet` விவரக்குறிப்பை `nupkg` கோப்பில் தொகுக்கவும்.
> மேலும் விவரத்திற்கு: <https://chocolatey.org/docs/commands-pack>.

- ஒரு `nupkg` கோப்பில் ஒரு `NuGet` விவரக்குறிப்பைத் தொகுக்கவும்:

`choco pack {{விவரக்குறிப்பு\பாதை}}`

- இதன் விளைவாக வரும் கோப்பின் பதிப்பைக் குறிப்பிடும் ஒரு `NuGet` விவரக்குறிப்பைத் தொகுக்கவும்:

`choco pack {{விவரக்குறிப்பு\பாதை}} --version {{version}}`

- ஒரு குறிப்பிட்ட கோப்பகத்திற்கு ஒரு `NuGet` விவரக்குறிப்பை தொகுக்கவும்:

`choco pack {{விவரக்குறிப்பு\பாதை}} --output-directory {{வெளியீடு_கோப்பகம்\பாதை}}`