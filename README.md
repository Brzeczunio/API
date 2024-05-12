# API
API do ćwieczeń

Z wykorzystaniem tego API można ćwiczyć pisanie testów:
	1. Wydajnościowych (z wykorzystaniem np. NBomber)
	2. API (z wykorzystaniem np. RestSharp)

Do uruchomienia API trzeba zainstalować SQL Server Express lub MariaDB Community Server, następnie stworzyć bazę np. TestAPI. Zainstalować środowisko uruchomieniowe .NET 8.

Po stworzeniu bazy danych trzeba podać parametry połączenia (uzupełnić ConnectionString) w pliku: appsettings.json

W ostatnim kroku uruchamiamy TestAPI.exe i możemy korzystać z naszego API na komputerze lokalnym: http://localhost:5000/swagger/index.html