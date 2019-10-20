# MajorTom - NASA Space Apps Challenge 

MajorTom is an app prototype from [The Phoenix Foundation](https://github.com/The-Phoenix-Foundation) that was developed during the NASA Space Apps Challange 2019 in Vienna. The app tackles the [set your sights high challenge](https://2019.spaceappschallenge.org/challenges/living-our-world/set-your-sights-high/details) by an gamified AR approach and focuses predominantly on a younger userbase. Satellites approaching the user in 1000 km radius are visualized via [NASA's WorldWind library](https://worldwind.arc.nasa.gov/). These satellites can be selected while the app will display fun facts an other fascinating information. Satellites within range can be collected similarly to Pokémon. Collecting and learning more about satellites will unlock different badges and rewards.

Additional features we envision in the future:
- Quizzes that test your obtained satellite knowledge and give different rewards
- International leaderboards focusing on collected satellites and widest knowledge
- The ablity to invite and compete against your friends
- Trading in rewards for different satellite parts which can be used to construct your own satellites in a sandbox mode. 


## Functionality overview
Satellite trajectory rendering ![img1](https://github.com/The-Phoenix-Foundation/majortom/blob/gh-pages/images/satellite.jpg)




## Setup Dev

```
pip install -r requirements.txt
pip install -e .
export FLASK_APP="phoenix.app:create_app()"
flask run
```

## Stuff


Let's collect everything we need here.

## SOCIAL

- GITTER: https://gitter.im/spaceapp-phoenix-foundation/community


