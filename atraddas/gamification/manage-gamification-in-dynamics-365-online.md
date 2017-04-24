---
title: "Pārvaldīt risinājumu Gamification pakalpojumā Microsoft Dynamics 365 (tiešsaistes) | Microsoft Docs"
ms.custom: ""
ms.date: "2017-04-06"
ms.reviewer: ""
ms.service: "gamification"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "get-started-article"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: cff88aa0-01a3-4cd7-adcf-8d4b8dec9f20
caps.latest.revision: 36
ms.author: "mhart"
manager: "sakudes"
caps.handback.revision: 30
---
# Pārvaldīt risinājumu Gamification pakalpojumā Microsoft Dynamics 365 (tiešsaistes)
[!INCLUDE[pn_gamification_solution](../gamification/includes/pn-gamification-solution-md.md)] iespējas ir risinājums pakalpojumam [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)], kas tiek viesots pakalpojumā [!INCLUDE[pn_microsoft_appsource](../gamification/includes/pn-microsoft-appsource-md.md)], kuru nepieciešams instalēt, pirms varat sākt šo iespēju izmantošanu, lai pārvaldītu [!INCLUDE[pn_gamification](../gamification/includes/pn-gamification-md.md)] spēles, KPI un spēlētājus.  
  
<a name="BKMK_prerequisistes"></a>   
## Priekšnosacījumi  
  
-   [!INCLUDE[cc_capabilities_require_online_8_1_0](../gamification/includes/cc-capabilities-require-online-8-1-0-md.md)]  
  
-   Lai piekļūtu [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)] pakalpojumam, lietotājiem ir jābūt piešķirtai [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)] licencei.  
  
-   Lietotājiem ir nepieciešams atjaunināts pārlūks.[!INCLUDE[proc_more_information](../gamification/includes/proc-more-information-md.md)][Browser and system requirements for Gamification](http://msdn.microsoft.com/lv-lv/b79dc1de-ca01-45f9-b5ac-123f3d26111b)  
  
<a name="BKMK_install"></a>   
## Instalēt risinājumu Gamification pakalpojumam [!INCLUDE[pn_crm_shortest](../gamification/includes/pn-crm-shortest-md.md)]  
 [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)] iespējas programmatūrā [!INCLUDE[pn_crm_shortest](../gamification/includes/pn-crm-shortest-md.md)] ir risinājums pakalpojumam [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)], kuru jūs instalējat no [Microsoft AppSource](https://go.microsoft.com/fwlink/p/?linkid=830919).  
  
#### Risinājuma instalēšana no AppSource  
  
1.  Vietnē [AppSource](https://go.microsoft.com/fwlink/p/?linkid=830919) atlasiet [!INCLUDE[pn_gamification_solution](../gamification/includes/pn-gamification-solution-md.md)].  
  
2.  Pierakstieties savā [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)] sistēmas administratora kontā, ja vēl to neesat izdarījis.  
  
3.  Lai sāktu risinājuma instalēšanu, noklikšķiniet uz **Iegūt**.  
  
4.  Lai pievienotu [!INCLUDE[pn_gamification_solution](../gamification/includes/pn-gamification-solution-md.md)] pakalpojumam [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)], pārskatiet atrunu un noteikumus un piekrītiet tiem.  
  
 Risinājuma instalēšana pakalpojumā [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)] var ilgt dažas minūtes.  
  
<a name="BKMK_users"></a>   
## Drošības loma KPI pārvaldnieks  
 Kad instalējat risinājumu [!INCLUDE[pn_gamification_solution](../gamification/includes/pn-gamification-solution-md.md)], tiek izveidota drošības loma **KPI pārvaldnieks**. Šo drošības lomu sistēmas administratori var piešķirt [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)] lietotājiem, kuriem vēlas ļaut izveidot KPI rīkam [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)] pakalpojumā [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)] un konfigurēt savienojumus starp [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)] un [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)].  
  
 Papildinformāciju par drošības lomām un atļaujām skatiet vietnē [TechNet: Drošības lomas un atļaujas](https://technet.microsoft.com/library/dn531090.aspx)  
  
 Papildinformāciju par KPI pakalpojumā [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)] skatiet vietnē [Configure KPIs in Dynamics 365](http://msdn.microsoft.com/lv-lv/b0c9af15-5cdf-4f8b-838c-49bf5dd50b6b).  
  
<a name="BKMK_authorize"></a>   
## Gamification aktivizēšana pakalpojumā [!INCLUDE[pn_crm_shortest](../gamification/includes/pn-crm-shortest-md.md)]  
 Lai varētu veikt [!INCLUDE[pn_gamification](../gamification/includes/pn-gamification-md.md)] un [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)] sinhronizēšanu, sistēmas administratoram ir jāizpilda iestatīšanas procedūra, iegūstot drošības atslēgu.  
  
#### Gamification tīmekļa lietojumprogrammas aktivizēšanai savai organizācijai  
  
1.  Pakalpojumā [!INCLUDE[pn_microsoftcrm](../gamification/includes/pn-microsoftcrm-md.md)] atveriet sadaļu **Iestatījumi** \> **Risinājumi** un pēc tam veiciet dubultklikšķi uz risinājuma **[!INCLUDE[pn_gamification_solution](../gamification/includes/pn-gamification-solution-md.md)]**.  
  
2.  Noklikšķiniet uz **Sākt aktivizēšanu** un pierakstieties ar saviem [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)] administratora akreditācijas datiem.  
  
3.  Piekrītiet atrunai un norādiet savas Gamification tīmekļa lietojumprogrammas instances **nosaukumu** un **atrašanās vietu**.  
  
4.  Lai sāktu aktivizēšanu un iegūtu drošības atslēgu, noklikšķiniet uz **Reģistrēt**.  
  
5.  Kopējiet **drošības atslēgu** un ielīmējiet to ievades lodziņā.  
  
6.  Noklikšķiniet uz **Autorizēt**, lai pabeigtu pakalpojuma [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)] un rīka [!INCLUDE[pn_gamification](../gamification/includes/pn-gamification-md.md)] savienojuma izveidi.  
  
 Jūs saņemsit e\-pasta ziņojumu ar papildinformāciju un varēsit piekļūt savas organizācijas [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)] instancei.  
  
 Turklāt sistēma izveido noklusējuma KPI kopu pakalpojumā [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)], lai jūs varētu ātri sākt darbu ar pirmo spēli.[!INCLUDE[proc_more_information](../gamification/includes/proc-more-information-md.md)][Konfigurēt un rediģēt KPI pakalpojumā Dynamics 365](http://msdn.microsoft.com/lv-lv/b0c9af15-5cdf-4f8b-838c-49bf5dd50b6b)  
  
 Lai pierakstītos kā pirmais komisārs, atveriet lapu [Pierakstīšanās rīkā Gamification](https://go.microsoft.com/fwlink/p/?linkid=830344).  
  
<a name="updateApp"></a>   
## Microsoft Dynamics 365 — Gamification atjaunināšana  
 Mēs rūpīgi strādājam, lai varētu nodrošināt labāko [!INCLUDE[pn_gamification](../gamification/includes/pn-gamification-md.md)] lietošanas pieredzi. Tas ietver risinājuma [!INCLUDE[pn_gamification_solution](../gamification/includes/pn-gamification-solution-md.md)] atjauninājumus. Sistēmas administrators var atjaunināt risinājumu tieši no pakalpojuma [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)].  
  
 Ja atjauninājums ir pieejams, lapā **Gamification iestatījumi** tiek parādīts paziņojums.  
  
#### Risinājuma Gamification for Dynamics 365 atjauninājums  
  
1.  Pierakstieties vietnē [https:\/\/portal.office.com](https://portal.office.com) ar savu globālā administratora vai [!INCLUDE[pn_microsoftcrm](../gamification/includes/pn-microsoftcrm-md.md)] sistēmas administratora akreditācijas datiem.  
  
2.  Noklikšķiniet uz **Administrēšanas centri** \> **Dynamics 365**.  
  
3.  Noklikšķiniet uz cilnes **Instances** un pēc tam atlasiet instanci, kurai ir pievienots šis risinājums.  
  
4.  Noklikšķiniet uz **Risinājumi**.  
  
5.  Atlasiet risinājumu, kuru vēlaties atjaunināt, un noklikšķiniet uz **Atjaunināt**.  
  
6.  Pakalpojumā [!INCLUDE[pn_microsoftcrm](../gamification/includes/pn-microsoftcrm-md.md)] atveriet sadaļu **Gamification** \> **Gamification iestatījumi** un noklikšķiniet uz **Atjaunināt programmu**, lai atjauninātu visas atkarības uz jaunāko versiju.  
  
    > [!IMPORTANT]
    >  Šī darbība ir nepieciešama, lai nodrošinātu visu sinhronizēšanas procesu darbību.  
  
 Sistēma lietos visas nepieciešamās izmaiņas un apstiprinās atjauninājumu, lai nodrošinātu netraucētu datu plūsmu.  
  
> [!NOTE]
>  Atjauninot risinājumu, katru reizi ir jāatkārto iepriekš minētās darbības.  
  
## Skatīt aktīvās spēles programmatūrā [!INCLUDE[pn_crm_shortest](../gamification/includes/pn-crm-shortest-md.md)]  
 Kad risinājums [!INCLUDE[pn_gamification_solution](../gamification/includes/pn-gamification-solution-md.md)] ir instalēts pakalpojumā [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)], varat skatīt informāciju par aktīvajām [!INCLUDE[pn_gamification](../gamification/includes/pn-gamification-md.md)] spēlēm.  
  
#### Skatīt aktīvās spēles  
  
1.  Pakalpojumā [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)] dodieties uz **Gamification** \> **Spēles**.  
  
2.  Spēļu sarakstā noklikšķiniet uz spēles, par kuru vēlaties redzēt informāciju.  
  
3.  Sadaļā **Informācija par spēli** atrodas pamatinformācija par spēli, piemēram, spēles nosaukums un tās sākuma un beigu datumi.  
  
     Sadaļā **Iestatījuma KPI** varat redzēt KPI un to iestatīšanas statusu atlasītajā spēlē. Papildinformāciju par KPI pakalpojumā [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)] skatiet vietnē [Configure KPIs in Dynamics 365](http://msdn.microsoft.com/lv-lv/b0c9af15-5cdf-4f8b-838c-49bf5dd50b6b).  
  
<a name="BKMK_privacy_notice"></a>   
## Paziņojums par konfidencialitāti  
 [!INCLUDE[cc_privacy_gamification_solution](../gamification/includes/cc-privacy-gamification-solution-md.md)]  
  
## System_CAPS_seeAlso  
 [For admins](http://msdn.microsoft.com/lv-lv/9cbe15a2-8239-4601-8af2-50a92c28f81f)   
 [Configure KPIs in Dynamics 365](http://msdn.microsoft.com/lv-lv/b0c9af15-5cdf-4f8b-838c-49bf5dd50b6b)   
 [Manage players and fans](http://msdn.microsoft.com/lv-lv/4df5e61b-0d7b-4cef-b741-14bed0637756)   
 [Run a game](http://msdn.microsoft.com/lv-lv/ec71f8e3-5cc9-4941-8067-5bf8e1081da9)   
 [Legal information about Microsoft Dynamics 365 \- Gamification](http://msdn.microsoft.com/lv-lv/98461a5f-9c04-4dcd-aaf1-44cc5706e419)