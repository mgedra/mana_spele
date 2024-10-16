Mērķis - izveidot karātavu spēli un izprast python pamata funkcijas.
Spēles gaita - spēlētājs izvēlas vienu burtu, mēģina uzminēt nejauši izvēlēto vārdu. Ja konkrētajā vārdā ir uzrakstītais vārds, tad tas tiks uzrādīts, ja nē, 
tad spēlētāja minējumu skaits samazināsies un attiecīgi parādīties karātavu grafikā.Ir iespējams spēlēt vēlreiz via beigt spēli.
Uzvaras nosacījumi - spēlētājs uzvar, ja uzmin konkrēto vārdu.

"Komponentes"
1.Vārda nejauša atlase - vārdu nejauši izvēles no vārdu_saraksts. Vārds tiek izvēlēts ar funkciju random.choice, kas importēta no import random.
2. Indformācijas atlasīšana - ar funkciju "karātavu_ spēle" izveidoti divi saraksti (uzminēts_pareizi un uzminēts_nepareizi), kā arī 
spēlētājam izveidoti 6 mēģinājumi, lai uzminētu pareizo vārdu. Funkcija "input" tiek izmantota, lai  iegūtu minējumu no  spēlētāja.
3.Attēlojums - ja spēlētājs uzmin burtu (burts in uzminēts_pareizi), tad svītriņa aizvietota ar attiecīgo burtu, ja spēlētājs min burtu nepareizi, tad tas 
tiek attēlots karātavu zīmējumā ("grafiks"). Savukārt, ja spēlētājam beidzas mēģinājumi (mēģinājumi == 0), tad spēle ir zaudēta.
4.Pārbaudīšana - "If output replace" pārbauda, vai spēlētājs ir uzminējis vārdu, salīdzinot ar izvēlēto vārdu. Ja vienādi, spēlētājs uzvar.
6.Spēles atkārtošana - funkcija "def spēlēt_atkal" dod iespēju spēlētājam spēlēt vēlreiz vai izbeigt spēli.

Papildus informācija redzamā arī kodā.
