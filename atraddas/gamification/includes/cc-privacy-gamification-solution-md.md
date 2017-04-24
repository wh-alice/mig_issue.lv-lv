Instalējot un iespējojot risinājumu [!INCLUDE[pn_gamification_solution](../../gamification/includes/pn-gamification-solution-md.md)], pakalpojumā [!INCLUDE[pn_azure_shortest](../../gamification/includes/pn-azure-shortest-md.md)] tiek saglabāta lietotāju kontu identifikatoru \(piemēram, vārda, uzvārda un e\-pasta adreses\) iespējošana, ļaujot autorizēties [!INCLUDE[pn_gamification_shortest](../Token/pn_gamification_shortest_md.md)] pakalpojumā, kurš tiek viesots pakalpojumā [!INCLUDE[pn_azure_shortest](../../gamification/includes/pn-azure-shortest-md.md)]. Tas attiecas uz visiem lietotājiem, kurus viņu administrators ir iespējojis [!INCLUDE[pn_gamification_shortest](../Token/pn_gamification_shortest_md.md)] pakalpojumā. Risinājums [!INCLUDE[pn_gamification_solution](../../gamification/includes/pn-gamification-solution-md.md)] datus par administratora konfigurētajiem Izpildes pamatrādītājiem \(Key Performance Indicator — KPI\) sūta uz [!INCLUDE[pn_azure_shortest](../../gamification/includes/pn-azure-shortest-md.md)] pakalpojumu, un šie dati tiek glabāti [!INCLUDE[pn_azure_shortest](../../gamification/includes/pn-azure-shortest-md.md)] strukturētajā krātuvē, kā arī BLOB krātuvē.  Katra lietotāja Avatārs, Pielāgotie apbalvojumi un Uzņēmuma logotips tiek saglabāti pakalpojumā [!INCLUDE[pn_azure_shortest](../../gamification/includes/pn-azure-shortest-md.md)], bet šī informācija netiek atgriezta uz [!INCLUDE[pn_crm_shortest](../../gamification/includes/pn-crm-shortest-md.md)].  
  
 Ņemiet vērā, ka administratori un pilnvarotie lietotāji var izmantot [!INCLUDE[pn_crm_shortest](../../gamification/includes/pn-crm-shortest-md.md)] datus, piemēram, tālruņu zvanus, iespējas un rezervētos ieņēmumus, lai konfigurētu spēlēs lietojamos KPI. [!INCLUDE[pn_gamification_shortest](../Token/pn_gamification_shortest_md.md)] pakalpojums neuzsāk nekādus izsaukumus uz [!INCLUDE[pn_crm_shortest](../../gamification/includes/pn-crm-shortest-md.md)], bet tikai atbild uz datiem, kuri plūst atpakaļ uz [!INCLUDE[pn_crm_shortest](../../gamification/includes/pn-crm-shortest-md.md)], piemēram, spēlēs, kur tiek lietoti KPI.  
  
 Administrators [!INCLUDE[pn_gamification_shortest](../Token/pn_gamification_shortest_md.md)] TV straumi var padarīt arī publisku. Spēļu vadītāji, kas iestata [!INCLUDE[pn_gamification_shortest](../Token/pn_gamification_shortest_md.md)] TV straumes un iespējo publisku straumēšanu, šādu TV straumi ļauj skatīt ikvienam interneta lietotājam, kam ir saite uz šo straumi.  
  
 Pēc tam administrators var arī noņemt [!INCLUDE[pn_gamification_shortest](../Token/pn_gamification_shortest_md.md)] funkcionalitāti, atinstalējot šo risinājumu no [!INCLUDE[pn_microsoftcrm](../../gamification/includes/pn-microsoftcrm-md.md)] organizācijas.  
  
 [!INCLUDE[pn_azure_shortest](../../gamification/includes/pn-azure-shortest-md.md)] komponenti un pakalpojumi, kas ir saistīti ar [!INCLUDE[pn_gamification_shortest](../Token/pn_gamification_shortest_md.md)], ir detalizēti aprakstīti tālāk norādītajās sadaļās.  
  
 [!INCLUDE[cc_privacy_note_azure_trust_center](../Token/cc_privacy_note_azure_trust_center_md.md)]  
  
 [Mākoņpakalpojumi](https://azure.microsoft.com/services/cloud-services/)  
  
 **Noformētāja pakalpojums \(tīmekļa loma\)**  
  
 Tas nodrošina vairākus tīmekļa pakalpojumus, ko lieto saziņai starp [!INCLUDE[pn_crm_shortest](../../gamification/includes/pn-crm-shortest-md.md)] organizāciju un vairāku nomnieku [!INCLUDE[pn_gamification_shortest](../Token/pn_gamification_shortest_md.md)][!INCLUDE[pn_azure_shortest](../../gamification/includes/pn-azure-shortest-md.md)] komponentiem.  Piemēram, Gamification dati tiek glabāti [!INCLUDE[pn_azure_shortest](../../gamification/includes/pn-azure-shortest-md.md)] SQL krātuvē.  Spēļu aprēķinos tiek lietota [!INCLUDE[pn_azure_service_bus](../Token/pn_azure_service_bus_md.md)] rinda, un tie tiek atgriezti punktu skaitīšanai un parādīšanai pakalpojumā.  Klientu un lietotāju augšupielādētie attēli tiek glabāti pakalpojumā [!INCLUDE[pn_azure_blob_storage](../Token/pn_azure_blob_storage_md.md)].  Visiem pieprasījumiem tiek veikta autentificēšana ar [!INCLUDE[pn_azure_active_directory](../../gamification/includes/pn-azure-active-directory-md.md)].  
  
 [Azure Key Vault](https://azure.microsoft.com/services/key-vault/)  
  
 Visiem pakalpojumiem konfigurācijas dati tiek glabāti pakalpojumā [!INCLUDE[pn_azure_key_vault](../Token/pn_azure_key_vault_md.md)].  
  
 [Azure SQL datu bāze](https://azure.microsoft.com/services/sql-database/)  
  
 [!INCLUDE[pn_gamification_shortest](../Token/pn_gamification_shortest_md.md)] lieto SQL [!INCLUDE[pn_azure_shortest](../../gamification/includes/pn-azure-shortest-md.md)], lai glabātu tālāk minētos datus.  
  
-   KPI dati  
  
-   Spēļu aprēķini  
  
-   Organizācijas \(nomnieka\) dati  
  
 [Azure BLOB krātuve](https://azure.microsoft.com/services/storage/)  
  
 Avatāri, uzņēmuma logotipi un citi klientu augšupielādētie attēli tiek glabāti pakalpojumā [!INCLUDE[pn_azure_blob_storage](../Token/pn_azure_blob_storage_md.md)].  
  
 [Azure satura piegādes tīkls \(Content Delivery Network — CDN\)](https://azure.microsoft.com/services/cdn/)\)  
  
 Risinājumā [!INCLUDE[pn_gamification_shortest](../Token/pn_gamification_shortest_md.md)] tiek izmantots [!INCLUDE[pn_azure_shortest](../../gamification/includes/pn-azure-shortest-md.md)] satura piegādes tīkls, lai izpildlaikam sniegtu statisko saturu, piemēram, attēlus \(tostarp augšupielādētos attēlus, piemēram, klientu logotipus\), [!INCLUDE[pn_JavaScript](../../gamification/includes/pn-javascript-md.md)] un CSS.  
  
 [Azure Active Directory](https://azure.microsoft.com/services/active-directory/)  
  
 Risinājums [!INCLUDE[pn_gamification_shortest](../Token/pn_gamification_shortest_md.md)] lieto [!INCLUDE[pn_azure_active_directory](../../gamification/includes/pn-azure-active-directory-md.md)], lai autentificētu lietotājus un noteiktu viņu piemērotību platformas lietošanai.