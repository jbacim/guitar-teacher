# Guitarven

En mobilvenlig, dansk guitar- og musikskole med korte daglige lektioner, en gehørøvelse og et instrumentværksted i topmenuen. Gehørøvelsen afspiller en tone, viser noden på nodesystemet efter svaret og går automatisk videre. Værkstedet viser et klaviatur eller en guitarhals og har også en tromme, der kan styres med telefonens bevægelsessensor efter tilladelse. Alle lyde laves i browseren med Web Audio API. Appen er bygget med almindelig HTML, CSS og JavaScript og gemmer genrevalg, gennemførte lektioner og øvestime lokalt i browseren.

## GitHub Pages

Workflowet i `.github/workflows/pages.yml` udgiver sitet, når der pushes til `main`. I repositoryets indstillinger skal Pages være sat til **GitHub Actions** som build- og deploymentkilde.

Projektets URL er `https://jbacim.github.io/guitar-teacher/`. Sitet bruger relative filstier, så det virker under GitHub Pages-projektets undermappe.
