# Rocaudio™ Web Apps

Three small, honest web apps by **Rocaudio™ Tech Company Europe**. Each is a single,
self-contained HTML file with zero dependencies, zero tracking, and zero servers —
everything runs (and stays) in the user's browser.

| App | What it is | File |
|---|---|---|
| **MindBaseline™** | Mental-health screening (PHQ-9, GAD-7, WHO-5, Mini-IPIP) + a 6-task cognitive battery (digit span, reaction time, Stroop, number series, mental math, rotating 60-word verbal deck). Straight results, standard bands, honest limits — and deliberately **no IQ number**, because no website can truthfully give one. | [`mindbaseline.html`](mindbaseline.html) |
| **Letters That Stay** | A quiet studio for writing an *ethical will* (legacy letter): eight guided prompt stations, autosave, assembled letter view with read-aloud, print, .txt and keepsake-.html export. | [`letters-that-stay.html`](letters-that-stay.html) |
| **The Listening Gym** | Practice reps for reflective listening: 12 written scenes, a local keyword coach that flags fix-it mode, silver-lining, story-hijack, interrogation and fast reassurance, model replies, and honest progress stats. | [`listening-gym.html`](listening-gym.html) |

`index.html` is a landing page that links and offers all three for download — it works
both when hosted and when opened straight from disk.

## Run them

No build step, no install. Either:

- open any `.html` file directly in a browser, or
- host this folder as static files (GitHub Pages, Netlify, Cloudflare Pages, any web server).

Data persistence uses `localStorage`, so results/drafts survive reloads in a normal
browser. (Inside sandboxed iframes storage may be memory-only; the apps detect this
and tell the user.)

## Why free

The clinical instruments inside MindBaseline are public-domain tools that exist so
*everyone* can be screened. Putting a paywall between a struggling person and a
screener would betray both the instruments and the point. There are no servers and no
running costs, so there is nothing to recover. Free, MIT-licensed, no ads, forever.

## Privacy

All three apps are 100% client-side. Nothing is uploaded, tracked, or sold — there is
no backend to send anything to. The only external links in the entire codebase are
crisis-helpline resources (findahelpline.com) shown for user safety.

## Disclaimers (please keep these if you fork)

- **MindBaseline is a screening and practice tool — not a medical device, not a
  diagnosis, and not an IQ test.** Only qualified professionals can diagnose. Scores
  are self-reported estimates from a single sitting.
- The Listening Gym is practice, not therapy.
- If anyone is in crisis: local emergency number, or
  [findahelpline.com](https://findahelpline.com) (130+ countries); US/CA **988**,
  UK/IE Samaritans **116 123**, AU Lifeline **13 11 14**, IN Tele-MANAS **14416**.

## Instrument credits

- **PHQ-9** — Kroenke, Spitzer & Williams (2001). Public domain.
- **GAD-7** — Spitzer, Kroenke, Williams & Löwe (2006). Public domain.
- **WHO-5 Well-Being Index** — © World Health Organization; free to use and reproduce.
- **Mini-IPIP** — Donnellan, Oswald, Baird & Lucas (2006), *Psychological Assessment* 18,
  192–203. Items public domain via the International Personality Item Pool
  ([ipip.ori.org](https://ipip.ori.org/MiniIPIPKey.htm)).
- Cognitive task implementations and the verbal word bank are original to this project.
  "Typical adult ranges" shown in results are informal guides, **not** clinical norms.

## License

Code: **MIT** — see [LICENSE](LICENSE). Use it, learn from it, fork it, ship it.

**Trademark note:** the MIT grant does *not* include the right to use the
**Rocaudio™** name or mark. If you fork, please rename your fork and remove the
branding.

---

Created by **Rocaudio™ Tech Company Europe**
