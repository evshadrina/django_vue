python3 manage.py runserver 127.0.0.1:8003

см:
path('movies1/', views.show_all_movies1, name='movie-detail_all1'),
при вызове шаблона http://127.0.0.1:8003/movies1/
шаблон  show_all_movies1.html - не возвращается Hello Vue

сам по себе(в браузере) шаблон работает ном.

