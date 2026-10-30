# Zaphalt User Manual

**Zaphalt – zap it, then halt.** A charge alarm for Android. It rings the moment your phone reaches the battery level you choose, so you can unplug before the battery sits at 100% for hours.

Works on Android 8.0 or newer. No internet needed for the alarm itself.

---

## 1. Why use Zaphalt?

Phones stop charging at 100%, so they don't really "overcharge". The wear comes from **sitting at 100% for a long time** and from **heat**. Zaphalt lets you pick a gentler level (80–90% is a good choice) and tells you when to unplug.

**Tip:** Keeping your battery between 20% and 80% is the sweet spot. Use the full 100% only when you really need it.

---

## 2. Installing

1. Copy the **Zaphalt APK** to your phone (USB, Google Drive, WhatsApp) and tap it.
2. If Android says your phone isn't allowed to install unknown apps from this source, tap **Settings**, switch on **Allow from this source**, go back and tap **Install**.
3. If **Play Protect** warns about an unrecognized app, tap **More details**, then **Install anyway**. This message appears for any app outside the Play Store.
4. Tap **Open**.

**Updating:** install the new APK over the old one. Your settings stay.
**Uninstalling:** long-press the app icon, choose **App info**, then **Uninstall**.

---

## 3. First-time setup (2 minutes)

1. **Allow notifications** when Android asks. Without them you won't see the alarm screen.
2. On the **Live** tab, switch **Monitoring** on. A small notification saying "Zaphalt is watching your battery" means it works.
3. If a yellow **Finish setup for reliable alarms** card appears, tap **Allow** (notifications) and **Fix** (battery optimization). The card disappears when you're done.
4. Tap **Test alarm** to check you can hear it. Tap **Stop alarm** to silence it.
5. Plug in your charger. Done.

---

## 4. The four tabs

| Tab | What it does |
|---|---|
| ⚡ **Live** | Shows your battery percentage, voltage and temperature. Switch Monitoring on or off, set your **Alarm level**, and test or stop the alarm. |
| 📍 **Where** | Live map, place search, directions and an offline radar. Also where you save your office. |
| ⚙️ **Settings** | Voice, low-battery reminder, heat warning, Overnight mode, location options and battery diagnostics. Every change saves instantly. |
| 📖 **Guide** | Animated help inside the app, with a quick-start checklist. |

---

## 5. Setting your alarm level

On the **Live** tab, drag the **Alarm level** slider (50% to 100%). When your battery reaches that number while charging, the alarm goes off.

**When the alarm rings:**
- Loud sound (it uses your phone's **alarm volume**, not media volume)
- Vibration
- A spoken message: "Battery full, please unplug the charger"

**To stop it:** tap **Stop alarm**, or just **unplug the charger**. The alarm stops by itself and re-arms for your next charge.

---

## 6. Overnight mode 🌙

Overnight mode keeps your phone from waking you with a loud alarm, and from sitting at a high charge all night.

### What is the "Night limit"?

> **The Night limit is a lower battery level that Zaphalt uses only while you are asleep.**
>
> Your normal **Alarm level** might be 90%. At night you'd probably rather your phone stop charging earlier, because sleeping with a battery parked at 100% for hours is the hardest thing on it. So during your sleep hours Zaphalt uses the **Night limit** instead (80% by default).

**Simple rule:** while you sleep, Zaphalt uses whichever number is **lower**, your Alarm level or your Night limit.

| Alarm level | Night limit | Alarm goes off at (while asleep) |
|---|---|---|
| 90% | 80% | **80%** |
| 85% | 90% | **85%** |
| 100% | 70% | **70%** |

During sleep hours the alarm is **quiet**: it vibrates and speaks, but it **never rings**. If you turn off **Also speak while I sleep**, it only vibrates.

### Setting your sleep time

1. Turn on **Overnight mode** in Settings.
2. Choose how your week looks:
   - **Same every day**
   - **Sun – Thu + Sat, Friday different**
   - **Sun – Thu, Fri & Sat different**
   - **Set each day separately**
3. Set **Sleep from** and **Wake at** using the hour, minute and AM/PM boxes. (On the website demo you can drag the 🌙 and ☀️ handles around the clock instead.)
4. Set your **Night limit** with the slider.
5. Choose whether you want **Also speak while I sleep** on or off.

> The schedule belongs to the day you **wake up**. Friday's wake time covers Thursday night.

### Testing it

Tap **🔔 Test sleep-hours alert** to feel and hear exactly what the alarm will do while you sleep. On the website demo, tap **⏹ Stop alarm** to cut the voice short at any time.

---

## 7. Other alerts

- **🪫 Low-battery reminder.** One nudge to plug in at 20% (you can pick any level from 5% to 40%).
- **🔥 Heat warning.** An alert when charging gets hot, by default above 40°C. You get one alert per hot spell. Move the phone somewhere cool or unplug it.

---

## 8. Location profile: "No voice at office" 📍

Save your office once on the **Where** tab (**Set office**). Inside the **200 m zone** around it, the alarm still rings but **does not speak**, so you never embarrass yourself at your desk. Zaphalt checks your location only at the moment an alarm fires.

### How the alarm decides how to behave

The first match wins:

| Where / when | What happens |
|---|---|
| At your office | 🔊 Sound and vibration, no voice |
| During sleep hours | 📳 Vibration and voice, never rings (vibration only if sleep voice is off) |
| Anywhere else | 🔊 Sound, vibration and voice |

---

## 9. The Where tab 🗺️

- **Search:** type a place name, or coordinates such as `23.87, 90.38`.
- **Five map styles:** Streets, Bright, Light, Satellite, Hybrid.
- **Controls:** zoom (+ / −), compass, 3D tilt, and a locate-me button.
- **Gestures:** drag to move, pinch or double-tap to zoom, two-finger twist to rotate, two-finger drag to tilt.
- **Directions:** choose how you want to get there and see the route and estimated time. There is no live traffic.
- **Radar (works offline):** a rotating sweep with range rings, a trail of where you've walked and a dashed line to your office. Choose **North up** or **Heading up**, zoom in or out, or **Clear trail**.

**Internet is needed only here**, for the map picture, place search and directions. Searching and routing send the words you type and the points being routed to free OpenStreetMap-based services. The alarm, monitoring, notifications and radar all work offline.

---

## 10. Home-screen widget and Quick Settings tile

### Widget
1. Long-press an empty area of your home screen.
2. Tap **Widgets**, find **Zaphalt**, and drag it onto the home screen.
3. It shows your battery percentage and **ON** or **OFF**. Tap it to switch monitoring.

### Quick Settings tile
1. Swipe down twice from the top of the screen.
2. Tap the **pencil (Edit)** icon.
3. Drag the **Zaphalt** tile into your active tiles.
4. Tap the tile to switch monitoring on or off. It lights up when on.

If your phone blocks starting from the widget or tile, open Zaphalt and use the **Monitoring** switch instead.

---

## 11. Battery diagnostics

In **Settings**, battery diagnostics shows the live numbers your phone reports: current (mA), power (W), voltage, temperature, level, charge stored, average current and charging status.

- A **+** sign means charging. A **−** sign means draining.
- **Show raw readings** displays the exact values from Android.
- **Copy readings** puts them on your clipboard so you can paste them into a message when asking for help.
- **Re-detect current unit & sign** fixes numbers that look wrong (some phones report them differently).

---

## 12. Notifications you'll see

| Notification | Meaning |
|---|---|
| **Zaphalt is watching your battery** (quiet) | Monitoring is on. Android requires this while the app runs in the background. |
| **Unplug the charger!** (full screen) | The alarm is ringing. Tap **Stop alarm** to silence it. |
| **Battery low (20%)** | Time to plug in. |
| **Battery is hot (41.0°C)** | Move the phone somewhere cool or unplug it. |

---

## 13. Troubleshooting

### 🔇 No sound
- Raise the **Alarm volume** in your phone's Sound settings. Media volume doesn't affect it.
- Make sure **Do Not Disturb** isn't set to "Total silence".
- Tap **Test alarm** to check.

### 💤 Alarm stops working when the screen is off
Your phone's battery saver is putting Zaphalt to sleep.
- Set Zaphalt's battery use to **Unrestricted** (or "No restrictions").
- Tap **Fix** on the yellow setup card in the Live tab.

**Xiaomi · Redmi · Poco:** enable **Autostart** for Zaphalt and set Battery saver to **No restrictions**.
**Samsung:** remove Zaphalt from **Sleeping apps** and **Deep sleeping apps**, and set battery use to **Unrestricted**.
**Oppo · Realme · Vivo · OnePlus:** allow **Auto-launch** / **Background activity** for Zaphalt and disable battery optimization for it.

### 🗣️ No voice
- Install or enable a text-to-speech engine, for example **Speech Services by Google**, in your phone's **Text-to-speech** settings, and download your language.
- Check **Voice announcement** is on in Zaphalt's Settings.
- Remember the voice is off at your saved office. During sleep hours it also needs **Also speak while I sleep** switched on.

### 🔔 No notifications
- Open Android Settings → Apps → Zaphalt → Notifications and turn them on.
- Tap **Allow** on the yellow setup card in the Live tab.

---

## 14. FAQ

**Does my phone really overcharge?**
No. Modern phones stop charging at 100%. The harm comes from staying at 100% for a long time and from heat, which is why Zaphalt lets you choose a lower level.

**Does Zaphalt drain my battery?**
It is built to be light. It wakes only when Android reports a battery change and loads the voice engine only when it needs to speak.

**Does it work after a restart or with wireless chargers?**
Yes to both. If Monitoring was on before the restart it comes back on, and any charging method Android reports as charging works.

**Can I change the alarm sound?**
Zaphalt uses your phone's default alarm sound. Change it in your phone's Sound settings.

**Does it need internet?**
Only on the Where screen. The alarm, monitoring, notifications and radar work offline.

**Android warns me when I install the APK.**
That message appears for any app that is not from the Play Store. Allow installs from your browser or file manager, then tap **More details** and **Install anyway** on the Play Protect prompt.

---

*Made with ⚡ by Shukdev. Map data © OpenStreetMap contributors · Tiles by OpenFreeMap.*
