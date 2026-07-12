# Chore Quest — How It Works for Each of You

## As the Kid 🧒

1. Open the app link (bookmark it or add it to the home screen so it looks like a real app icon).
2. It opens straight into **Kid Mode** — no login needed.
3. Tap **Daily** tab → see today's chores as a checklist.
4. Tap a chore to check it off → instant animation-style feedback, points added right away.
5. Tap **Dashboard** anytime to see:
   - Today's progress bar and points
   - Current streak (consecutive days with everything done)
   - Badges earned
   - The Weather Insights section (what to wear)
6. Tap **Weekly** or **Monthly** to see a grid/heatmap of how the week or month is going.

The kid **cannot** add, rename, re-point, or delete chores — that option simply isn't visible in Kid Mode. They can only check things off.

## As the Parent 👨‍👩‍👧

1. On any device, tap the button in the top-right corner — it'll say **🧒 Kid Mode**.
2. Tap it → enter PIN **1300** → it switches to **🔓 Parent Mode** (button turns purple).
3. Go to the **Daily** tab → you'll see a purple **🛠️ ADMIN** banner with quick instructions, then:
   - **Manage Missions** — add new chores, rename existing ones, change point values, or delete ones no longer needed
   - **Sync Across Devices** — where you connect this device to your GitHub repo (one-time setup per device) so progress stays in sync everywhere
4. Tap the mode button again to switch back to **Kid Mode** — no PIN needed to go back, only to go *into* Parent Mode.

## The Sync Part (Behind the Scenes)

Once you've connected a device (owner/repo/token, tap Save connection), that device:
- **Auto-pushes** any change within ~1 second
- **Auto-pulls** other devices' changes every ~5 seconds

So if your kid checks something off on their tablet, your phone will show it updated within about 5 seconds — no manual syncing needed day to day.

## A Practical Workflow

- **Set up once**: You go into Parent Mode on the kid's device to add the chore list. Then Parent Mode on your phone (and a 3rd device if you have one) to connect it to the same GitHub sync.
- **Daily use**: Kid stays in Kid Mode, checks off chores as they go. You check the Dashboard on your phone to see their progress without needing to touch their device.
- **As chores change**: Only you, in Parent Mode with the PIN, edit the mission list — the kid's view updates automatically next time they open the Daily tab.
