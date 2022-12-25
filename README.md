# Player_Contact_Detection_Helpers

Helpers for 1st and Future - Player Contact Detection competition on Kaggle

References: [Starter code](https://www.kaggle.com/code/robikscube/nfl-player-contact-detection-getting-started)

Sample videos:

This video displays these helmet boxes on an example play. They are provided starting a few frames prior to the play starting and the video displays the associated player label (home/visiting team in combination with jersey number) next to the helmet box.

<video src="samples\contact_58168_003392_Sideline.mp4"></video>

<!-- <video width="320" height="240" controls>
  <source src="samples\labeled_58168_003392_Sideline.mp4" type="video/mp4">
</video> -->

In this video you can see the labels for this play, approximately linked with the associated helmets within the video.
Note in this video:

- **Black** helmet boxes indicate that player is not in contact. A unique number (home/visiting combined with jersey number) is shown next to their helmet.
- **Green** helmet box indicates the player is in contact with one or more players.
- **Red** helmet box indicates the player is in contact with the ground (and possibly another player).
- **Blue** lines show the link between players in contact with each other.

<!-- changed -->

<video src="samples\labeled_58168_003392_Sideline.mp4"></video>
