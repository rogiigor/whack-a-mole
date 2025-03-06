## US-06: Originality

#### 1. `Audio FX and music`

I was able to make use of audio in the game. 
1. While user plays the game the `mole song` plays
2. When hitting correct mole, `hit` sound plays
3. When hitting wrong mole, `wrong hit` sound is playsing

#### 3. Additional features

I was able to add some additional features
1. I added user control select to get set `user difficulty`
2. I added one more character, `mole2` that shows in addition to `mole`
3. When wrong mole gets hit, it `reduces total score`. 
    Since I implemented this functionality in `whack(event)` method,
    it breaks test that expects whack to only `increase` score.

#### 4. Change the look of the game
While working on #3, I changed css view of the game
1. User control difficulty select has additional styling for `select` and `input` elements
2. I put score and counter on the same level using `flex` styling.