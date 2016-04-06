# Shopping Cart

## Author
* Anna Goodman

## Purpose
Shopping Cart intends to simplify the shopping experience by both functioning as a normal shopping list and listing out the location of items in a store, so you aren't stuck wondering "where does Safeway keep the tomato sauce again?"

## Features
* Input for items in a shopping list
* Ability to control multiple lists (such as weekly lists, specialty lists)
* When you view a list, it organizes items by the aisle they're found in
* Provides description of where in the aisle (front or back relative to front of store, approx. shelf height, etc.)
* Ability to check things off the list when you have them in your cart

## Control Flow
* The user opens the application to find a Table View with all of their current lists in it. 
* They can either create a new list or select an existing shopping list. 
* When creating a list, the control flow will act much like a to-do list in the sense that you can insert many items cleanly (think Reminders)
* When the user is done with input and is ready to shop, they will hit a button in the top right corner of the screen, and the view will change so that the items are organized by the aisle they will be found in, or the identifying location (bakery, in the back and to the right, etc.) 
* The user can check off items as they pick them up in store
* When they complete their list, Shopping Cart will notify them that they're done with their shopping trip.

## Implementation

### Model
* storeLayout.plist
* LocateItem.swift

### View
* ListSelectorTableView
* ListInputTableView
* ShoppingModeTableView

### Controller
* ListSelectorTableViewController.swift
* ListInputTableViewController.swift
* ShoppingModeTableViewController.swift