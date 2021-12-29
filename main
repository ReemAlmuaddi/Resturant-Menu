

import Foundation
    
var name = readLine()

print ("\n\n Welcome \(name.unsafelyUnwrapped) to ✨Arno✨ resturant's menu app \n Kindly, type the number that corresponds to the option you want ;afterwards, click (Enter) from the keyboard to continue:1 \n ")
var userSelection = "4"
repeat{
    print ("-----------------------------")
    print ("1. \t View the menu options")
    print ("2. \t Make an order  ")
    print("9. \t To Exit & Close The Program")
    print("Note: If You Want to Run The program Again, Just Use The Shortcut (command+R) From The Keyboard \n")
    print("-----------------------------")


if let userSelection = readLine(){
    
    
    // list of food in pasta section in print
    let pMenuePrint = [2:"Lasagna",
                       3:" Penne Tukta",
                       4: "Spaghetti Tonno",
    
    ]
    
    let pizzMenuePrint  = [1:"Prosciutto e funghi",
                         2:" Quattro Stagioni",
                         3: "Capricciosa.",
      
      ]
  

    switch userSelection {
    case "1":
        print("-----------------------------")
        print ("✨Today's Offer✨ /n Get one Pasta with a free Pizza")
        print("1.\t Pasta🍝 \n kindly order the Pasta by typing its number like :2,3,4 ")
        print("2. \t Pizza🍕 \n kindly order the pizza by typing its number like : one, two, three")
    
        // Menu Food's type using a switch inside a switch
        if let menu = readLine(){
                switch menu {
                case "1" :
                    print (pMenuePrint)
                case "2" :
                    print (pizzMenuePrint)

                default:
                    "kindly,chose a number 1 or 2 in order to check menu"
                }
        }
        
    case "2":
        print("Kindly choose your plate by typing its number  ")
        //orders
        if let orderss = readLine(){
                switch orderss {
                case "2":
                  
                    orderLasagna(firstOrder: "Lasagna" , price: 60)
                case "3" :
                    orderPenne(secondOrder:"Penne Tukta" ,price: 40)
                case "4" :
                    orderSpaghetti(thirdtOrder: "Spaghetti Tonno",price: 50)
                
                default:
                    "kindly,chose a number 1 or 2 in order to check menu"
                }
            
        }
        case "0" :
        print("Exit")
        
    default:
        print("Error Message: Invalid Input, Please Enter (1) to View the menu options, Or (2) to  Make an order  , Or (0) To Close and Exit the Program ")
    }
    func orderLasagna(firstOrder: String, price : Int ){
        
        print ("Your order is \(firstOrder) Price : \(price)")
        
    }
    func orderPenne(secondOrder: String , price : Int){
        
        print ("Your order is \(secondOrder) Price : \(price)")
        
    }
    func orderSpaghetti(thirdtOrder: String , price : Int){
        
        print ("Your order is \(thirdtOrder) Price : \(price)")
        
    }
}
     class pizza {
        var order1 : String = "Prosciutto e funghi"
        var price1 : Int = 55
        func one(){
            print ("Your order is \(order1) Price : \(price1)")
        }
       
    }
var pizza1 = pizza()
    pizza1.one()

} while userSelection == "4"
