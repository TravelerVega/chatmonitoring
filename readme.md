# Modifying scripts like rolesFX to work with this:
    For example in rolesFX where "AddEventHandler('chatMessage', function(Source, Name, Msg)" is
    you need to add:
    ------------------------------------------------------------
    if not exports["chatmute"]:checkIfCanSendMessage(Source) then
        return
    end
    ------------------------------------------------------------
    right after it :P 

    and inside config.lua you need to modify "config.other_chat = false" to be true.




**Discord: Traveler Vega#0495**
