# Mateusz Śliwa

I design, deploy and maintain Python backends, document-processing pipelines and mobile apps.
Python · FastAPI · PostgreSQL · React Native · TypeScript · Swift · Kotlin.

EcoSort and TrueSky are on the App Store. [Fixes merged into Docling, React Native Skia, React Navigation and T3 Code](#merged-contributions).

Based in Zielona Góra, Poland. MSc in Data Engineering. Open to remote or hybrid roles and relocation.

[Portfolio and project demos](https://mateuszsliwa.dev) · [Email](mailto:sliwa.mateo@gmail.com)

## Apps and data projects

- [EcoSort](https://mateuszsliwa.dev/ecosort): waste collection dates for your address, reminders and an assistant
  grounded in your local schedule. I built the document extraction pipeline, backend, admin panel and mobile apps.
  The pipeline reads municipal schedules and holds uncertain dates for review.
  [On the App Store](https://apps.apple.com/pl/app/ecosort/id6785674008); Android is in closed testing on Google Play.
  [Extraction evaluation and methods](https://mateuszsliwa.dev/ecosort-data).
- [TrueSky](https://apps.apple.com/pl/app/live-weather-rain-truesky/id6816346955): weather shown as an animated, painted
  landscape. Built with React Native and Skia, with subscriptions through RevenueCat. On the App Store.
- [Keenwit](https://mateuszsliwa.dev/keenwit): Wordle-style word, maths and logic puzzles with competition against
  other players and friends. React Native and Expo, with a Fastify and PostgreSQL backend that validates game
  sessions and results. In development.
- MSc thesis: a Python pipeline for collecting and processing Counter-Strike 2 match data, plus a win-probability
  model. Worked with 16.8 million game states from 9,196 professional maps and compared nine models. In quarterly
  walk-forward tests, XGBoost reached ROC-AUC 0.81 to 0.82. Defended in 2026.

## Open-source tools

- [storeshots](https://github.com/MSliwa01/storeshots): captures real app screens, composes App Store slides in
  HTML/CSS with device frames and app artwork, checks the rendered images and uploads through the App Store Connect
  API. Node.js CLI with JSON output.
- [macsim](https://github.com/MSliwa01/macsim): builds and tests iOS apps on a remote Mac from Linux or WSL.
  Syncs over SSH, builds Swift, XcodeGen and Expo/React Native projects, and provides Simulator controls and a browser
  stream. Written in Bash.
- [wwxd](https://github.com/MSliwa01/wwxd): builds a cited knowledge base from expert talks, podcasts and essays
  for use in model conversations. Its Python CLI handles source discovery, transcript fetching and quote checks;
  topic pages provide context for answers with source references.

## Merged contributions

- [T3 Code #18860](https://github.com/pingdotgg/t3code/pull/18860): fixed Linux primary-selection paste when closing
  a panel tab with the middle mouse button.
- [React Native Skia #4221](https://github.com/wcandillon/react-native-skia/pull/4221): shared WebGL contexts to
  prevent blank canvases after the browser's context limit was reached. Released in 3.4.3.
- [Docling #4802](https://github.com/docling-project/docling/pull/4802): fixed characters from adjacent PDF lines
  leaking into extracted text cells.
- [React Navigation #13287](https://github.com/react-navigation/react-navigation/pull/13287): fixed keyboard
  dismissal when opening a drawer programmatically.
