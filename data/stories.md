## happy path
* greet
  - utter_greet
  - utter_greet_career_guidance

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## career guidance confused
* career_guidance_confused
  - action_respond_confused

## career guidance paths
* career_guidance_paths
  - action_respond_career_paths

## career guidance tech
* career_guidance_technologies
  - action_respond_technologies
## interactive_story_1
* career_guidance_paths
    - action_respond_career_paths
* career_guidance_technologies{"career_path": "devops"}
    - form_action_career_path
    - form{"name": "form_action_career_path"}
    - slot{"requested_slot": "slot_career_path"}
    - action_respond_technologies
