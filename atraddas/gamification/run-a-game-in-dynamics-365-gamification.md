---
title: "Palaist spēli rīkā Microsoft Dynamics 365&#160;— Gamification | Microsoft Docs"
ms.custom: ""
ms.date: "2017-04-06"
ms.reviewer: ""
ms.service: "gamification"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "get-started-article"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: ec71f8e3-5cc9-4941-8067-5bf8e1081da9
caps.latest.revision: 35
ms.author: "mhart"
manager: "sakudes"
caps.handback.revision: 35
---
# Palaist spēli rīkā Microsoft Dynamics 365&#160;— Gamification
Komisāri un spēļu vadītāji izveido un palaiž spēles, lai pakalpojuma [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)] izpildes pamatrādītājiem \(KPI\) piešķirtu spēles elementus un motivētu darbiniekus tiekties pēc labākiem rezultātiem. Izveidojiet spēles, kad vien vēlaties, un plānojiet to sākumu jebkurā turpmākajā laikā.  
  
 Pirms sākat spēles iestatīšanu risinājumā [!INCLUDE[pn_gamification](../gamification/includes/pn-gamification-md.md)], noteikti ir jāizpilda tālāk aprakstītie priekšnosacījumi.  
  
-   Pakalpojumā [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)] esat piešķīris drošības lomu Komisārs vai spēles vadītājs.  
  
-   Jūsu skolas vai organizācijas [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)] instancē ir instalēts un pareizi konfigurēts risinājums [!INCLUDE[pn_gamification_solution](../gamification/includes/pn-gamification-solution-md.md)].[!INCLUDE[proc_more_information](../gamification/includes/proc-more-information-md.md)][Manage Gamification in Microsoft Dynamics 365 Online](http://msdn.microsoft.com/lv-lv/cff88aa0-01a3-4cd7-adcf-8d4b8dec9f20)  
  
## Spēles iestatīšana  
 Iestatot spēli, komisārs vai spēles vadītājs rada gaidāmā konkursa pamatu. Velties kādu brīdi nākamo nodaļu izlasīšanai, kur sniegtas detalizētas instrukcijas.  
  
<a name="step1"></a>   
### Spēles pamata opcijas  
 Spēles iestatīšanas procedūras pirmais posms ir pamatinformācijas norādīšana spēlei, kuru veidojat. Risinājumā [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)] atveriet sadaļu **Spēles** \> **Spēles iestatīšana**, lai iestatītu jaunu spēli, vai sadaļu **Spēles** \> **Spēles**, lai rediģētu esošās spēles.  
  
##### Jaunas spēles izveide  
  
1.  Norādiet spēles **nosaukumu**.  
  
2.  Atlasiet vērtību vienumam **Spēles modelis**.[!INCLUDE[proc_more_information](../gamification/includes/proc-more-information-md.md)][Spēļu modeļi un sporta tēmas](http://msdn.microsoft.com/lv-lv/f37b3fc7-2c99-46ac-aa75-526baac4d434)  
  
     Papildinformāciju par TV straumes iestatīšanu skatiet vietnē [Configure and view Gamification Stream TV](http://msdn.microsoft.com/lv-lv/31346f85-42c9-4675-a8dd-062da7b94d4f).  
  
3.  Atlasiet to vienumu **Sporta tēma**, kuru vēlaties lietot šai spēlei.  
  
4.  Izvēlieties, vai spēlē vēlaties lietot KPI rādītājus **Faktiskie** vai **Mērķi**.[!INCLUDE[proc_more_information](../gamification/includes/proc-more-information-md.md)][Izpildes pamatrādītāji (KPI)](http://msdn.microsoft.com/lv-lv/f37b3fc7-2c99-46ac-aa75-526baac4d434)  
  
5.  Lai norādītu, cik bieži spēlētāji var mainīt savas komandas, iestatiet vienumu **Komplektēšanas biežums**. Vislabākajā gadījumā jūs komplektēšanas biežumu iestatāt uz reizi nedēļā, lai spēlētājiem nodrošinātu elastīgas iespējas aizstāt savā komandas dalībnieku sarakstā iekļautos spēlētājus, ja spēlētāji tiek noņemti no spēles vai izmanto prombūtnes laiku.  
  
6.  Spēlei iestatiet vērtības **Sākuma datums** un **Beigu datums**. Spēles darbojas pēc nedēļas grafika, no pirmdienas līdz svētdienai. Sākuma un beigu datumi ir jāiestata atbilstoši, lai neveidotos spēļu periodi, kas ir mazāki par nedēļu.  
  
    > [!TIP]
    >  Lai spēlētājiem vairotu interesi piedalīties, ieteicams izmantot spēles ilgumu no 2 līdz 6 mēnešiem. Ir pierādīts, ka īsākās spēlēs cilvēkiem ir grūtāk iesaistīties spēlē, bet garākām spēlēm ir grūtāk sekot līdzi.  
  
7.  Spēles iestatīšanas galvenē noklikšķiniet uz **1**, lai pārietu uz nākamo darbību.  
  
<a name="step2"></a>   
### KPI tipi un lietotāju lomas  
 KPI ir spēles atslēga. Tie ir uz [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)] datiem balstīti rādītāji, kas automātiski tiek sinhronizēti ar [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)], un tie regulē spēlētājiem piešķirtos punktus. KPI ir jāiestata iknedēļas mērķiem.  
  
> [!TIP]
>  -   Attiecībā uz KPI **lietojiet aprakstošus nosaukumus**, lai spēlētāji varētu saprast, kā iespējams nopelnīt punktus.  
> -   **Ieteicamais KPI skaits katrā spēlē ir no 3 līdz 5.** Ja tiek izmantots pārāk liels KPI skaits, spēlētāji koncentrējas uz dažiem rādītājiem, kamēr pārējie rādītāji tiek atstāti novārtā.  Taču ir nepieciešami arī pietiekami daudzi KPI, lai visu līmeņu spēlētāji justu, ka arī viņi var sniegt kādu ieguldījumu un gūt panākumus.  Ieteicams iekļaut gan no rezultātiem, gan no uzvedības atkarīgus KPI.  No rezultātiem atkarīgi KPI ir, piemēram, ieņēmumu summa, % no kvotas un noslēgtie pārdošanas darījumi. No uzvedības atkarīgo rādītāju klāstā ietilpst tādi faktori kā veikto zvanu skaits, norunāto tikšanos skaits un noturētu demonstrāciju skaits.  Taču savai spēlei varat definēt, cik vien KPI vēlaties.  
> -   **Attiecībā uz KPI lietojiet mazus skaitus.** Piemēram, piešķiriet 1 punktu par katru jauno interesentu, nevis 100 punktus par katriem 5 interesentiem, lai neveidotos pārāk liela starpība starp pirmo un otro vietu. Ja nākamās pozīcijas sasniegšanai ir nepieciešams iespaidīgs punktu skaits, spēlētājiem var rasties sajūta, ka viņi jau ir zaudējuši.  
> -   **Attiecībā uz KPI norādiet minimālo un maksimālo robežvērtību**, lai nepieļautu, ka atsevišķa pārstāvja sasniegums viņu padara par visa spēles laukuma līderi.  Minimāla robežvērtība definē minimālo KPI skaitu, kāds ir nepieciešams, lai spēlētājs saņemtu punktus. Maksimāla robežvērtība definē KPI skaita augšējo ierobežojumu, kas spēlētājiem ģenerē punktus. Piemēram, ja attiecībā uz tālruņa zvanu izsekošanas KPI minimālo robežvērtību iestatāt uz 5 un maksimālo robežvērtību iestatāt uz 50, tad spēlētājiem ir jāsasniedz vismaz 5 tālruņa zvani, lai saņemtu punktu.  Maksimālā robežvērtība nosaka, ka spēlētāji saņems par 50 zvanu veikšanu noteikto punktu skaitu arī tad, ja būs veikuši 80 zvanus.   Minimālās un maksimālās robežvērtības spēlei katru nedēļu tiek atiestatītas.  
  
 Papildinformāciju par KPI skatiet vietnē [Izpildes pamatrādītāji (KPI)](http://msdn.microsoft.com/lv-lv/f37b3fc7-2c99-46ac-aa75-526baac4d434).  
  
##### Atlasīt KPI  
  
1.  Spēles iestatīšanas procedūras 2. darbībā nolaižamajā izvēlnē izvēlieties no pieejamajiem KPI. KPI tiek veidoti pakalpojumā [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)], un tos veido lietotājs ar drošības lomu KPI pārvaldnieks.[!INCLUDE[proc_more_information](../gamification/includes/proc-more-information-md.md)][Configure KPIs in Dynamics 365](http://msdn.microsoft.com/lv-lv/b0c9af15-5cdf-4f8b-838c-49bf5dd50b6b)  
  
2.  Ja vēlaties, norādiet citādu \(no spēles atkarīgu\) KPI nosaukumu.  
  
3.  Nolaižamajā sarakstā metodi attiecīgā KPI mērīšanai. Varat izvēlēties metodi **Skaits**, **Ieņēmumi vai summa**, **Procenti** un **Kvotas procenti**.  
  
     Ja vienam no saviem KPI atlasāt metodi **Kvotas procenti**, tad spēles iestatīšanas procedūrai tiek pievienota jauna darbība, kur jums ir jādefinē kvotas katram spēlētājam.   Novērojumi liecina, ka iestatot **Noklusējums** nevis **Lineārs**, spēlētājiem ir vienkāršāk sekot līdzi.  
  
     [!INCLUDE[proc_more_information](../gamification/includes/proc-more-information-md.md)] [Spēles kvotas](#step5)  
  
4.  Definējiet, cik punktus spēlētāji saņem, sasniedzot kādu KPI.  
  
     Lai iestatītu spēlētājam sasniedzamu iknedēļas mērķi, izveidojiet aptuvenu KPI un pēc tam spēles iestatīšanas procedūras 2. darbībā vārdus **ik pēc** nomainiet uz **pie**.  
  
5.  Ja vēlaties, iestatiet šī KPI **minimālo robežvērtību** un **maksimālo robežvērtību**.  
  
6.  Iepriekš aprakstītās darbības atkārtojiet visiem KPI, ko plānojat izmantot spēlē.  
  
7.  Ja vēlaties, noteiktu KPI punktu skaitīšanai varat lietot Excel punktu skaitīšanu.[!INCLUDE[proc_more_information](../gamification/includes/proc-more-information-md.md)][Update scores using Excel Point Scoring](http://msdn.microsoft.com/lv-lv/1c58f29f-95df-4b2d-b0c4-56cea45bf196)  
  
8.  Spēles iestatīšanas galvenē noklikšķiniet uz **2**, la pārietu uz nākamo darbību.  
  
> [!IMPORTANT]
>  Kad aktīvai spēlei noņemat kādu KPI, lietotājam ar drošības lomu KPI pārvaldnieks pakalpojumā [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)] ir jānoklikšķina uz Atsvaidzināt datus, lai atsvaidzinātu pakalpojumā [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)] rādītos datus.  
  
<a name="step5"></a>   
#### Spēles kvotas  
 Ja spēles iestatīšanas procedūras 2. darbībā izveidojāt KPI Kvotas procenti, jums spēlētājiem ir jādefinē spēles kvotas. Ja vēlaties, visiem spēlētājiem attiecībā uz visiem vai atsevišķiem KPI varat iestatīt kvotu uz to pašu vērtību.  
  
> [!NOTE]
>  Katrā spēlē varat izmantot līdz četriem KPI, kam tiek lietotas kvotas.  
  
 Lai pārietu uz nākamo darbību, noklikšķiniet uz **Tālāk**.  
  
<a name="step3"></a>   
### Spēlētāji un līdzjutēji  
 Atkarībā no atlasītās sporta tēmas tagad spēlētājus varat piešķirt pozīcijām un nākamajā darbībā varat atlasīt līdzjutējus dalībai spēlē.  
  
 Lai spēlētājam piešķirtu kādu pozīciju, noklikšķiniet uz pozīcijas un atzīmējiet to spēlētāju izvēles rūtiņas, kuriem vēlaties piešķirt pozīciju.  
  
> [!TIP]
>  Nodrošiniet, lai spēlētāji būtu vienmērīgi izplatīti pa pozīcijām un tādējādi nepieļautu, ka kāds savā komandā komplektē visus vadošos spēlētājus.  
  
 Lai spēlei pievienotu līdzjutējus, atlasiet tos sarakstā 3. darbībā.  
  
 Noklikšķiniet uz **4**, lai pārietu uz nākamo darbību.  
  
<a name="step4"></a>   
### Apbalvojumi un balvas  
 Šajā darbībā varat definēt dažādos apbalvojumus un balvas visai spēlei.[!INCLUDE[proc_more_information](../gamification/includes/proc-more-information-md.md)][Apbalvojumi un balvas](http://msdn.microsoft.com/lv-lv/f37b3fc7-2c99-46ac-aa75-526baac4d434)  
  
 Papildus spēles apbalvojumiem varat iestatīt iknedēļas apbalvojumus.[!INCLUDE[proc_more_information](../gamification/includes/proc-more-information-md.md)][Define weekly awards](http://msdn.microsoft.com/lv-lv/f34678ce-1037-4788-8394-f83866583c3c)  
  
 Lai pabeigtu spēles iestatīšanu, saviem definētajiem datumiem noklikšķiniet uz **Sākt spēli**. Spēli varat arī saglabāt un pirms tās sākšanas vēl precizēt savus iestatījumus.  
  
 Pēc spēles aktivizēšanas un pirms spēles sākuma datuma varat mainīt tikai KPI, spēles apbalvojumus un spēlētāju spēles kvotas, bet nevarat pievienot jaunu KPI Kvotas procenti. Spēles sākuma datumā vai pēc tā joprojām varat mainīt spēles apbalvojumus un spēlētāju spēles kvotas.  
  
> [!NOTE]
>  Pēc spēles aktivizēšanas jebkurā laikā varat pievienot vai noņemt spēlētājus vai līdzjutējus, izmantojot pogu **Pievienot vai noņemt spēlētājus vai līdzjutējus** lapā **Spēles**, kura kļūst redzama pēc spēles aktivizēšanas. Ja spēlētājs vairs neietilpst organizācijā, deaktivizējiet šo spēlētāju lapā **Spēlētāji**. Ja darbināt spēli, kurā tiek izmantotas fantāzijas komandas, spēlētāju vispirms ir nepieciešams deaktivizēt pakalpojumā [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)], lai fiksētu attiecīgā spēlētāja punktu skaitu un komandas nezaudētu punktus par pašreizējo un iepriekšējiem spēles periodiem.  
  
 Neaizmirstiet pabeigt spēli, kad ir sasniegts spēles beigu datums. Šī darbība ir svarīga, lai nodrošinātu, ka spēlētājiem tiek piešķirtas balvas.[!INCLUDE[proc_more_information](../gamification/includes/proc-more-information-md.md)][Pabeigt spēli](#completeGame)  
  
<a name="BKMK_runGame"></a>   
## Palaist spēli un izmantot visjaunākos rezultātus  
 Aktīvas spēles laikā ir jānodrošina, lai spēlētāji un līdzjutēji nezaudētu interesi. Ja noteiktus KPI atjaunināt manuāli, jūs izmantojat līdzekli Excel punktu skaitīšana.[!INCLUDE[proc_more_information](../gamification/includes/proc-more-information-md.md)][Update scores using Excel Point Scoring](http://msdn.microsoft.com/lv-lv/1c58f29f-95df-4b2d-b0c4-56cea45bf196)  
  
> [!IMPORTANT]
>  Kad rediģējat aktīvu spēli un noņemat kādu KPI vai maināt aktīvos spēlētājus, lietotājam ar drošības lomu KPI pārvaldnieks pakalpojumā [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)] ir jānoklikšķina uz Atsvaidzināt datus, lai atsvaidzinātu pakalpojumā [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)] rādītos datus.  
  
> [!TIP]
>  -   Apsveriet iespēju birojā uzstādīt televizoru, lai rādītu līderu tabulu un aizvainojumu paneļa paziņojumus.[!INCLUDE[proc_more_information](../gamification/includes/proc-more-information-md.md)][Configure and view Gamification Stream TV](http://msdn.microsoft.com/lv-lv/31346f85-42c9-4675-a8dd-062da7b94d4f)  
> -   Sūtiet iknedēļas e\-pasta viļņus visiem dalībniekiem, lai informētu par bara vadoņiem pašreizējā spēlē un spēlētājus motivētu sasniegt vislabākos rezultātus.[!INCLUDE[proc_more_information](../gamification/includes/proc-more-information-md.md)][Schedule weekly or one\-time emails](http://msdn.microsoft.com/lv-lv/1e93e7a0-a0f6-4817-a361-a173df8fc74b)  
  
<a name="completeGame"></a>   
## Pabeigt spēli  
 Pēc spēles beigu datuma spēles vadītājam vai Komisāram ir jāizpilda punktu skaitīšana pēdējam spēles periodam. Ja risinājumu [!INCLUDE[pn_gamification](../gamification/includes/pn-gamification-md.md)] integrējat pakalpojumā [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)], viņiem ir arī jānodrošina, ka visi dati ir pareizi, lai KPI atainotu pareizās vērtības un spēlētājiem tiktu piešķirts pareizais galīgais punktu skaits un balvas. Pabeidziet spēli manuāli vai ļaujiet spēlei automātiski beigties 30 dienas pēc spēles beigu datuma.  
  
#### Pabeigt spēli manuāli  
  
1.  Risinājumā [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)] dodieties uz **Spēles**.  
  
2.  Sarakstā **Aktīvās spēles** noklikšķiniet uz pogas **Spēle pabeigta** tai spēlei, kuru vēlaties pabeigt.  
  
    > [!NOTE]
    >  Ja nepieciešams veikt korekcijas jau pabeigtā spēlē, sarakstā **Pabeigtās spēles** noklikšķiniet uz pogas **Padarīt aktīvu**.  
  
## System_CAPS_seeAlso  
 [For admins](http://msdn.microsoft.com/lv-lv/9cbe15a2-8239-4601-8af2-50a92c28f81f)   
 [Manage Gamification in Microsoft Dynamics 365](http://msdn.microsoft.com/lv-lv/cff88aa0-01a3-4cd7-adcf-8d4b8dec9f20)   
 [Manage players and fans in Gamification](http://msdn.microsoft.com/lv-lv/4df5e61b-0d7b-4cef-b741-14bed0637756)