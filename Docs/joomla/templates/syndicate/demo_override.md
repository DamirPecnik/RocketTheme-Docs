---
title: Syndicate: Recreating the Demo - Template Settings
description: Your Guide to Recreating Elements of the Syndicate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/syndicate:Syndicate

---

Template Settings
-----
One of the most important aspects of any Gantry template is its ability to be easily customized using the settings present in the Template Settings page. These settings can be adjusted by navigating to **Administration -> Template Manager -> Syndicate Template**. To replicate the demo, the main changes being made will happen within the Style, Features, Layouts, and Advanced tabs. 

![][Syndicate2]

:   1. **Logo** [6%, 15%, se]
    2. **Menu** [6%, 28%, se]
    3. **Branding** [92%, 45%, se]
    4. **Gantry To Top** [91%, 82%, se]

This table will break down the various settings you may need to adjust in order to recreate the demo. Most of the settings under **Style** are adjusted automatically with the selection of a template preset. You can set presets using the **Presets** button located next to the **Save** option at the top of the Template Settings page.

Once you have selected a Preset, these options can be further adjusted to match the demo.

>> Note: In the interest of simplicity, the override settings listed below are presented as they appear on our demo site.

### Style

![][styles]

|  Style  |       Option       | Position |                  Setting                   |
| :------ | :----------------- | :------- | :----------------------------------------- |
| Default | Body Level         |          | High                                       |
| Default | Read More Style    |          | Button                                     |
| Default | Article Style      |          | `title7`                                   |
| Default | Article Info Style |          | Layout 2                                   |
| Default | Header Width       |          | Full                                       |
| Default | Footer Width       |          | Full                                       |
| Default | Font Settings      |          | Font Family: Syndicate, Font Size: Default |

### Features

![][features]

|  Style  |      Option      |  Position |                                         Setting                                         |
| :------ | :--------------- | :-------- | :-------------------------------------------------------------------------------------- |
| Default | Logo             | logo      | Show: On, Auto Size: On                                                                 |
| Default | Date             | top-a     | Show: Off                                                                               |
| Default | Font-Sizer       | footer-a  | Show: Off                                                                               |
| Default | Login Panel      | utility-a | Show: Off, Login Button Text: `Member Login`, Logout Button Text: `Logout`              |
| Default | Feature Panel    |           | Enable: On, Delay: 250, Default: Open                                                   |
| Default | Lower Panel      |           | Enable: On, Delay: 250, Default: Open                                                   |
| Default | Popup Panel      | utility-a | Show: Off, Popup Button Text: `Popup Module`                                            |
| Default | Branding         | copyright | Show: On                                                                                |
| Default | Copyright        | footer-b  | Show: Off, Text: `Designed by RocketTheme`                                              |
| Default | SmartLoad        |           | Show: On, Component Ignores: `com_community,com_contact,com_k2,com_tienda,com_weblinks` |
| Default | More Articles    |           | Enable: On, Text: Load More Articles, Hide Pagination: On                               |
| Default | To-Top Scroller  | copyright | Show: On, Text: `Scroll to Top`                                                         |
| Default | System Messages  | drawer    | Show: On                                                                                |
| Default | Reset Settings   | footer-b  | Show: Off, Text: `Reset Settings`                                                       |
| Default | IE6 Warning      |           | Show: On, Delay: 2000                                                                   |
| Default | Google Analytics |           | Enable: Off                                                                             |


### Menu

![][menu]

|  Style  |          Option         |          Setting           |
| :------ | :---------------------- | :------------------------- |
| Default | Menu Control            | Show: On, Type: Split-Menu |
| Default | Enable ID               | Off                        |
| Default | Select a Menu           | Main Menu                  |
| Default | Module Cache            | On                         |
| Default | Main Menu Position      | navigation                 |
| Default | Sub Menu Position       | subnavigation              |
| Default | Side Menu Position      | sidebar-a                  |
| Default | Side Menu Module Suffix |                            |

### Layouts

![][layouts]

|  Style  |        Option        |        Setting        |
| :------ | :------------------- | :-------------------- |
| Default | Top Positions        | Positions: 4, 3:3:3:3 |
| Default | Header Positions     | Positions: 4, 3:3:3:3 |
| Default | Showcase Positions   | Positions: 3, 5:6:5   |
| Default | Feature Positions    | Positions: 4, 3:3:3:3 |
| Default | Utility Positions    | Positions: 4, 3:3:3:3 |
| Default | MainTop Positions    | Positions: 3, 5:6:5   |
| Default | MainBody Positions   | Positions: 2, 12:4    |
| Default | MainBottom Positions | Positions: 3, 5:6:5   |
| Default | Bottom Positions     | Positions: 3, 8:4:4   |
| Default | Lower Ad Positions   | Positions: 4, 3:3:3:3 |
| Default | Footer Positions     | Positions: 3, 4:4:8   |

### Mobile

![][mobile]

|  Style  |        Option        |      Position     |                   Setting                    |
| :------ | :------------------- | :---------------- | :------------------------------------------- |
| Default | iPhone Custom Theme  |                   | On                                           |
| Default | Scalable Content     |                   | Off                                          |
| Default | Standard View Switch | mobile-copyright  | Enable: On                                   |
| Default | Mobile Menu          |                   | Menu: Main Menu, Menu Animation: Slide       |
| Default | Image Resize         |                   | Enabled: On, Min-Width: 80, % of Resize: 25% |
| Default | Positions Aliases    | mobile-drawer     | drawer                                       |
| Default | Positions Aliases    | mobile-top        | top-a                                        |
| Default | Positions Aliases    | mobile-header     | header-b                                     |
| Default | Positions Aliases    | mobile-navigation | mobile-navigation                            |
| Default | Positions Aliases    | mobile-showcase   | header-a                                     |
| Default | Positions Aliases    | mobile-footer     | footer-a                                     |
| Default | Positions Aliases    | mobile-copyright  | copyright                                    |

### Advanced

![][advanced]

|  Style  |        Option       |                                        Setting                                        |
| :------ | :------------------ | :------------------------------------------------------------------------------------ |
| Default | Gantry Cache        | Enabled: On, Cache Timeout: 900                                                       |
| Default | Input Styling       | Enabled: On, Exclusions: `'.content_vote','#rt-popup','#rt-popuplogin','#vmMainPage'` |
| Default | Display Component   | On                                                                                    |
| Default | Display Mainbody    | On                                                                                    |
| Default | RT Typography       | On                                                                                    |
| Default | RT Extensions       | On                                                                                    |
| Default | RTL Support         | On                                                                                    |
| Default | Build Titles Spans  | On                                                                                    |
| Default | Page Suffix         | On                                                                                    |
| Default | Third Party Styling | Off                                                                                   |
| Default | IE6 Redirect        | On                                                                                    |

[demo25]: assets/Syndicate.jpg
[menu]: ../../start/menu.md
[Style]: http://docs.gantry.org/gantry4/configure
[Syndicate2]: assets/syndicate2.jpeg
[styles]: assets/style.jpeg
[features]: assets/features.jpeg
[menu]: assets/menu.jpeg
[layouts]: assets/layouts.jpeg
[mobile]: assets/mobile.jpeg
[advanced]: assets/advanced.jpg
