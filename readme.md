TimPlayer: HTML5 Video Player that is an Open Source and beautiful alternative to Vimeo, JWPlayer, VideoJS, Youtube, Wistia

1) To run the app locally, do the following,
```bash
git clone git@github.com:timchunght/timplayerdemo.git
cd timplayerdemo
rails server
```

2) To deploy the app on heroku, do the following,

```bash
heroku create
RAILS_ENV=production bundle exec rake assets:precompile
git add public/assets
git push heroku master
```
You must precompile assets since the video player depends on the asset files.

![Alt text](https://raw.githubusercontent.com/timchunght/tim-html5-player-rails/master/tim-html5-video.png)

Click [demo](https://timplayer.herokuapp.com/) for a live version.

The standalone player files are [here](https://github.com/timchunght/tim-html5-player-rails)

Modified and Styled by Timothy Chung

Copyright [Timothy Chung](www.linkedin.com/in/timchunght)

Please feel free to use it for any of your projects

Special thanks to Designmodo for their free UI assets!
