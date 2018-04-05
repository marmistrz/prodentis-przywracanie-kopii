### Przywracanie kopii w programie ProDentis 5.0
#### Restoring from backup in ProDentis 5.0

Ten poradnik ma znaczenie tylko dla polskich użytkowników i jest dostępny tylko po polsku.
This guide is relevant only for Polish users, hence provided only in Polish.

### Jeżeli kupiłeś lub zamierzasz kupić program ProDentis, koniecznie przeczytaj to jak najszybciej!

Z przywróceniem bazy danych gabinetu w programie ProDentis jest kłopot. Przywrócenie kopii zapasowej wymaga aplikacji BackupManager, która nie jest dostarczana wraz programem ProDentis. 

Niestety, na obecną chwilę nie znalazłem w Internecie żadnej jego kopii, jest on więc na wagę złota. Dawniej na stronie firmy INFOTEL dostępny był plik zip, ale już został usunięty. Plik `BackupManager.exe` należy umieścić w katalogu roboczym programu ProDentis.

Kolejnym krokiem jest zmiana rozszerzenia backupu na `.xls`. Zatem plik `backup100.BAK` powinien nazywać się `backup100.xls`. Tylko takie pliki są wykrywane przez `BackupManager`.

Ostatnim krokiem jest wgranie kopii zapasowej. Uruchamiamy program `BackupManger.exe`, próbujemy wybrać plik. Pojawia się jednak pytanie o hasło. Nie jest to jednak hasło administratora ani lekarza. Jest to po prostu hasło arbitralnie ustalone przez twórcę programu. Brzmi ono `admin_restore`. 

Po wybraniu pliku kopii zapasowej i potwierdzeniu, że chcemy przywracać z kopii, operacja przebiega bez komplikacji.

Cała procedura pokazuje jak zachłanna i pazerna jest wrocławska firma INFOTEL. Wspracie techniczne dostępne jest tylko przez rok (później płatne), a procedura przywracania z kopii zapasowej jest zaprojektowana tak, aby bez opłaconego wsparcia technicznego nie mogła zostać przeprowadzona.
