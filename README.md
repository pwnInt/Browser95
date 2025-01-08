# Browser95
A Windows 95 themed 404 page.

# MODIFIED :
- js CDN addr
- Start text position
- W95 themed font
- Search engine link changed to bing

If you want to use w95 font, put font files at ./static/font/

should be like this:

--------404.html
               |
               |_______static----font-----W95FA.otf
                                                 |
                                                 |__w95fa.woff
                                                 |
                                                 |__w95fa.woff2

## Features
### Error Window
- starts with **one** window on random screen position
- windows are **freely draggable**
- click on `OK` or `X` **spawns another window** at a *random location*
- `?`-Button is a **dummy** link to `bing.com`, may be replaced with anything

### Desktop
- `My Computer` opens a dummy upload dialog (will accept but not process any file)
- `Recycle Bin` reloads and thereby clears the desktop back to one error window
- `Printers` offers a PDF file of the page (*so you can share your **Errror-Window-Count-Highscore** to all your friends*)
- `Start` is a **dummy** linkt to `bing.com` &rarr; may be a redirect to the main page
- `Clock` displays the actual time
- W95 font for real

## Demo
![](https://user-images.githubusercontent.com/57369924/218161483-fd97a374-8568-4d46-9676-024dcfc304c7.gif)
