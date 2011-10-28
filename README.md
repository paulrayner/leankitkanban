LeanKitKanban
=============

LeanKitKanban is a simple ruby wrapper around the LeanKitKanban API

http://leankitkanban.com/

Usage
-----

`
LeanKitKanban::Config.email    = "mytestemail@test.com"
LeanKitKanban::Config.password = "mypassword"
LeanKitKanban::Config.account  = "myaccount"

LeanKitKanban::Board.all # gets all boards and returns an array of hashes
LeanKitKanban::Board.find(board_id) # gets the specified board
`
