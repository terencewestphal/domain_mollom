# Domain Mollom 6.x-1.0
Domain Mollom extension allows each domain to have it's own public and private Mollom keys.

**Description**  
By default Mollom stores the Public and the Private key inside the system variable table. And since its generally not such a good idea to prefix the variable's table with the Domain Prefix module for additional domains, its unfortunately not possible to have different "Public" and "Private" keys for your Mollom install. With this small module you can without hacking Mollom or the Domain_Conf module. 

**Requirements**   
* [Drupal 6.x](https://www.drupal.org/project/drupal)
* [Domain Access 6.x-2.x](https://www.drupal.org/project/domain) *(Domain Configuration module)*
* [Mollom 6.x](https://www.drupal.org/project/mollom)

**How to use**  
You can edit these keys in the domain batch page per domain (admin/build/domain/batch). The keys for the default domain can be set at the standard admin location (admin/settings/mollom).
