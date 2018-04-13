## Darts Tracker App

This Darts App project was developed within the internship program (Android Basics by Google Nanodegree Program).

1.  For the reason of convenience, I decided to present only some of the possible points to add, especially: 1, 5, 10 and 20 - the buttons add points on onClick.

2. The maximum number of points to be achieved is 180. In this case, in Java, I created the method with if/else 3 conditions which will prevent you from adding more than 180 points, and will pop up a toast message “You cannot obtain more than 180 points!”. But, instead will leave you to add a smaller value. (For ex: you have 176, you will not be able to add 5, 10, 20 because it exceeds 180, but you can still add 1)
Also, once you get 180 points another toast message pop up: “180 points, Player 2 - You Win!” and the score resets.

3.  **The background image and scores are saved while turning the landscape mode.**

4. As something new, I also added an icon of darts in action bar, placed in the drawable folder.
The background image is set to all dimensions in mipmap folder (hdpi, ldpi, mdpi, xhdpi, xxhdpi, xxxhdpi) .

5. Scroll within the app is activated.

Please find below the screenshots of the active app (as well as the gif file): 

![screenshot_1523575815](https://user-images.githubusercontent.com/33226462/38709933-9e01d75a-3eb5-11e8-80ed-ad6d07f9fc8d.png)
![screenshot_1523575842](https://user-images.githubusercontent.com/33226462/38709938-a1528d50-3eb5-11e8-9127-7491b1e66260.png)
![screenshot_1523575853](https://user-images.githubusercontent.com/33226462/38709940-a39ae8e6-3eb5-11e8-8193-72f7e6642500.png)
![darts](https://user-images.githubusercontent.com/33226462/38709945-a6ba249c-3eb5-11e8-9b1c-53b301671b48.gif)
