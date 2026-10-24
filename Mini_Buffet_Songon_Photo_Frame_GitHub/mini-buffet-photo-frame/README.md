# Mini-Buffet Songon Photo Frame

Mini-site statique mobile-first pour créer une affiche de statut personnalisée avec sa photo. Pas d'application à installer, pas de serveur et pas d'envoi de photo : la composition se fait localement dans le navigateur.

## Fonctions
- Importer une photo JPG, PNG ou WebP (maximum 10 Mo)
- Cadrage circulaire et zoom
- Deux messages : « Je serai au » et « Je t'invite au »
- Export de l'affiche en PNG
- Partage natif si le navigateur le permet
- Bouton de réservation WhatsApp configuré pour +225 0709083200

## Publier gratuitement avec GitHub Pages
1. Connecte-toi à GitHub et crée un dépôt public nommé `mini-buffet-songon`.
2. Téléverse `index.html` à la racine du dépôt (et ce README si tu le souhaites).
3. Ouvre **Settings → Pages**.
4. Dans **Build and deployment**, choisis **Deploy from a branch**, sélectionne `main` et `/ (root)`, puis **Save**.
5. Attends la publication indiquée par GitHub Pages. Le lien sera du type `https://TON-PSEUDO.github.io/mini-buffet-songon/`.
6. Ouvre le lien sur ton téléphone et teste le chargement de photo, le téléchargement et le bouton WhatsApp avant de le diffuser.

## À vérifier avant diffusion
- Vérifier que le numéro WhatsApp est bien celui qui reçoit les réservations.
- Le QR code n'est pas inclus dans cette version : le bouton WhatsApp est le lien d'action. Si tu veux un QR code imprimé, génère-le à partir du lien public une fois GitHub Pages activé.
- Le partage d'image dépend du navigateur et du téléphone. Si le partage direct n'est pas pris en charge, l'utilisateur télécharge le PNG puis le publie dans son statut WhatsApp.
