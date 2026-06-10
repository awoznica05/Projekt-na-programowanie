# Projekt-na-programowanie
Repozytorium z bazą danych, notatnikiem z Colaba i plikiem readme na programowanie.
Cel analizy: stworzenie modelu przewidywania ocen uczniów na podstawie ilości grania w gry wideo i innych danych, np. godzin snu i poziomu stresu, za pomocą modeli uczenia maszynowego (regresja).
Baza danych:
Pobrana z Kaggle
Składa się z 8000 wierszy oraz 14 kolumn (student_id, age, gender, gaming_hours, study_hours, sleep_hours, attendance, gaming_genre, social_activity, device_usage, reaction_time_ms, addiction_score, stress_level, grades)
Dane są ciągłe oraz kategoryczne (kolumny: gender, gaming_genre, stress_level)
Użyte modele:
Regresja liniowa
Random Forest
Wyniki:
Mniejszy błąd średniokwadratowy popełnił model Random Forest (rmse = 2.29), a w przypadku Regresji Liniowej wyniósł on aż 6.34.
Wniosek: Random Forest lepiej się sprawdza w przewidywaniu ocen uczniów na podstawie danych behawioralnych.
