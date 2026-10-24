# Agent Firewall landing page

Static site for agentfirewall.app, hosted on Vercel. The Vercel project deploys from this repo's main branch, so every push to main updates production. Preview deployments sit behind Vercel's Standard Protection; the production domain is public.

- index.html: the landing page ($150 pilot front door, sample-audit proof).
- CNAME: left over from GitHub Pages hosting; Vercel ignores it. DNS for agentfirewall.app is at Namecheap and points to Vercel.
- robots.txt and sitemap.xml: crawler rules and the sitemap (add any new page to sitemap.xml).
- assets/og.png: 1200x630 share image used by the Open Graph and Twitter tags.

The break-in video section slots in once the video is published.

Credits:
- Font: Inter Tight (SIL Open Font License), self-hosted in assets/fonts.
- UI icons: Lucide (ISC).
- Platform logos in the "Any stack" section: Simple Icons (CC0) and LobeHub Icons (MIT). The logos are trademarks of their owners and are shown only to illustrate the platforms agents are built on; no affiliation or endorsement is implied.
