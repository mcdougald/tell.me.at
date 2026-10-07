<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/hero-dark.png">
    <img src=".github/assets/hero.png" alt="tell.me.at landing page" width="880">
  </picture>
</p>

# tell.me.at

Post an idea once. Watch it move from board to roadmap to changelog.

tell.me.at is a feedback board, a public roadmap and a changelog in one place. Someone posts an idea to the board; the same post becomes a card in a roadmap column, and when it ships, the changelog entry links back to it, so there is no second copy to keep in sync. Visitors read, vote and post without an account, and the team keeps the moderation controls. Tell runs its own feedback on a Tell board.

## Features

- **Public boards**: read, vote, post and comment without making an account. Owners can require sign-in for posting while reading and voting stay open.
- **Roadmap view**: the same posts grouped into status columns, which team members can move along.
- **Changelog with RSS**: shipped work is published with stable URLs and an RSS feed, each entry linked to the posts that asked for it.
- **Follow and merge**: follow a post to hear when it changes; merging duplicates moves votes without double counting, and old links keep working.
- **Moderation queue**: a members-only queue for reports, plus pinning, renaming and anonymous-abuse velocity limits.
- **Embeddable widget**: separately licensed, and it renders server-sanitized HTML, never raw user input.
- **Integrations and webhooks**: board events can be forwarded to Slack, Linear and Jira, or delivered as webhooks through hook.me.at.

## Screenshots

<table>
  <tr>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/changelog-dark.png"><img src=".github/assets/changelog.png" alt="Changelog"></picture><br><sub>Changelog: release notes and shipped changes, with an RSS feed</sub></td>
  </tr>
</table>

## Built with

- Next.js 16 (App Router), React 19, TypeScript
- Tailwind CSS 4
- Drizzle ORM + Postgres
- Better Auth, with optional organisation SSO over OIDC
- Pro plan checkout through pay.me.at

## Part of the me.at family

tell.me.at is one of my [`*.me.at`](https://me.at) apps. They share one design system, account, and app shell. Development happens in a private monorepo; this repository is the project's public-facing home.

## License

See [LICENSE](LICENSE).
