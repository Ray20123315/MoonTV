# LunaTV Cloudflare D1 port
Code basis: MoonTechLab/LunaTV UI plus kzb12580/LunaTV-CF Pages/D1 adapter.
Original private D1 data stays in the original Cloudflare database, not in Git.
The standalone Pages project continues using DB and the original environment variables.
Official upstream commit: 6c0428d1ae7a8322efa8031909ec77cac22fd866
Reference adapter commit: ef14d866fb390db8ea189ae3f1768c9a45455a12
The upstream Node.js migration endpoints are deliberately excluded from the Edge build.
