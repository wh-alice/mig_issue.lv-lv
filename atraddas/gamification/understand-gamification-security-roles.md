---
title: "Saprast Gamification drošības lomas | Microsoft Docs"
ms.custom: ""
ms.date: "2017-04-06"
ms.reviewer: ""
ms.service: "gamification"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: afad369f-fe8a-4ced-8808-0af86ffad2c1
caps.latest.revision: 15
ms.author: "mhart"
manager: "sakudes"
caps.handback.revision: 15
---
# Saprast Gamification drošības lomas
Administratori lietotājiem piešķir licences, lai viņiem sniegtu noteiktu programmu lietošanas atļaujas. Lai [!INCLUDE[pn_azure_active_directory](../gamification/includes/pn-azure-active-directory-md.md)] lietotājiem ļautu izmantot pakalpojumu [!INCLUDE[pn_gamification](../gamification/includes/pn-gamification-md.md)], ir nepieciešams viņiem piešķirt [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)] licenci. Pirmajam lietotājam, kam sistēmas administrators pakalpojumā [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)] piešķir drošības lomu KPI pārvaldnieks, ir nepieciešams iestatīt savienojumu starp [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)] un [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)]. Šis pats lietotājs pakalpojumā [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)] automātiski kļūst par pirmo Komisāru.  
  
## Pieejamās drošības lomas  
 Pakalpojumā [!INCLUDE[pn_gamification_subsequent](../gamification/includes/pn-gamification-subsequent-md.md)] atļaujas spēlēs tiek piešķirtas tikai ar drošības lomām. Pieejamo drošības lomu aprakstu skatiet sadaļā [Gamification Glossary](http://msdn.microsoft.com/lv-lv/10c6a538-985a-4ea2-b8d9-4efc67f7363f).  
  
 Papildinformāciju par pieejamo drošības lomu atļaujām skatiet nākamajā tabulā.  
  
|Atļauja|Komisārs|Spēles vadītājs|Lietotājs|  
|-------------|--------------|---------------------|---------------|  
|[Manage Gamification in Microsoft Dynamics 365](http://msdn.microsoft.com/lv-lv/cff88aa0-01a3-4cd7-adcf-8d4b8dec9f20)|Nē\*|Nē\*|Nē\*|  
|[Manage players and fans](http://msdn.microsoft.com/lv-lv/4df5e61b-0d7b-4cef-b741-14bed0637756)|Jā|Nē|Nē|  
|[Set up a game](http://msdn.microsoft.com/lv-lv/ec71f8e3-5cc9-4941-8067-5bf8e1081da9)|Jā|Jā|Nē|  
|[Configure and view Gamification Stream TV](http://msdn.microsoft.com/lv-lv/31346f85-42c9-4675-a8dd-062da7b94d4f)|Jā|Jā|Nē|  
|[Update scores using Excel Point Scoring](http://msdn.microsoft.com/lv-lv/1c58f29f-95df-4b2d-b0c4-56cea45bf196)|Jā|Jā|Nē|  
|[Schedule weekly or one\-time emails](http://msdn.microsoft.com/lv-lv/1e93e7a0-a0f6-4817-a361-a173df8fc74b)|Jā|Jā|Nē|  
|[Define weekly awards](http://msdn.microsoft.com/lv-lv/f34678ce-1037-4788-8394-f83866583c3c)|Jā|Jā|Nē|  
|[Manage a Fantasy Sports team](http://msdn.microsoft.com/lv-lv/ce3d8906-0c19-4aac-aba6-e9385a21f18d)|Nē|Jā\*\*|Jā|  
|[Post on Smack Talk](http://msdn.microsoft.com/lv-lv/958c8d0d-d57e-492b-bb83-1594c4d1a984)|Jā|Jā|Jā|  
|[View the leaderboard](http://msdn.microsoft.com/lv-lv/088b9a63-9cda-4e45-80b6-5482ac81147b)|Jā|Jā|Jā|  
  
 Nē\* \= pakalpojuma [!INCLUDE[pn_gamification_solution](../gamification/includes/pn-gamification-solution-md.md)] pārvaldīšanu regulē [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)] atļaujas, un šādas pārvaldīšanas nolūkos ir nepieciešama drošības loma KPI pārvaldnieks pakalpojumā [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)].  Ja meklējat informāciju par drošības lomu KPI pārvaldnieks pakalpojumā [!INCLUDE[pn_crm_online_subsequent](../gamification/includes/pn-crm-online-subsequent-md.md)], skatiet sadaļu [Configure KPIs in Dynamics 365](http://msdn.microsoft.com/lv-lv/b0c9af15-5cdf-4f8b-838c-49bf5dd50b6b) un [Manage Gamification in Microsoft Dynamics 365](http://msdn.microsoft.com/lv-lv/cff88aa0-01a3-4cd7-adcf-8d4b8dec9f20).  
  
 Jā\*\* \= Spēļu vadītāji var piedalīties kā līdzjutēji vai spēlētāji tādā spēlē, kuru viņi neadministrē.  
  
## System_CAPS_seeAlso  
 [For admins](http://msdn.microsoft.com/lv-lv/9cbe15a2-8239-4601-8af2-50a92c28f81f)   
 [For players and fans](http://msdn.microsoft.com/lv-lv/4aa06e76-6c87-424e-9068-58e706ddd7f9)   
 [Manage players and fans](http://msdn.microsoft.com/lv-lv/4df5e61b-0d7b-4cef-b741-14bed0637756)