# es-plantuml
Event storming PlantUML diagram template and VS Code snippets

## Warning - verison 0.0.1 

I found this github project when I was searching for a tool for learning event storming. The original author states >I started working on this event-storming plant uml template inspired by [C4-PlantUML](https://github.com/adrianvlupu/C4-PlantUML) but found it impractical to use due to layout limitations in PlantUML.  Event storming relies a great deal on being able to position elements relative to other elements. PlantUML supports this in theory, but in practice I found the layout results to be unpredicable. See [Known Issues] for more details.

She is mostly right. But I was able to make this work with some minor changes.

## Sample Diagrams

### Sample with Top Down Layout

Source: [samples/EventModel.puml](samples/EventModel.puml)

![Feature_Explorer_Event_Model](https://www.plantuml.com/plantuml/png/0/hLdfK-Eu4l_klw8dErK35B0GZZagazgGWw4saAaGbffw-oebR2LnOLjUIHacRtV-zzUIx5W-GhA1V818wkFNxRxa_2OauN8U1j2ZHCuv7NT_n07Zb8-xtsaanzVCeu7p3lGARYNZeHzD7TnfCwGJ-EMNjH_7UJCDs0C9u6rhE1pSZtk3cz6uFUWFXl0PQh_Kpq_g9nzg5jd5uEwcqnf-MqLP9hmO33lTuRD2-ztBxasdABAdFxKIsUXgrEyMYO_qfqnyqMh_VZbKM39YoKaaOiBHSNdJya1pP0K_FMTDUt3JxWvlrffp--rsrBrUIzRzeui4wwXQbvV3xcLhjDunmswhCxuUTBhzjKBRW-lhrWOFvkkWVzN-jegix9cBIukispixEJig-oL7r3iwht-ibxoIf-bz_92pDFD9WQvxSN9HxP4SuMcxrSiXI_sHepewQNtidPQzaICwVt_IkdYFli2ql9MBGANgPWagMGoImGEJaeNW-PowqcUHC_Cz2gxFtO22MOGqVA2O-7eX9EMKoKLC7KSy-X76CGdXse_Q0H7YtlVa38wFZgmpCICUUq9WC261eDP9XAL6q1ZfhKrCZiVIfaSdP1x84VqXMu4_ZK9LcrpyGxaDuucJs42e8mHqX52vDgN10WILKc6GCme1dTB8WmbJGbHHKuvuclcI0Y9ao8U5CHAQze5n3urFZW_KVtS6ljeW4gxWYKJoyF3G0j7NqdieN1VCYYfK8hxGIX9okroKAOdxEELi7dbvuSLoP36k5cuHkUhfmTyEuETs-OYL4RV-_oWSrvsVDdcBS_QKa2UIhVgbjoq755l0yhnIjWf4V6W1RJIKfN6pcIZA95eLL9_O9jfdg-G-A0SIlgWGNTM8IZggcv15fbAHWaV4Z7fv5DhHZORB8fVog0f0kSnNwI-gBSP5iIHMeX0BJEUm2aIfXso3eL1mAo5GDMPK8IYsfsq0v8jvfNuodN8w9P9MOQXgVjlWA3UCIYoS4YzKurSLbihskWsOYgwq8aJ3a4HUTOWM-_Ts8PhlUfKeOXRuRcMYbeQ3RJ0KUgg2WEM_JnPiBZUTT2VpIBTEwBU-3Uv6u_khqPUngSixkwMkcJIVfEzoVpgJpZyDtOO-hPf4ctjxflplxJL-rQHD-0UvIbdUX5HIkOeqavgJbr38qKn0gG8qJRN8i-SpBECkPczJvtcUjvmL6NzLvZMNkPgNKn7GcQ3Aj6cgJ0ETQaL_vaFIzcSnv9j9WkGb508g4r0ArwO9ROiT7x293kSD_ad3gYB2HeEluyxW_WR3QzKOjqP2lziRZOTNbrz6Exk0CJcHIegEnfL2tc5owRxfqurlWVFehpcJ58Uj582MGJ7_S7Zx8NVUai0dOX_U1kI11hlEiaj3xVDdi_bdr10uA7mwhZVpp8rVrNwp1hcE3aI0aGeb0oxLGF42y9e_mPp3gWyKa7HaoK106KOte6g2VG6GjidbWllmFqxKBlzSg-qwPgIplFXdb1pNB7JsA58CchBQMrq2NaFhSlHOhrI_YNWDdUciiLvbAwqqhw7M7Z7MgnvYQTBlO5wk6l8ZnNhTRLFHLcl6hyILp81uuqzWnwpX3Lv6QrX9DWBMIAH04-mn0_7X_H3-HU0cdDemVxBUlg-wuhx6CrsE9QNS7jA0gEzYviVRvtTVQH_l61IMj_KwyRRpAR5WO_k7MgQsuNW_CQPk-o6j_5fZGcXjfonvUBiRATvvE-4iH2MIfHgr5eEfTBOFjOE3fWgfZQnIWzs_rz0uEAXjXdvyGx4tFZ2-XHdDJNKe8rwWgB6nCPqjhF3OKrGsPPK297ur7QkKt6sXOHvlRCDT_4hoLodeRo5VJMeRMz17ubVJiKh9S0iDUixSs8oXeduzBSlx7NoXGKovU4cLNkHo2Mkc-Wu7_y5RdqUZ_te7QdkjbKhEtNDovflB6JudXsykf_-SdA12ZlCkVuq8Z9Enqyz9eD_0qb2euvWpR-vIl7zn2cm213UnLQhaJvaEu46n1e91I8MW0kOnC3cZ7EJCZwO20l-HGeIm8Gw8gyTfvrt5vKOzxaIekYff9RvvjPkyLDu7rEABw9q4d9OKKax_ccFByvpoTSkflECxqfTu2zZRo_ze1XsVJ3a9z_OSft3jGJrjmhtH8gOuYDHQGG1g3Ne3kzxVJZhX9-Ev8agdVepeP10tKxG-CpjuPCPbFUkgWsH-neDig5rEf8PWkGGNCTJKPheZW73pLXpqpKOS7Xxgh4k7L9v-qo3KFkWb4gNJP3Ad9HRextYQp69caD9dPWUFVZgEVhB9fLQ5YEKkPpGpG46zJn7mO3mBhd6jUhgUBp0g5hY9unpkHEWQ18Q29ZuNyj0fob16Pan-1FejaWv2H0AFD9Q0US4YYe4NKHJGKYx1M1Gc2F6_cCSn4yYkhkFeCvdyVf3QO5Ovh8Vgog_udLA0c9yTq2y3_QMsgzv_cUjdyePBErBiBj_26sVhRD0yoFjLBK2lr5DLqvHDwn8Cfo0bRkkLJPqZ_ewZduSHaPB_aQmB33_pC9U1bEBCWf1otoMPWIi4wE1TMcbYMnzesxoK7ypIjjAYDQO55lbonxBKOaYDonYMEnbGK7fCgSpRkW_vHvIG3Ql94WinwWj1Rq90Xwh9lNAOSanpZdSc4wuJl5895b9LnmI6Aoe79roazIyaBcTQYAfrCsn-MAFIKBOqY5Yv4iEOmOHm837XpqMg864Sq6I5phdLQqWsJE0cDGal7JNCeQKBassyWjJa4rjkB-EpIByyMCbneWvcd6OyLjLReVuKrnCsvyNzCxNlVo_Hd-DQ-3-As-_LjYgxnOCFk5P3lIp3BQbUdfIKMtOKhJSngCnpZtVJeEnezxdrtMoDVEv95esAWHvdv-hnqBebKD6VMlIufgUbSqiXckEUhMBeQ4_JCskDHj9pQusUfU-jDRgKVbW5ADDNofnSI3htlfpXa15W8SSpEi4qKR_SOlM3ALM_09iqtS_weDXtLExe7YgIEOL3W9C8FE4CGfFVVLL93vDcef96jNpL2AIFxPnvc48pDf_EhDpv3R_Dm-3_ "Feature_Explorer_Event_Model")

### Sample with Left Right Layout

Source: [samples/EventModelLeftRight.puml](samples/EventModelLeftRight.puml)

![Feature_Explorer_Event_Model](https://www.plantuml.com/plantuml/png/0/hLdfK-Eu4l_klw8dErK35B0GZZagazgGWw4saAaGbffw-oebR2LnOLjUIHacRtV-zzUIx5W-GhA1V818wkFNxRxa_2OauN8U1j2ZHCuv7NT_n07Zb8-xtsaanzVCeu7p3lGARYNZeHzD7TnfCwGJ-EMNjH_7UJCDs0C9u6rhE1pSZtk3cz6uFUWFXl0PQh_Kpq_g9nzg5jd5uEwcqnf-MqLP9hmO33lTuRD2-ztBxasdABAdFxKIsUXgrEyMYO_qfqnyqMh_VZbKM39YoKaaOiBHSNdJya1pP0K_FMTDUt3JxWvlrffp--rsrBrUIzRzeui4wwXQbvV3xcLhjDunmswhCxuUTBhzjKBRW-lhrWOFvkkWVzN-jegix9cBIukispixEJig-oL7r3iwht-ibxoIf-bz_92pDFD9WQvxSN9HxP4SuMcxrSiXI_sHepewQNtidPQzaICwVt_IkdYFli2ql9MBGANgPWagMGoImGEJaeNW-PowqcUHC_Cz2gxFtO22MOGqVA2O-7eX9EMKoKLC7KSy-X76CGdXse_Q0H7YtlVa38wFZgmpCICUUq9WC261eDP9XAL6q1ZfhKrCZiVIfaSdP1x84VqXMu4_ZK9LcrpyGxaDuucJs42e8mHqX52vDgN10WILKc6GCme1dTB8WmbJGbHHKuvuclcI0Y9ao8U5CHAQze5n3urFZW_KVtS6ljeW4gxWYKJoyF3G0j7NqdieN1VCYYfK8hxGIX9okroKAOdxEELi7dbvuSLoP36k5cuHkUhfmTyEuETs-OYL4RV-_oWSrvsVDdcBS_QKa2UIhVgbjoq755l0yhnIjWf4V6W1RJIKfN6pcIZA95eLL9_O9jfdg-G-A0SIlgWGNTM8IZggcv15fbAHWaV4Z7fv5DhHZORB8fVog0f0kSnNwI-gBSP5iIHMeX0BJEUm2aIfXso3eL1mAo5GDMPK8IYsfsq0v8jvfNuodN8w9P9MOQXgVjlWA3UCIYoS4YzKurSLbihskWsOYgwq8aJ3a4HUTOWM-_Ts8PhlUfKeOXRuRcMYbeQ3RJ0KUgg2WEM_JnPiBZUTT2VpIBTEwBU-3Uv6u_khqPUngSixkwMkcJIVfEzoVpgJpZyDtOO-hPf4ctjxflplxJL-rQHD-0UvIbdUX5HIkOeqavgJbr38qKn0gG8qJRN8i-SpBECkPczJvtcUjvmL6NzLvZMNkPgNKn7GcQ3Aj6cgJ0ETQaL_vaFIzcSnv9j9WkGb508g4r0ArwO9ROiT7x293kSD_ad3gYB2HeEluyxW_WR3QzKOjqP2lziRZOTNbrz6Exk0CJcHIegEnfL2tc5owRxfqurlWVFehpcJ58Uj582MGJ7_S7Zx8NVUai0dOX_U1kI11hlEiaj3xVDdi_bdr10uA7mwhZVpp8rVrNwp1hcE3aI0aGeb0oxLGF42y9e_mPp3gWyKa7HaoK106KOte6g2VG6GjidbWllmFqxKBlzSg-qwPgIplFXdb1pNB7JsA58CchBQMrq2NaFhSlHOhrI_YNWDdUciiLvbAwqqhw7M7Z7MgnvYQTBlO5wk6l8ZnNhTRLFHLcl6hyILp81uuqzWnwpX3Lv6QrX9DWBMIAH04-mn0_7X_H3-HU0cdDemVxBUlg-wuhx6CrsE9QNS7jA0gEzYviVRvtTVQH_l61IMj_KwyRRpAR5WO_k7MgQsuNW_CQPk-o6j_5fZGcXjfonvUBiRATvvE-4iH2MIfHgr5eEfTBOFjOE3fWgfZQnIWzs_rz0uEAXjXdvyGx4tFZ2-XHdDJNKe8rwWgB6nCPqjhF3OKrGsPPK297ur7QkKt6sXOHvlRCDT_4hoLodeRo5VJMeRMz17ubVJiKh9S0iDUixSs8oXeduzBSlx7NoXGKovU4cLNkHo2Mkc-Wu7_y5RdqUZ_te7QdkjbKhEtNDovflB6JudXsykf_-SdA12ZlCkVuq8Z9Enqyz9eD_0qb2euvWpR-vIl7zn2cm213UnLQhaJvaEu46n1e91I8MW0kOnC3cZ7EJCZwO20l-HGeIm8Gw8gyTff-9kevvs8bFTbBGEtxpPJTufxmCgyKNqJW8EImeeft_DiUDvAb1AzosdyfBlI5_YDM1lB_-h6NHyCkKatDjpdCAz1pMr2VT6YvZY959h1G6eDUWDR7j_E-c8dypdYYWT-p6aaqdSZD7wpEpWaPcNzR2h3f816W-ogNOvaXg2vH9Sn51Jc-cE0CBDQt7GLnjnU7YeqowTKddwJODG-w2NI9IEaycWbbYWl-DfCeoPIKgVcHqy-kau-j4cjreL8vQxdD7C00NrGaN0W_4ikCQrwlbwli2mME0cpdEu4w5h41WAclXSo4EdA4CPcJ7v4UZNI3eA4GayqbW29WQBA4PUH550Ixa4Wr6OACJ_OXx7J22xke-ZpsJo0q9gWrdbi1wgEx_YTqe1OdvtGByCz9VQhde1PkwVoIikxKYnktmDRvojqq7p8EzNjG2zKazLZLCshKimd8AKkArNDdME-3lEVXv6H4h-Hx8kCFpCmrm6Keep2qBAVPTa1guGe8DtQQM9RNsWRVDIVZ1BsqgBrfWMMEJB7SjIYo4rBcDOxcH0GUanjJ9lwpxa7r52DgmcIop4g2y4lGa17QeczyfXoZ7DELwQJBXEy4ubM4XL9HCOhgWSd72HLi2Gk9nf8QhQpR3xOOrAGzdI86BbIWnZ1XF2WSI4FnUfWeHnG9CLEkTMho7PC86Rr2IyTTGmXvOkJBRn3bAJJsovlOpF8ltoO2N7YJgOSPhnM5LlXVfJN4_Od1VtpzI-_xr4VuvhuVyeRhzNswhi5Wy-u5fDzR8CjwHwUL9IRjbHjDx4e3BFFTvDWxAZtUVMTxCryhadMJGg1dgSdQl7G-kMG4L_Qj7ZcfwMpYs5Q8vxjegXeprDpwmr6adFhJLwbhwtrkXI-c4Le4nVANDo8UdS-tA6KqQ0XHpFw0JJHFrqYzKFfbJz16pIT3_hWsBVKRcZUwX81XKE0OuYy8H324r--5KbFKoQYKeQrV9L8v0-jdFcOGhDs7mwitBdD_ms3uF_0m00 "Feature_Explorer_Event_Model")

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
