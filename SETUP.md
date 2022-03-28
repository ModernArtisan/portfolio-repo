# [SETUP](https://laravel.com/docs/9.x/installation#installation-via-composer)

```
composer create-project laravel/laravel portfolio-repo
```

Alternately setup using advanced git command: laravel new portfolio-repo --github="--private"

```
laravel new portfolio-repo --git
git remote add origin https://github.com/ModernArtisan/portfolio-repo
git branch -M main
git push -u origin main
git branch -M editing
git push -u origin editing
```

## Setting Download Links

Place files at: storage\app\public

Then create a symbolic link and reference the url call 

```
php artisan storage:link

{{ asset('storage/mainResume.pdf') }}
```







