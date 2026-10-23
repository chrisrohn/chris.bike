# Training & Recovery

The installable training app and cycling computer, served at **<https://chris.bike/>**.

It lives at its own address, apart from the music app at chrisrohn.com, so Android installs it as an app of its own.
Nothing here is edited by hand: `.github/workflows/deploy.yml` builds it from
[chrisrohn/chrisrohn](https://github.com/chrisrohn/chrisrohn) (`fitness/`, `node fitness/build-app.mjs --as app`) every
hour when that changes, and on demand (*Actions → Deploy the Training app → Run workflow*), and commits it here with
its `CNAME`. It holds no one's data. The old addresses (chrisrohn.github.io, chrisrohn.com/fitness/) forward here and
bring each phone's data along (`move.html`). See
[fitness/README.md](https://github.com/chrisrohn/chrisrohn/blob/main/fitness/README.md#the-app-on-your-phone).
