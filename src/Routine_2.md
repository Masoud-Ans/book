# Routine 2

@startuml Routine 2

MakeCoffee->EatBreakfast
EatBreakfast->DoLaundry
DoLaundry->DoGroceries
DoGroceries->ComeBackHome
ComeBackHome->OrganizeGroceries
OrganizeGroceries->CheckingTheWashing
CheckingTheWashing->DoOtherChores
DoOtherChores->CookSomething
CookSomething->EatLunch
EatLunch->UnloadMachine
UnloadMachine->GoToBed

@enduml