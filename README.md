---

# 🚀 ISS Overhead Notifier

Ever wanted to *casually* look up at the night sky and say,
“Hey, that bright dot is literally a \$150 billion science lab orbiting Earth at 28,000 km/h”?
Well, now you can.

This little Python script will send you an email whenever the **International Space Station (ISS)** is flying right above your location *and* it’s dark enough to actually see it. No telescope, no NASA job, just… Gmail.

---

## 🌌 How it works

1. **Tracks the ISS** using a public API that tells us where it is right now.
2. **Checks if it’s night** at your location (because space spotting in daylight is just cloud-spotting).
3. **Emails you** with a friendly “LOOK UP 👆” when the ISS is nearby.

---

## 🛠 Requirements

* Python 3
* `requests` (for talking to the ISS and the Sun)
* `smtplib` (for harassing your inbox)
* A Gmail account that won’t mind being a space notifier

---

## 🧑‍🚀 Setup

1. Clone this repo.
2. Open the script and put your latitude/longitude.
3. Add your Gmail + App Password (don’t use your *real* password, or the ISS won’t be the only thing spying on you).
4. Run it and wait for your inbox to say:

```
Subject: Look Up 👆
The ISS is above you in the sky.
```

---

## 📡 Why?

Because looking at the ISS makes you feel small, humble, and slightly jealous of astronauts.

---
