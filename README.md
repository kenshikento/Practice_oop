# Practice_oop
oop php
## About
Redoing this legendary project that i did couple years ago which is a pretty simple project based on ShopCart Application. Taking from some inspiration from Laravel i tried making it a bit more from scratch.

## Setting Up

### Requirements
- Use PHP 7.3

Entry Point too the program is Index.php no FE currently


## Running Tests [Unit Testing] 

### Customer Model [Mocking The Request With Symfony Request]
- Run `./vendor/bin/phpunit Test/Unit/Model/CustomerModelTest.php  ` to make sure you have the right database details
- Run `./vendor/bin/phpunit Test/Unit/Model/ProductModelTest.php  `

### TODO:
- Finish off Models 
- Add in necessary validation involved
- Remove all request data in model 
- create controllers and handle custom routing 
- Figure way to return data to controller to the view
- do simple front view