---
title: "Pārvaldīt spēlētājus un līdzjutējus rīkā Gamification | Microsoft Docs"
ms.custom: ""
ms.date: "2017-04-06"
ms.reviewer: ""
ms.service: "gamification"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: 4df5e61b-0d7b-4cef-b741-14bed0637756
caps.latest.revision: 34
ms.author: "mhart"
manager: "sakudes"
caps.handback.revision: 34
---
# Pārvaldīt spēlētājus un līdzjutējus rīkā Gamification
Kad iestatāt jaunu spēli, ir nepieciešams definēt, kuri lietotāji gaidāmajā [!INCLUDE[pn_gamification](../gamification/includes/pn-gamification-md.md)] spēlē ir spēlētāji un kuri — līdzjutēji.  
  
 **Spēlētāji** ir dalībnieki, kas spēlē sacenšas un saņem punktus par definēto KPI sasniegšanu.  
  
 **Līdzjutēji** ir cilvēki, kas aktīvajā spēlē nav spēlētāji — piemēram, uzņēmumu vadītāji, pārvaldnieki vai sekretāri —, bet [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)] spēlē piedalās, komplektējot komandu. Ja izpilddirektors iesaistās spēlē, komplektē kādu komandu un personiski seko līdzi spēlētāju statistikai, tas kalpo kā efektīva motivācija sasniegt vislabākos rezultātus\!  
  
<a name="registerPlayersFans"></a>   
## Importēt lietotājus no [!INCLUDE[pn_azure_active_directory](../gamification/includes/pn-azure-active-directory-md.md)]  
 Lietotāji no [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)] ir automātiski pieejami pakalpojumā [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)]. Komisāri no [!INCLUDE[pn_azure_active_directory](../gamification/includes/pn-azure-active-directory-md.md)] var importēt papildu lietotājus, kuriem nav piešķirta [!INCLUDE[pn_CRM_Online](../gamification/includes/pn-crm-online-md.md)] licence.  
  
#### Lietotāju importēšana no pakalpojuma [!INCLUDE[pn_microsoftcrm](../gamification/includes/pn-microsoftcrm-md.md)]  
  
1.  Risinājumā [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)] atveriet sadaļu **Lietotāji**.  
  
2.  Lapā **Lietotāju importēšana no Dynamics 365** katram lietotājam atlasiet **drošības lomu**.  
  
     Visticamāk, vairums importēto lietotāju būs lietotāji, kurus ir pievienojuši daži spēļu vadītāji. Papildinformāciju par pieejamajām drošības lomām un ar tām saistītajām atļaujām skatiet vietnē [](http://msdn.microsoft.com/lv-lv/afad369f-fe8a-4ced-8808-0af86ffad2c1).  
  
3.  Atzīmējiet izvēles rūtiņu tiem lietotājiem, kurus vēlaties importēt pakalpojumā [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)].  
  
4.  Lai sāktu importēšanas procesu, noklikšķiniet uz **Importēt atlasītos lietotājus**.  
  
    > [!NOTE]
    >  Atkarībā no importējamo lietotāju skaita tas var aizņemt pāris minūtes.  
  
 Importētie lietotāji tagad tiek rādīti risinājumā [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)], ja atverat lapu **Lietotāji**.  
  
 Tagad spēlētājiem varat rediģēt lomas atbilstoši savam plānotajam spēles iestatījumam.  
  
## System_CAPS_seeAlso  
 [For admins](http://msdn.microsoft.com/lv-lv/9cbe15a2-8239-4601-8af2-50a92c28f81f)   
 [Set up a game](http://msdn.microsoft.com/lv-lv/ec71f8e3-5cc9-4941-8067-5bf8e1081da9)