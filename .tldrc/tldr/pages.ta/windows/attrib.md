# attrib

> கோப்புகள் அல்லது கோப்பகங்களின் பண்புக்கூறுகளைக் காட்டவும் அல்லது மாற்றவும்.
> மேலும் விவரத்திற்கு: <https://learn.microsoft.com/windows-server/administration/windows-commands/attrib>.

- தற்போதைய கோப்பகத்தில் கோப்புகளின் அனைத்து தொகுப்பு பண்புகளையும் காண்பி:

`attrib`

- ஒரு குறிப்பிட்ட கோப்பகத்தில் கோப்புகளின் அனைத்து செட் பண்புக்கூறுகளையும் காண்பி:

`attrib {{அடைவிற்குப்\பாதை}}`

- தற்போதைய கோப்பகத்தில் கோப்புகள் மற்றும் [d]அடைவுகளின் அனைத்து தொகுப்பு பண்புகளையும் காண்பி:

`attrib /d`

- தற்போதைய கோப்பகம் மற்றும் [கள்]உப்-கோப்பகங்களில் கோப்புகளின் அனைத்து செட் பண்புக்கூறுகளையும் காண்பி:

`attrib /s`

- கோப்புகள் அல்லது கோப்பகங்களில் `[r]ead-only` அல்லது `[a]rchive` அல்லது `[s]ystem` அல்லது `[h]idden` அல்லது `not content [i]nexed` பண்புக்கூறைச் சேர்க்கவும்:

`attrib +{{r|a|s|h|i}} {{கோப்பு_அல்லது_அடைவு1\பாதை கோப்பு_அல்லது_அடைவு2\பாதை ...}}`

- கோப்புகள் அல்லது கோப்பகங்களின் குறிப்பிட்ட பண்புகளை அகற்றவும்:

`attrib -{{r|a|s|h|i}} {{கோப்பு_அல்லது_அடைவு1\பாதை கோப்பு_அல்லது_அடைவு2\பாதை ...}}`