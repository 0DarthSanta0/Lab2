# Lab2
Карпов Павел Дмитриевич, 2023, 4 курс 4 группа
Справочник Фильм: Название(текст), Режиссер(зависимость), год выхода(число), оценка на IMDb(число с фиксированной запятой)  
Справочник Режиссёр: Имя(текст), Дата рождения(дата)


Шаг 2:
1. SQLite
2. CREATE TABLE Director (
    director_id INTEGER PRIMARY KEY,
    name TEXT,
    birth_date DATE
);

CREATE TABLE Movie (
    movie_id INTEGER PRIMARY KEY,
    title TEXT,
    director_id INTEGER,
    release_year INTEGER,
    imdb_rating NUMERIC(3,1),
    FOREIGN KEY (director_id) REFERENCES Director(director_id)
);

3. 
![image](https://github.com/0DarthSanta0/Lab2/assets/93156714/b025af70-d6bb-4233-9f64-a84191bb2a80)
![image](https://github.com/0DarthSanta0/Lab2/assets/93156714/10116bfa-ed41-48a5-8986-f016568525a3)

