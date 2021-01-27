# _Order Vendor Tracker_

#### _Order/Vendor, 1/19/21_

#### By _Andrew Mickel_

## Description

_This is a program to simulate a tracker for baked goods, based on orders and the vendors that places them._

## Setup/Installation Requirements

* _Clone this repository._
* _Open repository in your preferred code builder program. (This was built in VS Code)_
* _Check both of the .csproj files to ensure the proper framework under the "PropertyGroup" and "TargetFramework". I am using netcoreapp2.2. Your version may be newer_
* _If the framework does not match above, update the version of your netcoreapp by changing the numbers. For example if you are using netcoreapp 3.1, change netcoreapp2.2 to netcoreapp3.1_
* _In the terminal, cd into the VendorOrderTracker folder_
* _Type in the terminal "dotnet restore"_
* _Repeat the two steps above for "VendorOrderTracker.Tests" folder if you want to run tests_
* _To run the program, type "cd VendorOrderTracker" into the terminal, then type "dotnet run" in the terminal._
* _After dotnet finishes restoring, type "dotnet run". The program should now be running_

## Known Bugs

_No known bugs at the this time._

### Specs

| Spec                                            | Input                        | Output                        |
| :---------------------------------------------- | :--------------------------- | :---------------------------- |
| **Can make an instance of Order object** | `new Order()` | typeof(Order) = Order |
| **Return given title** | "orderOne" | "orderOne" |
| **Return given description** | "order description" | "order description" |
| **Return given price** | `12` | `12` |
| **Return given date** | "December 18 2020" | "December 18 2020" |
| **Get all instances of Order** | `Order.GetAll()` | {Order, Order} |
| **Get Id of Order** | orderInstance.Id | `2` |
| **Find Order by Id** | `Order.Find(2)` | `Order` |
| **Can make an instance of Vendor object** | `new Vendor()` | typeof(Vendor) = Vendor |
| **Return given name** | "vendorOne" | "vendorOne" |
| **Return given description** | "vendor description" | "vendor description" |
| **Add Order to order list** | `newVendor.AddOrder(Order)` | newVendor.Orders[0] = Order |
| **Get Order list** | `Vendor.Orders` | {Order, Order} |
| **Get all instances of Vendor** | `Vendor.GetAll()` | {Vendor, Vendor} |
| **Get Id of Vendor** | vendorInstance.Id | `2` |
| **Find Vendor by Id** | `Vendor.Find(2)` | `Vendor` |

## Support and contact details

_Please check the .csproj files to ensure the proper framework you are running and change if necessary as described in the Setup section_

_Any known issues, please reach out to Andrew Mickel at andrew.m.mickel@gmail.com._

## Technologies Used

* _C#_
* _VS Code_
* _.NET Core v 2.2_
* _REPL_
* _MSTest_
* _ASP.NET_

## License

Copyright (c) 2020, **_Andrew Mickel_**_

This software is licensed under the MIT license.