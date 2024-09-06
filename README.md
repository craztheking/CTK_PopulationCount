# CTK_PopulationCount
Population Count Blueprint (UE4/Insurgency Sandstorm)

Intended for use on Insurgency Sandstorm, Based on the same blueprint made by myself for Operation : Harsh Doorstop.

Can be used in any Unreal Engine Game, Only change needed is replacing bone name, with one contained on your Characters Skeletal Mesh.

Details/Defaults:

►Check Timer: 1.0
This is how often the blueprint checks on updated player count, Increasing this improves performance while lowering accuracy.
►Text Color : (B=255,G=255,R=255,A=0)
Text/Number Display Color
►Sample Player Count: 10
This is a default number to display while working in engine to verify how it would display, This is updated after first player check.
►Debug Draw: none
Shows Debug when checking
►Base on Player Count: false
Using this will set population based on players in server (will not check if players are dead or alive)
