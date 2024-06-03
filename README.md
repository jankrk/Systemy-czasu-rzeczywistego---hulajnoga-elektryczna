=== Napęd hulajnogi ===

  - Opis modelowanego systemu
    * **Opis ogólny**: Modelowany system to hulajnoga elektryczna, która wykorzystuje napęd elektryczny do poruszania się. System składa się z kilku głównych komponentów, takich jak potencjometr sterujący prędkością, silnik elektryczny, akumulator, wyświetlacz LCD do wyświetlania informacji o prędkości i poziomie naładowania baterii, oraz układ hamulcowy.
    * **Opis dla użytkownika**: Użytkownik steruje hulajnogą za pomocą potencjometru umieszczonego na kierownicy. Przechylając potencjometr do przodu, zwiększa prędkość, a przechylając go do tyłu, zmniejsza prędkość lub włącza hamowanie elektryczne. Silnik elektryczny odpowiada za napędzanie hulajnogi, a informacje o aktualnej prędkości oraz poziomie naładowania baterii są wyświetlane na ekranie LCD umieszczonym na kierownicy. Gdy bateria osiągnie niski poziom naładowania, użytkownik zostanie poinformowany przez odpowiednie komunikaty na wyświetlaczu. 
  - Spis komponentów z komentarzem 
    * processor Real_Time - procesor Real_Time
    * memory RAM - pamięci RAM
    * bus Mag - magistrala Mag
    * device sensor - urządzenie czujnika prędkości
    * device interface - interfejs pilota (manetka) 
    * process control - proces kontroli
    * device actuator - urządzenie siłownika (kontrolera silnika)
    * thread read_data - wątek do odczytu danych
    * thread control_laws - wątek praw sterujących
    * system Complete - fefinicja systemu
  - Model - rysunek (https://drive.google.com/drive/folders/1jF2cdSFW0qYRussQSj3l3D7JiF1lspHG?usp=sharing)
  - Repozytorium GitHub (https://github.com/jankrk/Systemy-czasu-rzeczywistego-hulajnoga-elektryczna)

----
[[dydaktyka:scr_isi:2024:projekty:start|Powrót do listy projektów]]
