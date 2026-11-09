# Atelier : Contrat de neutralisation financière

![Profile image](dumdum.png)

## Contexte

On vous engage comme netrunners. Le mandat : neutraliser les actifs liquides de trois dirigeants corporatistes. Leur fortune est stockée sur des comptes banques accessibles via un dépôt GitHub compromis.

Votre cible : mettre leur solde **Eurodollars** à **0** dans les trois fichiers de compte. Rien d'autre ne doit être modifié pour ne pas éveiller les soupçons

## Cibles

| Fichier | Corporation | Dirigeant |
|---------|-------------|-----------|
| `compte-militech.md` | Militech | Samantha Cole |
| `compte-kangtao.md` | Kang Tao | Lu Ting |
| `compte-arasaka.md` | Arasaka | Hanako Arasaka |

## Consignes

1. **Cloner** le dépôt compromis
2. Créer une branche avec le nom de votre équipe (`runners-alpha`)
3. Modifier **uniquement** la ligne `eurodollars` dans le frontmatter YAML de chaque fichier. Passer la valeur à `0`
4. **Add**, **commit** et **push**
5. Ouvrir une **Pull Request** vers `main`

**Attention** : toute modification d'un autre champ (nom, corporation, statut) invalide le contrat.

## Commandes de référence

```powershell
git clone [URL_DU_REPO]
git checkout -b runners-[votre-nom]
git add .
git commit -m "Contrat exécuté - neutralisation financière"
git push -u origin runners-[votre-nom]
```
