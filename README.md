# Mateusz Śliwa

Data and AI engineer who ships mobile apps. Zielona Góra, Poland, open to remote or hybrid roles and to relocation.
I build with coding agents (Claude Code, Codex, Cursor) and write tools they can drive.
Projects with live demos: [mateuszsliwa.dev](https://mateuszsliwa.dev).

**Open source**

- [wwxd](https://github.com/MSliwa01/wwxd) ("What would X do?"): turns one person's public talks, podcasts and essays
  into a wiki of their positions, so an agent can answer "what would X do?" with timestamped quotes. A script checks
  every quote against the transcript (158 of 160 found word for word), and a blind judge from Google preferred its
  answers to plain Claude on 34 of 40 questions. It can't predict opinions a person hasn't voiced yet.
- [storeshots](https://github.com/MSliwa01/storeshots): App Store screenshots from the running app. Captures in the iOS
  Simulator, lays out slides in HTML and CSS, checks them on the rendered pixels and uploads through the App Store
  Connect API. Every command prints JSON, so an agent can drive it.
- [macsim](https://github.com/MSliwa01/macsim): turns a Mac on the network into a remote iOS build server and iPhone
  Simulator for a Linux machine, so coding agents can build, run and test iOS apps from Linux.
- When a library I use has a bug, I send the fix upstream, for example
  [this one in React Navigation](https://github.com/react-navigation/react-navigation/pull/13287).

**Apps**

- [EcoSort](https://apps.apple.com/pl/app/ecosort/id6785674008), on the App Store in Poland: waste collection dates for
  your street. Its LLM pipeline reads scanned municipal schedules one month at a time. On six hard scans (2,190 cells)
  the best single prompt got 24.5% of cells wrong. Over three full runs the pipeline published 82.2% of the cell results
  with no wrong date and held the other 17.8% back. It was tuned on these documents, so that is its best case; documents
  it has not seen are the next test. The Android version is in testing on Google Play.
- TrueSky: weather drawn as a painted landscape, with a RevenueCat paywall. [On the App Store](https://apps.apple.com/pl/app/truesky-weather/id6816346955).
- Keenwit: a daily brain workout with 43 games, where the server checks every result. In development.

**Research**

- MSc thesis, University of Zielona Góra (defended 2026): win probability in Counter-Strike 2 from 16.8 million game
  states in 9,196 professional maps. Nine models compared; in quarterly walk-forward tests XGBoost reached ROC-AUC 0.81 to
  0.82.

Contact: sliwa.mateo@gmail.com
