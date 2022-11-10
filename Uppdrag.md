#Missionstatement

CLASSES:
User


Admin
-Admin ska kunna:
	-Skapa nya användare (admin och customer)
	-Sätta växelkurs (SekToUSD, SekToEur, UsdToSek, EurToSek)

Customer


BankAccount


SavingsAccount


BankSystem
-Måste logga in för att använda systemet:
	-3 försök, sen låsas man ut ur systemet.
	-Olika menyer beroende på om det är ADMIN eller CUSTOMER

-Alla överföringar TILL och FRÅN användarnas konto ska sparas på något sätt.

-Användare ska kunna se en lista med:
	-Bankkonton
	-Saldot på bankkonton

-Användare ska kunna föra över pengar mellan egna konton
	-Överföringar måste gå via växelkursen om de är av olika valuta.

-Användare ska kunna föra över pengar till andra användare
	-Överföringar måste gå via växelkursen om de är av olika valuta.

-Användare ska kunna öppna nya konton (för sig själv)
	-Ska kunna välja valutan på nya kontot
	-Ska kunna välja typ av konto (Bankkonto/Sparkonto)
		-Få se räntan utifrån insatta summan(t.ex sätta in 100 med ränta 0.1% = 110

-Användare ska kunna låna pengar från banken
	-Få se ränta på lånet
	-Får ej låna mer än 5x den totala summan på alla deras konton

-NÄR ALLT ÄR FÄRDIGT:
	-Fixa färg på menyerna
	-Allt ska vara tydlig på menyerna
	-FIXA EN ASCII-LOGGA
	-UserInterface

-AVSLUTNINGSVIS
	-Transaktioner ska ske 15-minuter EFTER att man lägger in de.
