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
    * Left Handle for Hot Water
    * Right Handle for Cold Water

* Soap

* Towel

* Users Hands
    * Left Hand
    * Right Hand

* Dirty

* Clean

**Function:** Wash hands
 If Either Users Hands are Dirty, then Start Washing hands, ELSE Users Hands are Clean.
**Function:** Lather Soap 
    If Either or Users hands are Dirty, Turn on Sink for Hot or Cold.
     While water is running from sink, Place both Users Hands under Faucet until wet.
        End While

    If Users Hands are wet, then Add Soap.
     While Soap is on hands, Rub Users Hands together until Soapy.
        End while

    If Soapy then place and Rub Users Hands under Faucet for > 20 seconds, Rub Until Clean.

    If Clean is True, Then Rub Hands with Towel.
    
    If Clean is True, Then Turn Off Sink for Hot or Cold.

**End:** End The Program
