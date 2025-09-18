# NIE_CSD_Team22
entities
1)MEMBERS
  id,name,phoneno,balance(>=0)
2)Recharge
  id,memberid(referential),amount(100rs-2000rs),date,recharge_limit
3)Games
  id,name(unique),prize,description, duration,  status(active,  inactive), minPlayerCount ,maxPlayerCount ,multiplePlayerCount
4)Transactions
  id,memberid(referential),gameid(referential),amount,date
5)collections ---owners balance