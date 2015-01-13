As described on the Symfony documentation
>The Console component eases the creation of beautiful and testable command line interfaces.
The Console component allows you to create command-line commands. Your console commands can be used for any recurring task, such as cronjobs, imports, or other batch jobs.  

http://symfony.com/doc/current/components/console/introduction.html

#### Project Goals:
* Take advantage of Symfony Console Component to generate command.
* Take advantage of Twig Component in order to render PHP, YML and other files.
* Take advantage of OOP and modern development practices.
* No plans to support previous versions of Drupal.

#### What is out of the box?
* Generators:
 * Generates module and info files.
 * Generates PSR-4 compliant directory structure for a module.
 * Register routes on YML files and map to controller and form PHP Classes.
 * Create classes adding namespaces, uses and also the extend and implements keywords when required.
 * Support adding services using Dependency Injection on class generation.

* Other commands:
 * List registered services on the service container
 * List registered routes on the routing system
 * Rebuilt routes

#### Who will benefit of using it?
* **Module Maintainers & Developers**  
  Create & Migrate contributed modules to Drupal 8.

* **Drupal Trainers & Consultors**  
  Train developers on Drupal 8.

* **Drupal Shops**  
  Reduce module development time for Drupal 8.