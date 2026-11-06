# Training & Recovery · chris.bike (parked)

Reserved for the installable training app at **<https://chris.bike/>**, which for now lives at
**<https://chrisrohn.github.io/>**.

Nothing here is edited by hand. `.github/workflows/deploy.yml` asks
[chrisrohn/chrisrohn](https://github.com/chrisrohn/chrisrohn) (`node fitness/build-app.mjs --role`) what this site
serves: *parked* (an empty, unindexed site with no `CNAME`) until `[app] url` in `fitness/config.toml` names
`https://chris.bike/`; then it builds the app here with its `CNAME`, and chrisrohn.github.io forwards to it once it
answers, bringing each phone's data along. See
[fitness/README.md → Moving the app to a domain of its own](https://github.com/chrisrohn/chrisrohn/blob/main/fitness/README.md#moving-the-app-to-a-domain-of-its-own-later).
