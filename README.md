#  Projet Minimalist-blog-laravel

## Si vous souhaitez utiliser le projet :

```bash
gitclone https://github.com/Choom87/Blog_Laravel.git
```

Positionnez vous dans votre répertoire Projet et créer le fichier .env:

```bash
cd VotreRépertoireProjet
cp .env.example .env
```

```bash
docker run --rm --interactive --tty \
    --volume $PWD:/app \
    composer install
```
```bash
vendor/bin/sail up -d
vendor/bin/sail artisan migrate
```git