# rj-landing

Script for the Rhythm Juice Bangkok landing page test at rjbkk.com/try-new.

- `rj-try-page.js` defines the custom element `<rj-try-page>` used by a Wix Custom Element (Server URL).
- Wix loads it from jsDelivr pinned to a tag, e.g. `https://cdn.jsdelivr.net/gh/SummerwithTM/rj-landing@v1/rj-try-page.js`.
- To change the page: edit the prototype, rebuild, commit, push a new tag (v2, v3...), then update the URL in the Wix editor.

Do not delete this repo while the Wix page points to it.
