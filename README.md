# Item Catalog

### Project Overview
To develop a RESTful web application that provides CRUD (Create, Read, Update, Delete) operations to a user. User will be authenticated via gmail using OAuth 2.0 protocol . Registered users will have the ability to create, edit and delete only their own items.

### What Will I Learn?
  * Develop a RESTful web application using the Python framework Flask
  * Implementing CRUD (create, read, update and delete) operations.
  * Implementing third-party OAuth authentication.
  * JSON Endpoints.
  
### How to Run?

#### PreRequisites
  * [Python ~2.7](https://www.python.org/)
  * [Vagrant](https://www.vagrantup.com/)
  * [VirtualBox](https://www.virtualbox.org/)
  
#### Setup Project:
  1. Install Vagrant and VirtualBox
  2. Download or Clone [fullstack-nanodegree-vm](https://github.com/udacity/fullstack-nanodegree-vm) repository.
  3. Find the catalog folder and replace it with the the catalog folder of the zipped file.
 
#### Launch Project
  1. Launch the Vagrant VM using command:
  
  ```
    $ vagrant up
  ```

  2. Login into the VM using command:
  
  ```
    $ vagrant ssh
  ```

  3. Run your application within the VM
  
  ```
    $ python /vagrant/catalog/dbp.py
  ```

  4. Access and test your application by visiting (http://localhost:5000).
