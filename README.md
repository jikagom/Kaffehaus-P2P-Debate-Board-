# Kaffehaus — P2P Debattenbrett

> *"Where every thesis demands its antithesis."*
<img width="1296" height="846" alt="image" src="https://github.com/user-attachments/assets/1dae3777-6c90-49fd-ab6e-1b96cf48684c" />

A peer-to-peer anonymous debate board built on the [Intercom](https://github.com/Trac-Systems/intercom) protocol by Trac Systems.

Inspired by the **Wiener Kaffeehaus** of 1890–1920 Vienna — the coffeehouses where Freud, Klimt, Mahler, and Wittgenstein would argue, publish manifestos, and change the world over a *Melange*. Kaffehaus brings that tradition to the peer-to-peer internet.

---

## What It Does

Users broadcast a **thesis** — a single provocative statement — over Intercom sidechannels. Any peer can respond with an **antithesis**. The room votes. No server. No moderator. Only arguments.

- Post a thesis (broadcast to all connected peers via Intercom)
- Challenge any open thesis with an antithesis
- Vote anonymously — tallies are public, identities are not
- All coordination happens over Intercom P2P sidechannels
- Replicated state layer stores the debate record

---

## App

Open `index.html` in any browser to run the frontend.  
The app connects to the Intercom network for live P2P debate coordination.

**Proof of working:** See `<img width="1281" height="820" alt="image" src="https://github.com/user-attachments/assets/c56f1375-5d2c-4a36-9cc7-34b118ea866c" />
` folder or the demo video linked below.

---

## Trac Address

```
trac1zcxflsf3yf4sh8vt45ehncel5lja25kksxlk47ypqwd7t8wrx6eqh8e8am
```

> Replace this with your actual Trac wallet address before submitting.

---

## Built On

- Fork of [Trac-Systems/intercom](https://github.com/Trac-Systems/intercom)
- Pure HTML/CSS/JS frontend — no build step, no dependencies
- Intercom protocol for P2P sidechannel communication

---

## Contributing

Open a PR or post a thesis. All debate welcome.

*Est. MMXXV — Trac Network*
