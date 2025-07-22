## Afficher une page HTML à partir d'un template twig

```php
$this->render('base.html.twig');
```

## Profiler

_Un outil qui permet de déboguer une application symphony => c’est la barre en bas de la page quand tu es en mode dev_

| Fonction   | Description courte                                                              | Exemple d'utilisation             | Affichage dans le Profiler |
| ---------- | ------------------------------------------------------------------------------- | --------------------------------- | -------------------------- |
| `render()` | Affiche une **vue Twig** dans une réponse HTTP.                                 | `$this->render('home.html.twig')` | Oui (onglet **Twig**)      |
| `dump()`   | Affiche le contenu d'une variable pour le débogage sans interrompre l'exécution | `dump($variable);`                | Oui (onglet **Debug**)     |
| `dd()`     | Fait un `dump()` **et stoppe l'exécution** immédiatement                        | `dd($variable);`                  | Non (interrompt tout)      |
