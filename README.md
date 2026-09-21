# CGDS v2 — push all files to repo root (CNAME: columbusgaragedoorservice.com)
This replaces the CGDS_2026-09-18 package, which was never pushed. Don't push the old one.
- HTML: phone-first meta descriptions (unchanged from the earlier package) and the sticky call bar markup.
- style.css: call bar styling at the compact 44px height, plus the header phone set so it never wraps.
Push the HTML and style.css together.
- The phone number now appears once, in the header, at every width. The copy in the top bar is removed from the HTML. On phones it sits beside the menu button, and the empty top bar is hidden.
- The logo shrinks on phones so the logo, number and menu button fit on one row. For this, the logo's inline style on every page no longer uses !important. Desktop size is unchanged at 56px.
