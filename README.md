# Bannerlord-mod-RebelToNewKingdom
A custom mod changing Rebellion logic and creating a new kingdom for Mount &amp; Blade II: Bannerlord. 

## Main idea / feature
So far, this game has been updated to v1.3.13, yet no new kingdom creation mechanism was added; As time goes by in game, we didn't see significant new clans generated. 
Snowballing remains a known issue in this game affecting balancing. 
And lack of (clan) variability is another problem in this open-world game. 

As a light-weight solution, the RebellionsCampaignBehavior was modified to create a new kingdom by the rebels, right after (within 1 in-game day) the Rebellion event was triggered. 

Then the Rebel state is removed as normal as other regular clans. The clan owner becomes the ruler of the new created kingdom. 

## Compatibility
This mod removed the default in-game RebellionsCampaignBehavior. A custom behavior class (RebelToNewKingdomBehavior) was implemented to make the changes. 
Thus, if you're using other mods that rely on the default RebellionsCampaignBehavior, it's not compatible. 

It's developed based on game version 1.3.13. No testing was performed for previous versions, this part of game logic / mechanism didn't seem to have breaking changes for a while compared with earlier versions though. 

It's purely in-game logic change that no read / write operation to the game save. Turning this on / off shouldn't impact the save. 

## Installation
* Unzip the downloaded file. Copy `RebelToNewKingdom` folder to Bannerlord `Modules` folder.
* Open the game launcher and check this mod. 

## Troubleshoot / support
- Like other mods, it's common to see crashes / Unable to start when:
  - Running in mismatched game version.
  - Having conflicts with other mods.
- This mod is just for fun and mainly my own personal use, so no promise to maintain this for later versions or support others at this stage.
- Only best efforts to GitHub Issues filed here. 
