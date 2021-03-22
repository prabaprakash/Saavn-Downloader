# Saavn Downloader
PoC for vulnerability in Saavn App researched by Arun.
The fullset of funcitonality offered by this is:
  - High Qualtiy - M4A
  - Songs Detail
  - Download PlayList
  - Download Album
  - Download Entire PlayList from user profile
  - Download Entire Albums from user profile
  - Download Entire JioSaavn Originals and Podcasts in the user profile without any subscription.
 

### Installation
```
$ pip install poetry
$ poetry install
```

### Usage

##### Download Playlist or Album from Web URL
```
$ poetry run python run.py
$ Paste the URL: https://www.jiosaavn.com/album/tum-hi-aana-from-marjaavaan/j9bfphC2728_
```

![alt text](https://github.com/prabaprakash/Saavn-Downloader/raw/master/gallery/Process.png)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fprabaprakash%2FSaavn-Downloader.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fprabaprakash%2FSaavn-Downloader?ref=badge_shield)



### NOTE: If at any point there is an Error or the Download fails you can Retry the same command

#### Download All Albums of an Artist
```
$ poetry run python run.py -artist --album
$ Paste the URL of Artist Profile: https://www.jiosaavn.com/artist/babbal-rai-albums/pRd5ZTGrLv8_
``` 

#### Download All Songs of an Artist
```
$ poetry run python run.py -artist --song
$ Paste the URL of Artist Profile: https://www.jiosaavn.com/artist/babbal-rai-albums/pRd5ZTGrLv8_
```


#### Download All Playlist from your profile
```
$ poetry run python run.py -p
$ Enter your Email: your_saavn_email
$ Enter your Password: your_saavn_password
```

#### Download All Albums from your profile
```
$ poetry run python run.py -a
$ Enter your Email: your_saavn_email
$ Enter your Password: your_saavn_password
```

#### Download All JioSaavn Originals or Podcast Shows from your profile
```
$ poetry run python run.py -s
$ Enter your Email: your_saavn_email
$ Enter your Password: your_saavn_password
```


### Known Issues
  - No Meta Data in JioSaavn Originals and Podcasts

### Development

Want to contribute? Great!

### Docker
Not yet


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fprabaprakash%2FSaavn-Downloader.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fprabaprakash%2FSaavn-Downloader?ref=badge_large)
