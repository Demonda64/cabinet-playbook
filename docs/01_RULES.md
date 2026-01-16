# Règles — Cabinet (Repo privé)

## 1) Règles de sécurité

- Jamais de documents légaux : devis, contrats, factures, assurances.
- Jamais de données client identifiantes (PII).
- Jamais de secrets : .env, clés, tokens, accès.

## 2) Ce qui est autorisé

- Process génériques, checklists, templates neutres
- Standards techniques, snippets, conventions
- Documentation interne sans données sensibles

## 3) Répartition recommandée des repos

- `Cabinet` (privé) : système interne
- `cabinet-playbook` (public, optionnel) : version vitrine (process génériques uniquement)
- `template-*` (public) : templates réutilisables
- `demo-*` (public) : démos / cas simulés
- `client-*` (privé) : projets clients (un repo par client)
