# mygeeky-beacon

This is a [myGeeKy](https://github.com/mygeeky/myGeeKy) beacon.

`beacon.json` holds a public key, an optional status and a few interest tags.
It also holds **sealed signals** (🙏 thanks, 📚 learned from your work, ⭐ used
your work, 👀 following, 🤝 collaborate) this account sent to other myGeeKy
users. Each one is encrypted so that **only its recipient can read it**:
nobody else can tell who it's for or what it says. There's no free text.

It may also hold up to three **calls for contributors**: a short, public
invitation to help with one of this account's own repos (the skills wanted,
one sentence, how long it stays open). myGeeKy users whose own work fits see
it in their panel; an answer reaches this account as a sealed signal.

It's written only by myGeeKy, with a token scoped to this one repository.
