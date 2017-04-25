﻿---
title: "Before you get started | MicrosoftDocs"
ms.custom: ""
ms.date: "04/18/2017"
ms.reviewer: ""
ms.service: "gamification"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "get-started-article"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: f37b3fc7-2c99-46ac-aa75-526baac4d434
caps.latest.revision: 26
author: "m-hartmann"
ms.author: "mhart"
manager: "sakudes"
---
# Before you get started
Here are some basic guidelines for  game models, KPIs, awards, prizes, teams, player positions, and more. Familiarize yourself with these concepts to create games that works best for your business.  
  
<a name="gameModels"></a>   
## Game models and sports themes  
 [!INCLUDE[pn_gamification](includes/pn-gamification-md.md)] offers three team models for running a game: fantasy teams, fixed teams, and no teams. It also lets you create a leaderboard slide show that you can show on  a screen in your office. For game model descriptions, review the [Gamification glossary](gamification-glossary.md).  
  
 [!INCLUDE[proc_more_information](includes/proc-more-information-md.md)] [Run a game in Dynamics 365 - Gamification](run-a-game-in-dynamics-365-gamification.md)  
  
<a name="teamsPlayerPositions"></a>   
## Player positions  
 Most teams have their top performers, and your players probably know who they are. When you set up a game, we recommend you set it up in a way that prevents someone from drafting all of the top performers for their team.  
  
 **Player Positions** let you do exactly that.  Group sets of players who have similar performance records, goals, and experience. For example, think about a baseball sports theme. You might place your top performer at the first base player position, and then group other top performers at second base, right field, catcher, and so on. When players draft their teams, each player can select one player at any given time from each available player position.  
  
> [!TIP]
>  Start thinking about how you would group individuals on your team—by quota, how long they’ve been at the company, how successful they’ve been, their level of experience or skill, or any number of factors. The more you can level the playing field to make it as fair as possible, the more fun the game will be. If you're using fixed teams, you can also have players within other fixed teams compete against each other.  
  
 Commissioners and game managers: For more information about how to set up a game, see [Run a game in Dynamics 365 - Gamification](run-a-game-in-dynamics-365-gamification.md).  
  
<a name="KPIs"></a>   
## Key performance indicators (KPIs)  
 [!INCLUDE[pn_gamification_subsequent](includes/pn-gamification-subsequent-md.md)] can use any key performance indicator (KPI) that is tracked as data in [!INCLUDE[pn_crm_online_subsequent](includes/pn-crm-online-subsequent-md.md)] for point scoring in a game. For example:  
  
-   Number of calls made  
  
-   Percentage of sales quota attained  
  
-   Customer inquiries resolved  
  
-   Number of new opportunities created from a marketing campaign  
  
 Ideally, you'll want to track 3-5 KPIs per game, and make sure that every player has a KPI to score against for a fair competition.  You can use **Actuals** or **Targets**.  
  
 For example, if your game uses **Targets**, you might have “number of calls made” as a KPI, and weekly targets set at 20, 40, 60, 80, and 100 calls.  Players earn 1 point for every 20 calls.  If a player makes 72 calls in a specific week, he'll be awarded points for 60 calls.    If the player makes 30 calls, he'll be awarded points for 20 calls.  
  
 If you use **Actuals** and award one point per call, players will earn points based on the exact number of calls made.  So 30 calls will get you 30 points.  We recommend that you use **Actuals** in the first games. Targets might encourage players toward the end of each game period to make an extra effort to achieve the next target. If you have a decreasing KPI, such as number of cancellations or number of service incidents where players aim at having a smaller number, you should use **Targets**.  
  
 Think  about what KPIs you want to include, how you want to weigh them, and what thresholds you want to associate with each to keep your game balanced. Consider the following when selecting your KPIs:  
  
-   Make sure that the KPIs you choose can be reported on. For example, if you want to use "revenue booked from new customers" as a KPI, you need to have a way to identify a closed opportunity as a new or existing customer in [!INCLUDE[pn_crm_online_subsequent](includes/pn-crm-online-subsequent-md.md)].  
  
     For more information about defining KPIs in [!INCLUDE[pn_crm_online_subsequent](includes/pn-crm-online-subsequent-md.md)], see [Configure KPIs in Dynamics 365 (online)](configure-kpis-in-dynamics-365-online.md).  
  
-   Select KPIs that normalize the game to ensure even opportunities for all players. For example, if you have sales reps with significantly higher quotas than other reps, think twice before using a "revenue booked" KPI; those with higher quotas will probably be closing significantly more business. Instead, consider using "percentage of delivered quota" as a KPI. You can also use player positions and handicaps to normalize the game. [!INCLUDE[proc_more_information](includes/proc-more-information-md.md)] [Player positions](#teamsPlayerPositions)  
  
-   Set your maximum threshold amounts for targets, or cap for actuals, at above average, but not exceptional levels. For example, let’s say the average deal size at your company is $25,000 and you set "revenue booked" thresholds at $10,000, $25,000, $50,000, $100,000, and $200,000. That means if someone happens to close a $200,000 deal, they’re earning 8 times as many points as someone who closes a $25,000 deal. That player is likely going to lead the competition and make it difficult for others to compete. Instead, you might set your thresholds at $10,000, $25,000, $35,000, $50,000, and $75,000.  In this case, the individual that closes the $200, 000 deal would achieve the top threshold of $75,000 for that week and earn 3 times as many points as someone with a $25,000 deal. It's still a great week for that individual, but you haven’t allowed them to pull so far ahead that no one else can catch up.  
  
 [!INCLUDE[proc_more_information](includes/proc-more-information-md.md)] [Run a game in Dynamics 365 - Gamification](run-a-game-in-dynamics-365-gamification.md)  
  
<a name="awardsPrizes"></a>   
## Awards and prizes  
 What would a contest be without prizes? The types of awards and prizes you include in your game will determine what activities your players focus on. Assign cash, tangible prizes, or non-monetary prizes like a lunch with the CEO or an extra day off,  to each of the awards you choose.  
  
 Here are the types of awards that you can use for your game:  
  
- **Total points:**  Players who earn the most total points over the course of the game across all KPIs.  
  
- **Team manager**: Players who manage teams that earn  the most total points over the course of the game across all   KPIs.  
  
- **KPIs**: Players who earn the most points for a single KPI over the course of the game.  
  
- **Position**: Players who earn the most points in a specific position over the course of the game.  
  
 If you use fixed teams, you can use team awards and team MVP awards instead of team manager awards. If your game isn't using teams, you can't use any team awards. Have one winner for each award, or award up to ten places.  
  
> [!TIP]
>  Determine the budget available for prizes in your game. Distribute this across the awards in your game based on how you want to motivate and give out incentives to your players. Other considerations for awards:  
>   
> - It’s a good idea to include a number of awards with multiple paths to win. This way if someone falls significantly behind in one area, they have other things to focus on. For example, if a player recognizes that they can no longer win the Highest Point award, but are in the top 5 for a specific sales KPI – they’ll shift their focus and remain motivated.  
> - If your KPIs span the entire team, the Highest Point award is highly appropriate. However, if you’ve organized players into positions (based on quota, role, etc.) it’s better to use position awards. This levels the playing field and ensures each player has an equal chance to win.  
> - It’s important to associate prizes to Team Managers; otherwise, players won’t have any incentive to draft/trade players, and the ‘peer pressure’ element of the game will be diminished or lost.  
> - Based on the size of your team, consider offering prizes for multiple places (1st – 10th place).  
> - If you’re using position awards, keep in mind that you’ll have to distribute an award for “each” position being used. For example, if you have first base, second base, third base, pitcher, and catcher – and you use a gold award – you’ll have 5 winners.  
  
 Awards and prizes are assigned when you end a completed game.  
  
 You can also define weekly awards: [Define weekly awards for Gamification players and fans](define-weekly-awards-for-gamification-players-and-fans.md)  
  
## See Also  
 [Increase employee productivity with Dynamics 365 - Gamification](increase-employee-productivity-with-dynamics-365-gamification.md)   
 [Run a game in Dynamics 365 - Gamification](run-a-game-in-dynamics-365-gamification.md)   
 [Manage Gamification in Dynamics 365 (online)](manage-gamification-in-dynamics-365-online.md)