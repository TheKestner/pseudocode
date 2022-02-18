# Pseudocode for Washing Hands
## Main Goal: 
User should be able to wash their hands with the choice of either Hot or Cold water while using soap to lather to clean their dirty hands for at least 20 seconds. Hands can either be dried by Air or with a Towel. 

## Objects:
1. Sink 
    * Faucet for water to exit
    * Left Handle for hot water
    * Right Handle for cold water
2. Soap
3. Users Hands
    * Left Hand
    * Right Hand
4. Towel 

## Pseudocode

**START:** Start Program for Washing Hands

**INIT:** Create Variables for the Program

* Sink
    * Left Handle = Hot Water
    * Right Handle = Cold Water

* Soap

* Towel

* Users Hands
    * Left Hand
    * Right Hand

* Dirty

* Clean

**Function:** Turn on Sink

    If Either or Users hands are Dirty, 
    Add Sink for Hot water or Cold water.

**Function:** Soapy

    If Users hands + Soap been 4 seconds
    Soapy = true    

**Function:** Rub

    If Soapy Then 
    move Left hand.length + Right hand.length by half

**Function:** Washing Hands 
    
    Do Turn on Sink
     while Dirty is True


    If Dirty,
     Add Users Hands + Hot Water or Cold Water
        

    If Users Hands are Dirty, then Add Soap.
     While Soap is on hands, Rub Users Hands together until Soapy.
        End while

    If Soapy then Rub Users Hands 
     While Dirty Rub Until > 20 seconds
        End while

    Clean = Soapy + Rub = True

    If Clean is True, Then Rub Hands with Towel.

**End:** End The Program
