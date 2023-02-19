# Projekt 2: Omijanie zabezpieczeń - Andrzej, Dawid, Jacek, Jakub, Jan 
**Zadanie 1 - Łamanie haseł**: Dla podanych hashy określ typ wykorzystanego algorytmu hashującego, a następnie złam hasło metodą brute-force.
- [x] 1.1:

```
Cd workspace/

Touch hash.txt

Nano hash.txt copy hash

└─$ hashcat -m0 -a 0 hash.txt /usr/share/wordlists/rockyou.txt
```

<img src="../_resources/lu14744uq4wag_tmp_3a36f0adf09dc2f2.png" align="bottom" width="735" height="505" border="0">

- [x] 1.2: 

Hash

`hash-identifier`

d8826bbd80b4233b7522d1c538aeaf66c64e259a

<img src="../_resources/lu14744uq4wag_tmp_dbb6ef9d8c23590c.png" align="bottom" width="723" height="113" border="0">

rezulatat

<img src="../_resources/lu14744uq4wag_tmp_808d5edaa769542e.png" align="bottom" width="589" height="339" border="0">

- [x] 1.3: 

Hash

b021d0862bc76b0995927902ec697d97b5080341a53cd90b780f50fd5886f4160bbb9d4a573b76c23004c9b3a44ac95cfde45399e3357d1f651b556dfbd0d58f

`hash-identifier`

<img src="../_resources/lu14744uq4wag_tmp_4f3ef70df0b423d1.png" align="bottom" width="856" height="232" border="0">

<img src="../_resources/lu14744uq4wag_tmp_e9a58ad9933f2cfe.png" align="bottom" width="856" height="144" border="0">

<img src="../_resources/lu14744uq4wag_tmp_fcaf21f189bfaf1a.png" align="bottom" width="769" height="275" border="0">

- [x] 1.4:

Hash

`hash-identifier`

31bca02094eb78126a517b206a88c73cfa9ec6f704c7030d18212cace820f025f00bf0ea68dbf3f3a5436ca63b53bf7bf80ad8d5de7d8359d0b7fed9dbc3ab99

Rezultat:

`hashcat -m 1700 -a 0 hash.txt /usr/share/wordlists/rockyou.txt`

Rezulatat

<img src="../_resources/lu14744uq4wag_tmp_e37d9ea199e4f6.png" align="bottom" width="823" height="339" border="0">

- [x] **Zadanie 2/3** : Dla podanych hashy określ typ wykorzystanego algorytmu hashującego, a następnie złam hasło metodą brute-force.

`hash-identifier`

9e66d646cfb6c84d06a42ee1975ffaae90352bd016da18f51721e2042d9067dcb120accc5741 05b43139b6c9c887dda8202eff20cc4b98bad7b3be1e471b3aa5

<img src="../_resources/lu14744uq4wag_tmp_ccf797dd3d7588f0.png" align="bottom" width="761" height="150" border="0">

Rezulatat :

<img src="../_resources/lu14744uq4wag_tmp_56a50497361c7814.png" align="bottom" width="763" height="266" border="0">

`Hash-identifier`

8a04bd2d079ee38f1af784317c4e2442625518780ccff3213feb2e207d2be42ca0760fd847618

4a004b71bcb5841db5cd0a546b9b8870f1cafee57991077c4a9

Rezultat: 

<img src="../_resources/lu14744uq4wag_tmp_e085035fff08c4af.png" align="bottom" width="1210" height="190" border="0">

<img src="../_resources/lu14744uq4wag_tmp_d52b245316856a0c.png" align="bottom" width="480" height="75" border="0">

Rezultat:

<img src="../_resources/lu14744uq4wag_tmp_e6a745e7e3e97868.png" align="bottom" width="1210" height="414" border="0">

- [x] **Zadanie 1 3/3**: Dla podanych hashy określ typ wykorzystanego algorytmu hashującego, a następnie złam hasło metodą brute-force.

`Hash-identifier`

44d9886c0a57ddbfdb31aa936bd498bf2ab70f741ee47047851e768db953fc4e43f92be953 e205a3d1b3ab752ed90379444b651b582b0bc209a739a624e109da

Rezulatat:

<img src="../_resources/lu14744uq4wag_tmp_f6674e0df4e19fca.png" align="bottom" width="948" height="310" border="0">

<img src="../_resources/lu14744uq4wag_tmp_3bd0118482576203.png" align="bottom" width="948" height="125" border="0">

- [x] **Zadanie 2**: Dla podanych hashy określ typ wykorzystanego algorytmu hashującego, a następnie złam hasło metodą słownikową.

`Hash-identifier:`

9fd8301ac24fb88e65d9d7cd1dd1b1ec

7f9a6871b86f40c330132c4fc42cda59

6104df369888589d6dbea304b59a32d4

276f8db0b86edaa7fc805516c852c889 

04dac8afe0ca501587bad66f6b5ce5ad

Rezultat:

<img src="../_resources/lu14744uq4wag_tmp_3a6f29340a2ac973.png" align="bottom" width="621" height="339" border="0">

**Wszystkie hashe MD5**

`hashcat -m0 -a 0 hash.txt /usr/share/wordlists/rockyou-50.txt`

Rezultat:

<img src="../_resources/lu14744uq4wag_tmp_f3986b6db8fe3203.png" align="bottom" width="733" height="473" border="0">

- [x]  **Zadanie 2/2 - Łamanie haseł** : Dla podanych hashy określ typ wykorzystanego algorytmu hashującego, a następnie złam hasło metodą słownikową.

Hash:

`Hash-identifier`

7ab6888935567386376037e042524d27fc8a24ef87b1944449f6a0179991dbdbc481e98db4 e70f6df0e04d1a69d8e7101d881379cf1966c992100389da7f3e9a

470c62e301c771f12d91a242efbd41c5e467cba7419c664f784dbc8a20820abaf6ed43e09b0c da994824f14425 db3e6d525a7aafa5d093a6a5f6bf7e3ec25dfa

<img src="../_resources/lu14744uq4wag_tmp_9cc90c2a5c8ebb86.png" align="bottom" width="1210" height="173" border="0">

`hashcat -m 1700 -a 0 hash.txt /usr/share/wordlists/rockyou-50.txt`

<img src="../_resources/lu14744uq4wag_tmp_ebc7b2c38f20149.png" align="bottom" width="810" height="288" border="0">

- [x] **Zadanie 3 - Analiza ruchu HTTP**
1. Rozpocznij monitorowanie ruchu sieciowego (narzędziem Wireshark).
2. W przeglądarce nawiąż połączenie z http://testphp.vulnweb.com/login.php 
3. Wykonaj próbę logowania (dowolne dane).
4. Odszukaj w zapisanym ruchu swoje dane logowania.

<img src="../_resources/lu14744uq4wag_tmp_6eb58083b3a4d0b7.png" align="bottom" width="1210" height="596" border="0"> <img src="../_resources/lu14744uq4wag_tmp_7614e8cdfe95cce6.png" align="bottom" width="1210" height="891" border="0">

- [x] **Zadanie 4: - Analiza ruchu SSH**
1. Rozpocznij monitorowanie ruchu sieciowego (narzędziem Wireshark).
2. Nawiąż połączenie pomiędzy Kalim a SDA po SSH.
3. Stwórz pliki sekret1.txt i sekret2.txt z tajnymi hasłami.
4. Edytuj konfigurację vsFTPd, żeby umożliwić wgrywanie plików po FTP.
5. Zakończ połączenie po SSH.
6. Spróbuj poszukać w zapisanym ruchu sieciowym zawartość plików sekret1.txt i sekret2.txt


Terminal:

```
ssh root@$IP

touch sekret1.txt

echo ‘tajnehaslo ‘ > sekret1.txt

touch sekret2.txt

echo ‘tajnehaslo2’ > sekret2.txt
```

<img src="../_resources/lu14744uq4wag_tmp_cb12f516c0d4d4ac.png" align="bottom" width="685" height="365" border="0">

`Sudo nano /etc/vsftpd.conf`

<img src="../_resources/lu14744uq4wag_tmp_4c0568f498db7a81.png" align="bottom" width="734" height="413" border="0">

Zapisujemy

Gotowe

Spróbuj poszukać w zapisanym ruchu sieciowym zawartość plików sekret1.txt i sekret2. <img src="../_resources/lu14744uq4wag_tmp_fa7cb6a6a981c35f.png" align="bottom" width="960" height="464" border="0">

- [x] **Zadanie 5 - Analiza ruchu FTP.**

```
[ftp://root:666@$IP](ftp://root:666@$IP)

mget dowolnyplik.txt

get sekret1.txt

get sekret2.txt
```

<img src="../_resources/lu14744uq4wag_tmp_1782c49449753789.png" align="bottom" width="1220" height="389" border="0">

<img src="../_resources/lu14744uq4wag_tmp_385276a5b295950b.png" align="bottom" width="960" height="456" border="0">