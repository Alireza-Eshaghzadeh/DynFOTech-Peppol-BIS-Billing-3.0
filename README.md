# DynFOTech-Peppol-BIS-Billing-3.0
Configuration for e-Invoice with Peppol BIS Billing 3.0 format
Peppol configurations in Microsoft Dynamics 365 Finance and Operations are primarily tailored for generating e-invoices and ensuring compatibility with Peppol BIS Billing 3.0. These configurations are differentiated based on the following components:

-Peppol Project invoice

-Peppol Project credit note

-Peppol Sales invoice

-Peppol Sales credit note



To create a custom e-Invoice configuration in Microsoft Dynamics Finance & Operations, you can import a standard configuration from Microsoft repositories and create a derived version. You have the option to create or update the mapping. For more information, please refer to the following link: https://dynfotech.com/2021/10/17/e-invoice-in-d365fo-for-norway-part-2-configuration/ 

For this project, we will customize e-Invoice configurations derived from the standard version to streamline e-invoicing. This involves creating new mappings for sales and project invoices and facilitating validation of the e-invoice file through the access point. The specific tasks include:

-Implementing additional logic to generate e-invoice files that adhere to the validation requirements for Norwegian and Swedish legal entities.

-Modifying the mapping for company contact information

-Modifying the mapping for customer contact information

-Introducing conditions to customer reference and customer requisition to prevent the generation of empty values

-Including mappings for the delivery address, invoicing address, and primary address to enhance the comprehensiveness of the e-Invoice configurations.


