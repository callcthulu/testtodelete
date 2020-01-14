# testtodelete

Komendy - tworzenie repo:
	Skopiuj repo z github:
		git clone https://github.com/callcthulu/testrepo2.git
	
	Utwórz repo lokalnie i załaduj je:
		git init
		git add README.md
		git commit -m "first commit"
		git remote add origin https://github.com/callcthulu/testrepo2.git
		git push -u origin master
	
	Dodaj istniejące repo lokalne:
		git remote add origin https://github.com/callcthulu/testrepo2.git
		git push -u origin master
	
Komendy - ściąganie zmian:
	git pull
	
Statusy:
	git log - status commitow
	git status - jaki branch, jakie zmiany lokalne, co wejdzie do commita

Komendy wrzucanie zmian:
	git add "nazwa"
	git add -A
	
	git commit -m "message"
	
	git push

Branche:
	master - początkowy
	
	git branch -a -lista branchy 
	git branch nazwa_brancha - nowy branch
	git checkout -b nazwa_brancha -utwórz i przełącz się na branch
	git checkout nazwa_brancha - zmień branch
	git push origin nazwa_brancha - dodaje branch do gita
	
	git branch -d nazwa_brancha - usuwa branch
	git branch -D nazwa_brancha - wymusza usunięcie
	git push origin :nazwa_brancha - przekazuje usuniecie na github
	
merge branchu do master (lub innego):
	git checkout branch_ktory_ma_zostac
	git merge branch_do_zmergowania
	
https://learngitbranching.js.org/?fbclid=IwAR0H-h9h09YTAda3o1dWvtBswIw0dqKnHVxD7zS5hCO1wcIDJZo-KMcx4tM
	
