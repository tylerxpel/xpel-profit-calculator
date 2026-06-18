XPEL Dealership Profit Calculator — GitHub Pages package

Upload both files to the root of the GitHub repository:

1. index.html
2. embed.js

Enable GitHub Pages from the main branch and root folder.

Paste this into HubSpot's Rich Text embed-code field:

<div class="xpel-calculator" data-calc-id="xpel-dealership-profit" data-type="framed">&nbsp;</div>
<script src="https://tylerxpel.github.io/xpel-profit-calculator/embed.js" async></script>

This is a direct JavaScript embed, not an iframe. The calculator becomes part of the HubSpot page's normal document flow, so there is no separate internal scrollbar.
