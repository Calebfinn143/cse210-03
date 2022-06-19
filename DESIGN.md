+-- game
    +-- directing
      +-- director.py
    +-- casting
      +-- cast.py
      +-- actor.py
      +-- cyclers.py                    (Parent Class)
      +-- player_one.py                 (Child Class)
      +-- player_two.py                 (Child Class)
    +-- scripting
      +-- action.py                     (Parent Class)
      +-- control_actors_action.py      (Child Class) - (Polymorphism)
      +-- draw_actors_action.py         (Child Class) - (Polymorphism)
      +-- handle_collisions_action.py   (Child Class) - (Polymorphism)
      +-- move_actors_action.py         (Child Class) - (Polymorphism)
      +-- script.py
    +-- services
      +-- keyboard_service.py
      +-- video_service.py
    +-- shared
      +-- point.py
      +-- color.py
  +-- __main__.py
  +-- constants.py

DESIGN NOTES:

player_one and player_two will inherit similar methods from cyclers as the previous snake Class.
Update player trails so that they remain fixed in place.
Edit controls for both players
Ensure each cycler has separate color