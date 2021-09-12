# Management Module
### Sections:
* [Catalog](#catalog)
* [Locations](#locations)
* [Access Control](#access-control)
* [Import Data](#import-data)
* [Languages](#languages)
* [Currencies](#currencies)
* [Audit Log](#audit-log)
* [Settings](#settings)
* [Lookups](#lookups)

# Catalog
* [Brands](##brands)
* [Categories](##categories)
* [Items](##items)

## Brands
Brands are stored as tables with the following fields:
* ID 
  * An automatically-generated unique identifier for the brand
* Name 
  * The name of the brand 
  * Entered by the user 
  * Can be entered in multiple languages
* Items Count
  * Number of items holding this brand 
## Categories
Categories are stored as tables with the following fields:
* Name 
  * The name of the brand 
  * Entered by the user 
  * Can be entered in multiple languages
* Creation Time
  * Number of items holding this brand 

## Items
Items are stored as tables with the following fields:
* ID 
  * An automatically-generated unique identifier for the brand
* Name 
  * The name of the brand 
  * Entered by the user 
  * Can be entered in multiple languages
* Items Count
  * Number of items holding this brand 

# Locations
* [Countries](##countries)
* [Cities](##cities)
* [Regions](##regions)

## Countries
Brands are stored as tables with the following fields:
* ID 
  * An automatically-generated unique identifier for the brand
* Name 
  * The name of the brand 
  * Entered by the user 
  * Can be entered in multiple languages
 
## Cities
Categories are stored as tables with the following fields:
* Name 
  * The name of the brand 
  * Entered by the user 
  * Can be entered in multiple languages
* Country
  * Number of items holding this brand 

## Regions
Items are stored as tables with the following fields:
* ID 
  * An automatically-generated unique identifier for the brand
* Name 
  * The name of the brand 
  * Entered by the user 
  * Can be entered in multiple languages
* City
  * Number of items holding this brand
* Country
  * Number of items holding this brand 

# Access Control
* [Users](##users)
* [Roles](##roles)

## Users
Brands are stored as tables with the following fields:
* ID 
  * An automatically-generated unique identifier for the brand
* Name 
  * The name of the brand 
  * Entered by the user 
  * Can be entered in multiple languages
 
## Roles
Categories are stored as tables with the following fields:
* Name 
  * The name of the brand 
  * Entered by the user 
  * Can be entered in multiple languages
* Country
  * Number of items holding this brand 

# Import Data
* Employees 
* Suppliers

# Languages
* ID 
* Name
* Display Name
* Icon
* Is Disabled

# Currencies
* Code
* Symbol
* Display Precision
* Exchange Rate
* Is Based Currency

# Audit Log
* ID
* Username
* Time
* IP
* Service
* Method
* Pass

# Settings
* [Application](##application)
* [Users](##users)
* [Tenant](##tenant)

# Lookups
* ID
* Code
* Name
* Description
* Color

