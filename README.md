# es-plantuml
Event storming PlantUML diagram template and VS Code snippets

## Warning - verison 0.0.1 

I found this github project when I was searching for a tool for learning event storming. The original author states >I started working on this event-storming plant uml template inspired by [C4-PlantUML](https://github.com/adrianvlupu/C4-PlantUML) but found it impractical to use due to layout limitations in PlantUML.  Event storming relies a great deal on being able to position elements relative to other elements. PlantUML supports this in theory, but in practice I found the layout results to be unpredicable. See [Known Issues] for more details.

She is mostly right. But I was able to make this work with some minor changes.

## Sample Diagrams

### Sample with Top Down Layout

Source: [samples/EventModel.puml](samples/EventModel.puml)

![Feature_Explorer_Event_Model](http://www.plantuml.com/plantuml/svg/VLPFKzou4xtxK_IF2pCKcIa89AdVAIomX2esK32xr9ue8VTuj94bhzI6pARotRTRjj7WAVR2-Bt-ttgo-Hn91MfhM_pFE6tR4c55rCJ_p-T1FSygGwlsiOqOj7U4ZcRQr_E_LFJk7z_ECRvhh78IFwzL90ppyxjP8-cANOjB0l8GJBKYi6hjMmAbgLNMhY4Yrb7CJV1bgn5g7n3y4XIJJR5R-cSt1Bs3HmcrqKEDCMA4jW5FAmn0A-Eg2DPyGt2U4BWVZJKwAdQlJlwy_dtnS7N-w-BXzlBYos8ovRRwf585KX4JWLD1YKlLMjg7w9bokmG1KwS1_svDmBBeyoskRnxEhk-_IhQUkhzSVE4w5-TVpuGbGnPXR-_y2Ht17VbGSvTmPbGLLBstLnI_-DQLM9xAKh_JXEkSgb0krWt6VTWviHO4Go9sfl2Zk8onnOdsJcDmuWAdtVFEjBXRHy9w4jDFidKCcr874vI_Od2G23QSL5N0IX5ErF3KERn0qDp1Zf034q45x8wX2hvjucmsurItgChVV8bs4eQdr8Jma20xdVgwLgwSwEutEVGSMs-yDNezQT9FidKCctuMHJhNHq_aQn78vhAAnQfh54WWUwMzWkuMAsTRciYQM3DfLMJ6HK9LIgAb2P5cnJY739c3Z0CVIWn9WiuJVCE6m3Fh4Anno0bERFIYnDX9a7zZspG-OYa2VqHGnERD6GIDUfqLw4g9BxRaaHeGOLpB0mlYHm5m8KVGcVf5nYc80Q37atGNKWp7tWY0XEHKMLMlVBLo6ktWV9hGflShvoTbJQde9VSVFHu5_7pTvekGXZwp234OhVA0RoH8udsPCg7Ea6OhXtZeO3_bsBSRpMwuzymGCGuOXii1Bqnk5AJEBTg7gz6i-_3wY7gtssstFA6eVYJwP4rox-_Ujam3Fh4Bzd9T-W3HryYqlAs1YqDHhuUtNwrqy2c9lEbMQ1lZgbxAcnLYetIIiOUb2g0Q5VvBgL7LZSKUyNBk4eQU4E4EgyK3Ddk7tGepVSYOdlr0PtsE_BFXpOZtObW5p35PSEgDyaUCbxuDO_vOUFEqvV-1SJJVn_H7eP6VnuPFZ54-YDljvj9ZIow-FSTe-bw3Cfu-c49FdANrwSDfnXodtsSrIW0UP3iAFjn8AFv7sLym7ctPSq4PHnzl1UG2RCVZZ6N3-25ZsIn-p5XMYf-s2exhRT-SLv8ixWsjG87r93PSBdqWk0Ij75H8eFjhkf-_Wt6_O0OmtSp-lvG05cE4vnK6vEXdvT8Blku_9d9fZAlIXu2CjU3Baks-hLRvxdpcXxQs_m80)

### Sample with Left Right Layout

Source: [samples/EventModelLeftRight.puml](samples/EventModelLeftRight.puml)

![Feature_Explorer_Event_Model](http://www.plantuml.com/plantuml/svg/VLPVKzos5tttfxW_Nl0oP7SWa6H-Jw502JCqCB0jqoT6o7TjDxBaIjUGRIRVlVVADbgyGr_MEkV-buxi_Hn8UUeQa_sljjfq1K95r8R_BnPUFS_BcghkiGlejRE4bkRQDOk_L73s7zSjCBnhZR8IlsXK8FIByxjvA-coNOCh0dBWwx8YC6hjEWAbgLF6h24WDa7ChNT5fn4Qvn7S2XIJRRPRk6Sx1hs3HmarmK638M20hWL75NgWghPb05D_Gx2E4BWVZGrQogvE_hp-VVbmTVxhyk7sykBBCfznLqDEAGAnHXs0Cq61AzKPseVWcBAx11vZenx_xcgF1OSE6PVNDmzdr_TV9Tz0tLyklt2bY_ElPy9IJGPXR-_y2It17JdVS9jmLglIgsPlByj-SPqji3YLNVrEELSwLRvOhbiC-x1pOWm8XaZipE17TXb2XxbsLgEtuWAd_Nfdbjsj0s6JX_Y8jfvXK-mWH_aLWuL8iE6aB3sMYZ1NuwftU86WkOCT8KScWFBOdqFfNTU6-NpEgMvH5R-v0atknvL4WV0G8JkTkgPHjiXr_umE0yVM6sTglSxR-8Ysdc7JpooB1_leY5mZ2jdSh6nPzOq22OJ7Vbz1znihfrlKWKMnPjAem8mDXAgGHAlQ1vfdqnpAOmfYVt2-G2yQ58d1Dsm97BCMmTGMES692Kwa67eDyZDqRUi2XvE3HmH5RDwOGT2qrtc6jf3uR4iUiG4HnhKiM10_Ce0BEOBUD6nac84O00QSnyiGOpZsHW149AVAgdhbgvNLQ4RdquWslLyvFobJ5ufUSlynu4d0pzTjlWXfx3E947sjLHhmZGHHl2zJHjGRucp560yz7AQS-lQZcGttaHaYfW7ZS2dWXKcDWjIvHVDmDPbr7ruVqU1sk-sM9XJLJqGVhL7kmztRbgd79tR1GQuhvo6u1fcMrpLmSSYQzVZ-QvJsBYQHTrs5fgrjEKXviq9ebOuoTh1I7bIh_7yfDQYcDJWWtfoxY64WHBZZrk81cvt5VWiJVSYOdjr89tqc_udXpOZtOgWyffWaEFL6-IF6AzVvANyiVFsqvV-1SQY_J-cFGYElfuPFZ56-YDljfj9JIog-FSTa-a63Cfu-cC50dELQYCDPmXodtoSrIW0U93iAFjn8AFv7oLym7ctPKq4PHnzl1QG2RCVZX6M7yKF2ihFuCM7PKloqLN1QR_lcl99aTbzJ1GgC8x7XQkKymILePQ540ZrSq_tq7Gpx6JE0yMOEVrCy60m1dYlqoD7FoiONV3DyJEJIo0TVFWHK6mEkADZkkh9AT-SpBxh6_0i0)


## Known Issues

### Layout is difficult 

Unfortunately, layout options in PlantUML is difficult.

In an ideal world, the layout engine would:
* default to displaying each card from left to right in the order that they are listed in the file
* if two of the same type of card are listed in a row, they should automatically stack vertically
* allow you to place cards in groups called bounded contexts
* allow you to place cards in groups called aggregates - which can be placed inside of bounded contexts, but not
inside of other aggregates
* allow you to connect individual cards in bounded contexts to cards in other bounded contexts
* allow you to connect individual cards in aggregates with cards in other aggregates
* allow you to connect aggregates to each other
* allow you to connect bounded contexts to each other
* when items are connected, the groups (bounded contexts and/or aggregates) containing those items can move relative to other groups, but the items within the groups should not move

This might be possible by creating a new layout engine for graphviz and offering that layout option in plantuml... or maybe creating a new mermaid diagram type?... but that's a lot more work than I was planning...


### No auto-wrap for box descriptions

PlantUML has an option called WrapWidth that I was hoping to use, but it doesn't apply to the description lines in the cards I've created. Under the hood, I'm using classes for cards. The wrapwidth option would work if I used rectangles instead, but then I'd lose some other important features that I get with classes but not with rectangles.

## Event Storming Language
### Domain Event (something changed) - Fact
### Command (from user) (Change something) - Intent
### Issue (Needs attention!)
### Actor (User Category)
### Read Model (Data used to make decision)
### External System (3rd party)
### Policy (<-Whenever Then->) Can be manual or automatic
### Aggregate (Entity with state) 
