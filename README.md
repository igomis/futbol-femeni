# Guia d'Equips de Futbol Femení (Laravel)

Mini‑app MVC amb Laravel per a gestionar una guia d’equips (llistat, detall i alta bàsica). Inclou:
- Rutes web, controlador, vistes Blade i component.
- Estils amb Vite.
- Formulari amb validació que guarda en **sessió** (sense BBDD).

## Requisits
- PHP 8.2+, Composer, Node 18+
- Docker (opcional) + Laravel Sail

## Instal·lació ràpida (Sail)
```bash
curl -s "https://laravel.build/futbol-femeni?with=mysql,mailpit" | bash
cd futbol-femeni
./vendor/bin/sail up -d
./vendor/bin/sail artisan migrate
 ```
## Instal.lació en codespaces

 ```bash
php artisan serve --host=0.0.0.0 --port=8000
 ```
