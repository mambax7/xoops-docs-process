# Process Standards

1\) Please use the standard way of writing documentation using Markdown, and review the existing XOOPS Documents as examples

2\) Please consider making your documents Multi-lingual from the very beginning

3\) Please use following standards for Info/Tips:

> ![](https://github.com/xoops/xoops-documentation-process/tree/2184668a440f6665572a6217960e9650b439de70/es/assets/info/tips.gif) **TIP:** These images below do NOT have tool tip information.
>
> ![](https://github.com/xoops/xoops-documentation-process/tree/2184668a440f6665572a6217960e9650b439de70/es/assets/info/info.png) **NOTE:** These images below do NOT have tool tip information.
>
> ![](https://github.com/xoops/xoops-documentation-process/tree/2184668a440f6665572a6217960e9650b439de70/es/assets/info/important.png) **WARNING:** These images below do NOT have tool tip information.
>
> ![](https://github.com/xoops/xoops-documentation-process/tree/2184668a440f6665572a6217960e9650b439de70/es/assets/info/stop.png) **IMPORTANT:** These images below do NOT have tool tip information.

4\) When creating a XOOPS Tutorial in GitBook, please call it: **"XOOPS XYZ Module"**, replacing the "XYZ" with the name of the module, e.g. "XOOPS Protector Module"

5\) Directory structure

![](https://github.com/xoops/xoops-documentation-process/tree/2184668a440f6665572a6217960e9650b439de70/es/assets/directorystructure.jpg)

Above you can see the typical directory structure for a Gitbook document. Within the /book folder, you can have additional folders if needed \(e.g. for individual chapters\)

For Multi-lingual documents, the top structure will look like this:

![](https://github.com/xoops/xoops-documentation-process/tree/2184668a440f6665572a6217960e9650b439de70/es/assets/directorystructure_international.png)

with the LANGS.md file containing list of languages which you can activate or deactivate:

```text
* [English](en)
* [Deutsch](de)
* [Español](es)
* [Français](fr)

<!--
* [Português](pt-br)
* [Italiano](it)
* [العربية](ar)
* [azərbaycan dili](az)
* [беларуская мова](be)
* [català](ca)
* [čeština, český jazyk](cs)
* [Esperanto](eo)
* [suomi](fi)
* [हिन्दी, हिंदी](hi)
* [Magyar](hu)
* [Bahasa Indonesia](id)
* [日本語 (にほんご)](ja)
* [한국어, 조선어](ko)
* [македонски јазик](mk)
* [Nederlands](nl)
* [język polski](pl)
* [limba română](ro)
* [русский язык](ru)
* [српски језик](sr)
* [ไทย](th)
* [Türkçe](tr)
* [Tiếng Việt](vi)
* [漢語](zh-tw)
* [中文](zh)
-->
```

Please note that the active languages will then show up as selection for the user when they come to read the document.

5\) Please note that the structure for each Book is as follow:

* README.md is the file with Introduction
* SUMMARY.md is the Table of Contents, which is used on the left-hand side providing you with links to the content.

