---
date: 2020-02-27
title: Occurrence Selection
technologies: [.net]
products: [rider]
topics: [editing]
author: matkoch
subtitle: Poor manâs manipulation to the rescue!
thumbnail: ./thumbnail.png
cardThumbnail: ./card.png
animatedGif:
  file: './guide.gif'
  width: 500
leadin: |
    **Where we go, we donât need _Find & Replace_!** ð¹â¡ï¸

    Using actions for occurrence selection is a powerful way to transform and manipulate all kinds of texts. We start by making a selection for our text. With every call to `Add Selection for Next Occurrence` we get another multicaret that can be moved around, insert and delete text, expand or shrink its individual selection, or toggle the casing of its text. This is exactly what we need if we have to fix only a couple of similar invocations or change the format of our data! ð­ð

    Remember to always use meaningful names! ð·
    Invoking `Unselect Occurrence` removes the previously added selection; `Select All Occurrences` scans the whole document for occurrences and selects them.

    But remember: always give refactorings a try first! ð§ð¤

    ### See Also
    - https://www.jetbrains.com/help/rider/Multicursor.html
    - https://www.jetbrains.com/help/rider/Toggling_Case.html

---

