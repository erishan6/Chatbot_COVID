## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
  
## corona chatinfo
* corona_info
  - utter_coronainfo

## corona  q1
* corona_info_one
  - utter_coronainfo_one

## corona  q2
* corona_info_two
  - utter_coronainfo_two

## corona chatinfo menu
* corona_menu
  - utter_coronamenu
  