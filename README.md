# jasonkhaings.com

Personal portfolio site for Swan Yae Htet, who goes by Jason. Four pages: an
index, two project case studies, and a 404.

Plain HTML and CSS with one inline SVG. No JavaScript, no analytics, no
cookies, no trackers. The only external request is the IBM Plex webfont
stylesheet from Google Fonts.

No build step, no CI, deployed from branch via GitHub Pages.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | Landing page: intro, work, how I work, contact |
| `phasedraft.html` | Case study: Phasedraft (vib-agent) |
| `khaings.html` | Case study: Khaings International PdM pilot |
| `404.html` | Not-found page |
| `style.css` | The whole stylesheet |
| `resume.pdf` | Resume, linked from the header and the contact section |
| `CNAME` | Custom domain for GitHub Pages |

## Local preview

```
python3 -m http.server 8080
```

Then open http://localhost:8080
