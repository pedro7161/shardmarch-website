# shardmarch-website

Static marketing site and privacy policy for **SHARDMARCH: Match 3 Heroes**
(`com.pedro7161.shardmarch`).

Plain HTML with no build step, deployed to GitHub Pages from `main` by
`.github/workflows/`. Same shape as `portal-siege-website`.

| Page | Purpose |
|---|---|
| `index.html` | Landing page |
| `privacy-policy.html` | **Required by Google Play**, because the game serves ads |

The privacy policy URL goes in the Play Console store listing. Play rejects a
listing whose policy link is dead, so this repo must stay published.

## Keeping the policy honest

The policy describes what the app actually does. If the app's data handling
changes, update this page in the same pass:

- The game has no accounts, no analytics and no in-app purchases
- Google AdMob is the only third party that receives anything
- There is currently **no in-game control for changing ad consent**, and the
  policy says so plainly. When that ships, update the "Your Consent Choice"
  section and the date at the top.
