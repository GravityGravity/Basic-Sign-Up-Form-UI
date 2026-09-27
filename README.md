# Library Sign Up Form Mock-up
For practice only!
A responsive sign-up form built with HTML and CSS.
 
## Features
 
- **Two-column layout:** Built with Flexbox. Each row splits into equal-width fields, and rows wrap on narrow screens.
- **Fluid typography:** Font sizes scale with the viewport through `clamp()` and CSS custom properties.
- **Live validation feedback:** `:user-valid` and `:user-invalid` show ✓ and ✗ icons on each field. The icons are drawn with `::after` on a wrapper `div` selected via `:has()`, and they are hidden while a field has focus.
- **Required fields:** Uses native HTML5 constraint validation, such as `required` and `type="email"`.
 
https://gravitygravity.github.io/Basic-Sign-Up-Form-UI/

### Reflection as a dev
This project took way longer than anticipated but thats how most projects go.  Took around a full day of work.

#### issues, Setbacks, and Time wasters:
- Compatibility with large media queries for XX-Large screen sizez (e.g. TVs).  often times OSs or TV applications will auto-scale the UI to standard monitor sizes.  Spent too much time on this before letting it go. uncessacary.
- Forcing center of background image to sit on the left border of the viewport.  Very difficult to do with a scaling screen sizes.  Decided on skipping this because could not find a good solution.  Maybe media queries will make it easier to handle
- fixing compatibility with standard screen sizes.  Developing in VScode with the live preview site taking up half the screen means developing with a screen basis of half the desktop screen size.  When going to full screen live preview the site elements were WAYYYY smaller pretty much unusable. Pro tho is that it helped with making my site compatible with smaller mobile screens 😜.
- Attempting to format my input boxes cleanly with the label ontop of the input.  This is due to trying to keep html lean as possible but has led to alot of time wasted.  Spent few hours trying to prevent wrapping my labels + input elements in a div.  Actually originally wrapped my inputs in my label element which was silly.  Ultimately did it anyways fixing my input box scaling issues.  Why I didnt do it sooner i dont even know...
- Scaling fonts is a pain in the ass!  Pardon my language 👮

#### Whatd I learn
- Font scaling, margin scaling
- Using different CSS measurement units like ch, rem, em, and px
- Reinforcing difficult flex concepts
- The importance of drafting a UI before implementation (WOULD OF MADE MY LIFE EASIER!)
- Styling using Psuedo elements for responsive feedback
- House MD is a good show

#### What could be improved for this project
- Add Regular expression validation to inputs
- Add invalid input messages to inform user
- Add better visual indicators to 'required' inputs
- Typography could be improved

I need to focus on laying out my containers before putting any content in them.  Repeatedly messed with layout components causing a cascade of necessary changes to ALL CONTENT of the site.
