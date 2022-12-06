# passtime
4v4 Competitive Passtime plugins and configs used for the pugs at https://steamcommunity.com/groups/4v4PassTime

Feel free to use anything in this repository for your own pugs
## plugin features
- passtimecontrol.smx

    Disables shotgun, stickies, and needles via sm_passtime_whitelist 1/0 (def. 0)
    
    Prevents switches classes while dead to instantly respawn via sm_passtime_respawn 1/0 (def. 0)
    
    Disables the blurry screenoverlay after intercepting or stealing via sm_passtime_hud 1/0 (def. 1)

    Prevents the jack from colliding with dropped ammo packs or weapons via sm_passtime_disable_collisions 1/0 (def. 0)
    
    Turn on hud text, chat text, or sound notifcations when picking up the ball via sm_ballhud
    
- passtimestats

    Prints chat messages upon a player scoring, intercepting, or stealing
    
    Prints players total scores, saves, intercepts, and steals to chat after a game is over via sm_passtime_stats 1/0 (def. 0)

    Change the delay between a team winning and the stats being displayed in chat via sm_passtime_stats_delay (def. 7.5)
    
    sm_passtime_stats will be automatically set to 1 if the map name begins with "pa"
## config files
- pass_push.cfg
    
    Enables the passtime config
  
- pass_off.cfg
       
    Disables the passtime config
    
- passtime_whitelist.txt
    The 4v4 competitive passtime whitelist
