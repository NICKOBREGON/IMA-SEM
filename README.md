# SEM · IMV — Gestió d'Incidents de Múltiples Víctimes

Aplicació web progressiva (PWA) per a personal del SEM Catalunya per a la gestió operativa d'IMV en entorn extrahospitalari.

## Contingut basat en els Annexos oficials SEM:
- Annex I · Procediment operatiu al CECOS
- Annex II · Triatge de Pacients (mètode START)
- Annex III · Triatge Avançat META
- Annex V · Organigrama Operatiu al lloc de l'IMV
- Annex VI · Fitxes Operatives (per tipus de resposta)
- Annex VII · Targeta Triatge
- Annex VIII · Logística Sanitària IMV

## Funcionalitats
- **Activació IMV** amb temporitzador i selector de nivell (I / II / III / IV)
- **Criteri activació** automàtic per nombre de víctimes
- **Triatge START** pas a pas interactiu
- **Triatge META** avançat amb ordre d'evacuació
- **Comptadors** en temps real (Vermells / Grocs / Verds / Negres / Blancs)
- **Organigrama** per tipus d'incident (ATM, Incendi, RNBQ, Atemptat, General)
- **Fitxes operatives** per rol (Metge, DUI, TTS/TES, Papa Echo, Enllaç D)
- **Checklists** persistents per rol i tipus de resposta (adequada SVA / inadequada / sense SVA)
- **Canals de ràdio** per nivell: EME1_CAT · D_1 · EME2_CAT
- **Indicatius**: Alfa Sierra, Papa Echo, Enllaç D
- **Codis K** de ràdio (K-0 a K-12) i codis numèrics SEM (3.6, 3.10...)
- **Comunicats tipus** CECOS llestos per usar
- **Telèfons importants** editables i clicables

## Instal·lació al mòbil (PWA)
1. Obre `index.html` des de GitHub Pages (o servidor local)
2. **iOS**: Safari → compartir → "Afegir a pantalla d'inici"
3. **Android**: Chrome → menú → "Instal·lar aplicació"
4. Funciona **100% offline** un cop carregada

## GitHub Pages
1. Puja el contingut a un repositori GitHub
2. Ves a Settings → Pages → Branch: main / Folder: root
3. L'app estarà disponible a `https://<user>.github.io/<repo>/`

## Ús al camp
- Fes servir la **pestanya Inici** per activar l'incident i comptar víctimes
- **Triatge** per guia START o META i comptador ràpid
- **Org.** per veure l'organigrama del teu tipus d'incident
- **Fitxes** per seguir el checklist del teu rol
- **Ràdio** per canals, codis K i procediments de comunicació
- **Telèfons** per trucar directament

## Avís legal
Eina de suport operatiu. Sempre segueix els protocols vigents del SEM i les indicacions del Comandament Operatiu. En cas de dubte, consulta CECOS.
