# Captis - Landing Page

Landing page para GitHub Pages.

## Publicar no GitHub Pages

Se o repositório **captis-lpv1** já existir com outro conteúdo e você quiser que ele tenha **só** esta pasta:

```powershell
cd d:\apps\Obsidian\CAPTIS-OBSIDIAN\captis-lpv1
git init
git remote add origin git@github.com:guiaugustinegri/captis-lpv1.git
git add .
git commit -m "Landing page Captis CMI"
git branch -M main
git push -u origin main --force
```

**Atenção:** `--force` sobrescreve o histórico do repositório. Use só se quiser que o repo fique apenas com esta landing.

Depois, no GitHub: **Settings → Pages → Source:** Deploy from branch **main** / **/(root)**. Salve.  
O site ficará em: **https://guiaugustinegri.github.io/captis-lpv1/**
