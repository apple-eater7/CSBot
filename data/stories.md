## buy from list path
* want_to_buy
  - utter_product_list
* product_name{"product":"IPhone"}
  - utter_buy_success
  - utter_what_else


## info from list path
* more_info
  - utter_product_list
* product_name{"product":"IPhone"}
  - utter_more_info
  - utter_what_else

## buy product path
* want_product{"product":"MIPhone"}
  - utter_buy_success
  - utter_what_else

## info path
* more_info_on_product{"product":"MIPhone"}
  - utter_more_info
  - utter_what_else

## greet path
* greet
  - utter_greet

## stop after denial
* deny
  - utter_goodbye
