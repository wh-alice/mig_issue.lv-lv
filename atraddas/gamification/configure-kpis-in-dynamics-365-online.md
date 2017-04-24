---
title: "Konfigurēt KPI pakalpojumā Dynamics&#160;365 (tiešsaistes) | Microsoft Docs"
ms.custom: ""
ms.date: "2017-04-06"
ms.reviewer: ""
ms.service: "gamification"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "get-started-article"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: b0c9af15-5cdf-4f8b-838c-49bf5dd50b6b
caps.latest.revision: 29
ms.author: "mhart"
manager: "sakudes"
caps.handback.revision: 20
---
# Konfigurēt KPI pakalpojumā Dynamics&#160;365 (tiešsaistes)
Punktu skaits un sasniegumi spēlēs ir atkarīgi no pakalpojumā [!INCLUDE[pn_gamification](../gamification/includes/pn-gamification-md.md)] definētajiem KPI. Šī procedūra sastāv no diviem posmiem. Vispirms jums ir jāizveido KPI pakalpojumā [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)], un pēc tam tos varat izvēlēties un konfigurēt pakalpojumā [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)], kad iestatāt jaunu spēli.  
  
 Papildinformāciju par KPI iestatīšanu pakalpojumā [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)] skatiet vietnē [KPI tipi un lietotāju lomas](http://msdn.microsoft.com/lv-lv/ec71f8e3-5cc9-4941-8067-5bf8e1081da9). Pamatinformāciju par KPI skatiet vietnē [Izpildes pamatrādītāji (KPI)](http://msdn.microsoft.com/lv-lv/f37b3fc7-2c99-46ac-aa75-526baac4d434).  
  
<a name="BKMK_createKPI"></a>   
## Izveidot KPI pakalpojumā Gamification  
 Kad spēli iestatāt pirmo reizi, spēles iestatīšanas procedūras 2. darbībā jums tiek prasīts definēt šīs spēles KPI.  
  
 Pakalpojumā [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)] definētie KPI kļūst pieejami, kad iestatāt spēli un sinhronizējat datus no [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)]. Pamatinformāciju par KPI skatiet vietnē [Izpildes pamatrādītāji (KPI)](http://msdn.microsoft.com/lv-lv/f37b3fc7-2c99-46ac-aa75-526baac4d434).  
  
<a name="BKMK_ConfigureKPI"></a>   
## Konfigurēt un rediģēt KPI pakalpojumā Dynamics 365  
 Konfigurējiet KPI informāciju pakalpojumā [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)], lai tos atlasītu jaunam konkursam risinājumā [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)]. Kad instalējat risinājumu [!INCLUDE[pn_gamification_solution](../gamification/includes/pn-gamification-solution-md.md)], sistēma izveido noklusējuma KPI kopu. Tikai KPI īpašnieks var mainīt tā vērtības. Ja sistēma izveidoja KPI, jums tas ir jāpiešķir īpašniekam, pirms būs iespējams mainīt tā vērtības.  
  
#### KPI konfigurēšana  
  
1.  Pakalpojumā [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)] atveriet sadaļu **[!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)]** \> **KPI**.  
  
2.  Nolaižamajā sarakstā atlasiet vienumu **JAUNS**.  
  
3.  Sadaļā **Iestatījuma KPI** noklikšķiniet uz KPI, kuru vēlaties konfigurēt.  
  
     Jūsu konfigurētajiem KPI statuss ir **Iestatīts**, bet KPI, kas vēl gaida konfigurēšanu, tiek rādīti kā **Nav iestatīts**.  
  
4.  Sadaļā **KPI parametru iestatīšana** vienumam **Tips** atlasiet objekta tipu, kuru vēlaties izmantot sava KPI pamatā.  
  
5.  Definējiet, kuram datu laukam tiks piešķirti punkti.  
  
    > [!TIP]
    >  Izvēloties datu laukus, esiet piesardzīgs. Ja izmantojat datu lauku, kura vērtība dienā vairākas reizes var mainīties, piemēram, **Modificēšanas datums** vai **Modificēja**, piešķirtie punkti var tikt noņemti vienam spēlētājam un piešķirti citam vai var mainīties punktu piešķiršanas datums.  
    >   
    >  Piemērs. Pieņemsim, ka izveidojat KPI, pamatojoties uz interesenta entītiju, kurā kā datuma laiks tiek izmantots lauks **Modificēšanas datums**, bet lauks **Modificēja** — kā lauks, kurā noradīts lietotājs, kurš piešķir punktus. Ja lietotājs izveidoja jaunu interesentu pirmdien, sistēma pirmdien piešķirs punktus šim lietotājam. Ja šis interesents tiek atjaunināts otrdien, sistēma noņems lietotāja punktus no pirmdienas un pārvietos tos uz otrdienu. Tādējādi var tikt mainīti dati par to, cik daudz punktu spēlētājs iegūst noteiktajā spēles periodā.  
    >   
    >  Ja jums ir izveidots sistēmas uzdevums, kas katru dienu atjaunina interesentu ierakstus, lietojot sistēmas kontu, visi spēlētāju iegūtie punkti tiks noņemti pēc uzdevuma izpildes, jo sistēma mainīja interesentu. Ja cits lietotājs atjaunina šo interesenta ierakstu, notiek tas pats.  
  
6.  Atlasiet, kuriem lietotājiem tiek piešķirti punkti no attiecīgā KPI.  
  
     Turot nospiestu taustiņu Ctrl, varat atlasīt vairākus lietotājus.  
  
7.  Ja vēlaties, attiecīgajam KPI varat iestatīt papildu vaicājumu parametrus, izveidojot skatu **Saglabātais skats**.  
  
     Dodieties uz **Detalizētā atrašana**, atlasiet laukus, pēc kuriem vēlaties filtrēt, un pēc tam noklikšķiniet uz **Saglabāt kā jaunu skatu**. Pēc tam varat rediģēt šo KPI, un lai veiktās izmaiņas stātos spēkā, atlasiet saglabāto skatu un noklikšķiniet uz **Saglabāt**.  
  
     Piemēram, ja punktus vēlaties piešķirt tikai par tikšanos saistībā ar konkrētu produktu, tad tikšanās aprakstam varat pievienot produkta nosaukumu un pievienot vaicājuma parametru, lai punktu skaitīšanai tikšanos atlasītu tikai tad, ja laukā **Apraksts** ir ietverts produkta nosaukums.  
  
    > [!NOTE]
    >  [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)] neatbalsta saglabātos skatus, kuru filtros vai kolonnās ir saites uz entītijām.  
  
8.  Lai jūsu konfigurācija stāstos spēkā, noklikšķiniet uz **Saglabāt**.  
  
 Pēc visu nepieciešamo KPI iestatīšanas pakalpojums [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)] sinhronizē datus ar [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)], kad sākat spēli.  
  
 Ja KPI punktu skaitīšanu vēlaties veikt manuāli, varat lietot Excel punktu skaitīšanu.[!INCLUDE[proc_more_information](../gamification/includes/proc-more-information-md.md)][Update scores using Excel Point Scoring](http://msdn.microsoft.com/lv-lv/1c58f29f-95df-4b2d-b0c4-56cea45bf196)  
  
#### Rediģēt KPI  
  
1.  Pakalpojumā [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)] dodieties uz **[!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)]** \> **KPI**.  
  
2.  Noklikšķiniet uz KPI, kuru vēlaties rediģēt.  
  
3.  Sadaļā **KPI parametri** noklikšķiniet uz **Rediģēt**.  
  
4.  Mainiet KPI parametrus atbilstoši savām prasībām.  
  
5.  Lai lietotu veiktās izmaiņas, noklikšķiniet uz **Saglabāt**.  
  
> [!NOTE]
>  Pirms varat rediģēt KPI, kurš tika automātiski izveidots, instalējot [!INCLUDE[pn_gamification_solution](../gamification/includes/pn-gamification-solution-md.md)], tam ir jāpiešķir īpašnieks. Tikai KPI īpašnieks var mainīt KPI vērtības.  
  
## System_CAPS_seeAlso  
 [For admins](http://msdn.microsoft.com/lv-lv/9cbe15a2-8239-4601-8af2-50a92c28f81f)   
 [Run a game](http://msdn.microsoft.com/lv-lv/ec71f8e3-5cc9-4941-8067-5bf8e1081da9)