# dpth-keepawake

A scheduled GitHub Action that requests `https://payment-platform-h303.onrender.com/api/health` every 10 minutes, so the free Render instance stays awake.

- There's no application code and there are no secrets here.
- GitHub may delay scheduled runs at busy times.
- GitHub disables scheduled workflows after 60 days without repository activity. Re-enable it from the **Actions** tab if that happens.
