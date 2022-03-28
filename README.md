# membuat project laravel versi 8
- composer create-project --prefer-dist laravel/laravel pertemuan2 "8.*"

# masuk kedalam direktori pertemuan2
- cd pertemuan2
- code .

# untuk mengambil libraries UI
- composer require laravel/ui
- composer require livewire/livewire
- php artisan ui bootstrap --auth
- npm install && npm run dev
- https://laravel-livewire.com/docs/2.x/quickstart
- php artisan migrate