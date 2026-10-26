# De Fietsenmakerij

Statische one-page website voor De Fietsenmakerij (Affligem), gehost op GitHub Pages.

- `index.html` – de volledige pagina (HTML + CSS)
- `assets/` – logo's en foto's

## Lokaal bekijken

```bash
python3 -m http.server 8765
```

Open daarna http://localhost:8765.

## Publiceren op GitHub Pages

1. Push deze map naar een GitHub-repository.
2. Ga naar **Settings → Pages**, kies **Deploy from a branch**, branch `main`, map `/ (root)`.
3. De site staat na een minuutje op `https://<gebruikersnaam>.github.io/<repo>/`.

Eigen domein (defietsenmakerij.be): vul het in onder **Settings → Pages → Custom domain** en zet bij de domeinprovider een `CNAME`-record voor `www` naar `<gebruikersnaam>.github.io`.
