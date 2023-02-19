
# Zadanie 1 - Łamanie haseł (met.brute-force)

1. HASH: 81dc9bdb52d04dc20036dbd8313ed055
Possible Hashs:
[+] MD5
[+] Domain Cached Credentials - MD4(MD4(($pass)).(strtolower($username)))

hashcat -m 0 --show 81dc9bdb52d04dc20036dbd8313ed055
81dc9bdb52d04dc20036dbd8313ed055:1234

2. HASH: d8826bbd80b4233b7522d1c538aeaf66c64e259a
Possible Hashs:
[+] SHA-1
[+] MySQL5 - SHA-1(SHA-1($pass))

sudo hashcat -m 100 --show d8826bbd80b4233b7522d1c538aeaf66c64e259a
d8826bbd80b4233b7522d1c538aeaf66c64e259a:4121

3. Hash: b021d0862bc76b0995927902ec697d97b5080341a53cd90b780f50fd5886f4160bbb9d4a573b76c23004c9b3a44ac95cfde45399e3357d1f651b556dfbd0d58f
Possible Hashs:
[+] SHA-512
[+] Whirlpool
sudo hashcat -m 1700 --show b021d0862bc76b0995927902ec697d97b5080341a53cd90b780f50fd5886f4160bbb9d4a573b76c23004c9b3a44ac95cfde45399e3357d1f651b556dfbd0d58f
b021d0862bc76b0995927902ec697d97b5080341a53cd90b780f50fd5886f4160bbb9d4a573b76c23004c9b3a44ac95cfde45399e3357d1f651b556dfbd0d58f:6969

4. Hash: 31bca02094eb78126a517b206a88c73cfa9ec6f704c7030d18212cace820f025f00bf0ea68dbf3f3a5436ca63b53bf7bf80ad8d5de7d8359d0b7fed9dbc3ab99
Possible Hashs:
[+] SHA-512
[+] Whirlpool
sudo hashcat -m 1700 --show 31bca02094eb78126a517b206a88c73cfa9ec6f704c7030d18212cace820f025f00bf0ea68dbf3f3a5436ca63b53bf7bf80ad8d5de7d8359d0b7fed9dbc3ab99
31bca02094eb78126a517b206a88c73cfa9ec6f704c7030d18212cace820f025f00bf0ea68dbf3f3a5436ca63b53bf7bf80ad8d5de7d8359d0b7fed9dbc3ab99:0

5. Hash: 9e66d646cfb6c84d06a42ee1975ffaae90352bd016da18f51721e2042d9067dcb120accc574105b43139b6c9c887dda8202eff20cc4b98bad7b3be1e471b3aa5
Possible Hashs:
[+] SHA-512
[+] Whirlpool
sudo hashcat -m 1700 --show 9e66d646cfb6c84d06a42ee1975ffaae90352bd016da18f51721e2042d9067dcb120accc574105b43139b6c9c887dda8202eff20cc4b98bad7b3be1e471b3aa5 
[sudo] password for kali: 9e66d646cfb6c84d06a42ee1975ffaae90352bd016da18f51721e2042d9067dcb120accc574105b43139b6c9c887dda8202eff20cc4b98bad7b3be1e471b3aa5:sda

6. Hash: 8a04bd2d079ee38f1af784317c4e2442625518780ccff3213feb2e207d2be42ca0760fd8476184a004b71bcb5841db5cd0a546b9b8870f1cafee57991077c4a9
Possible Hashs:
[+] SHA-512
[+] Whirlpool
sudo hashcat -m 1700 --show 8a04bd2d079ee38f1af784317c4e2442625518780ccff3213feb2e207d2be42ca0760fd8476184a004b71bcb5841db5cd0a546b9b8870f1cafee57991077c4a9
8a04bd2d079ee38f1af784317c4e2442625518780ccff3213feb2e207d2be42ca0760fd8476184a004b71bcb5841db5cd0a546b9b8870f1cafee57991077c4a9:Asia


7. Hash: 44d9886c0a57ddbfdb31aa936bd498bf2ab70f741ee47047851e768db953fc4e43f92be953e205a3d1b3ab752ed90379444b651b582b0bc209a739a624e109da
Possible Hashs:
[+] SHA-512
[+] Whirlpool
Nie udało się, zbyt długo trwa.

# Zadanie 2 - Łamanie haseł (met.słownikowa)

1. Hash: 9fd8301ac24fb88e65d9d7cd1dd1b1ec
Possible Hashs:
[+] MD5
[+] Domain Cached Credentials - MD4(MD4(($pass)).(strtolower($username)))
sudo hashcat -m 0 --show 9fd8301ac24fb88e65d9d7cd1dd1b1ec 
9fd8301ac24fb88e65d9d7cd1dd1b1ec:butterfly

2. Hash: 7f9a6871b86f40c330132c4fc42cda59
Possible Hashs:
[+] MD5
[+] Domain Cached Credentials - MD4(MD4(($pass)).(strtolower($username)))
sudo hashcat -m 0 --show 7f9a6871b86f40c330132c4fc42cda59
7f9a6871b86f40c330132c4fc42cda59:tinkerbell

3. Hash: 6104df369888589d6dbea304b59a32d4
Possible Hashs:
[+] MD5
[+] Domain Cached Credentials - MD4(MD4(($pass)).(strtolower($username)))
sudo hashcat -m 0 --show 6104df369888589d6dbea304b59a32d4
6104df369888589d6dbea304b59a32d4:blink182

4. Hash: 276f8db0b86edaa7fc805516c852c889
Possible Hashs:
[+] MD5
[+] Domain Cached Credentials - MD4(MD4(($pass)).(strtolower($username)))
sudo hashcat -m 0 --show 276f8db0b86edaa7fc805516c852c889
276f8db0b86edaa7fc805516c852c889:baseball

5. Hash: 04dac8afe0ca501587bad66f6b5ce5ad
Possible Hashs:
[+] MD5
[+] Domain Cached Credentials - MD4(MD4(($pass)).(strtolower($username)))
sudo hashcat -m 0 --show 04dac8afe0ca501587bad66f6b5ce5ad
04dac8afe0ca501587bad66f6b5ce5ad:hellokitty

6. Hash: 7ab6888935567386376037e042524d27fc8a24ef87b1944449f6a0179991dbdbc481e98db4e70f6df0e04d1a69d8e7101d881379cf1966c992100389da7f3e9a
Possible Hashs:
[+] SHA-512
[+] Whirlpool
sudo hashcat -m 1700 --show 7ab6888935567386376037e042524d27fc8a24ef87b1944449f6a0179991dbdbc481e98db4e70f6df0e04d1a69d8e7101d881379cf1966c992100389da7f3e9a
7ab6888935567386376037e042524d27fc8a24ef87b1944449f6a0179991dbdbc481e98db4e70f6df0e04d1a69d8e7101d881379cf1966c992100389da7f3e9a:spiderman

7. Hash: 470c62e301c771f12d91a242efbd41c5e467cba7419c664f784dbc8a20820abaf6ed43e09b0cda994824f14425db3e6d525a7aafa5d093a6a5f6bf7e3ec25dfa
Possible Hashs:
[+] SHA-512
[+] Whirlpool
sudo hashcat -m 1700 --show 470c62e301c771f12d91a242efbd41c5e467cba7419c664f784dbc8a20820abaf6ed43e09b0cda994824f14425db3e6d525a7aafa5d093a6a5f6bf7e3ec25dfa
470c62e301c771f12d91a242efbd41c5e467cba7419c664f784dbc8a20820abaf6ed43e09b0cda994824f14425db3e6d525a7aafa5d093a6a5f6bf7e3ec25dfa:rockstar



# Zadanie 3 - Analiza ruchu HTTP

Podjęcie próby logowania z włączonym Whiresharkiem
![[strona.png]]

Podsłuchane dane
![[nasłuchiwanie.png]]

Przesłane dane logowania w plaintexcie
![[nasłuchiwanie2.png]]


# Zadanie 4 - Analiza ruchu SSH

Nawiązanie połączenia po ssh
![[sshpolaczenie.png]]

Stworzenie plików z zawartością
![[dodatkoweplikihasla.png]]

Edycja konfiguracji vsFTPd, żeby umożliwić wgrywanie plików po FTP.
![[dodatkoweFTPplikiprzesylanienanoodkomentowanie 1.png]]

Ruch po SSH jest zaszyfrowany 
![[dodatkoweSSHBezpiecznePNG.png]]


# Zadanie 5 - Analiza ruchu FTP

Nawiązanie połączenia po FTP
![[ftp.png]]

Przesłanie oraz ściągniecie plików
![[FTPprzesylanieplikow.png]]

Eksport plików podsłuchanych whiresharkiem
![[wiresharkFTPEksportPlikow.png]]

Eksportowane pliki z whiresharka 
![alt text](https://github.com/AngryPelikan/Projekt2-Omijanie-zabezpieczen/blob/main/FTPprzechwyconePliki.png?raw=true)

# Zadanie 6 - Eternal Blue (wykonane na platformie TryHackMe)

Wykrywanie podatności Nmapem
![[podatnosc.png]]

Wyszukanie podatności w metasploicie
![[eternal1.png]]

Konfiguracja exploita i wykonanie go 
![[eternal2.png]]
