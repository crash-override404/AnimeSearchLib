# Anime Search
Original from nugra

fixing some error and delete unusable code 

## Require to use
```
First, add in init.py:
from AniSearch import AniSearch
Second, use this code Nb : Untried:
  ani_ = LIBNAME.AniSearch('path/to/file')
  ret_ = ani_.post_image()
  data_ = ani_.get_data(ret_)
  info_ = ani_.get_info(data_[0]['season'], data_[0]['anime_name'])
  name_en = info_[0]['name_en']
  name_jp = info_[0]['name_jp']
  genre = info_[0]['genres']
  series_type = info_[0]['s_type']
  season = data_[0]['season']
  video = data_[0]['video']
  image = data_[0]['thumbnail']
  client.sendImageWithURL(image)
  client.sendText(msg.to,"Name English:\n%s\nName Japan:\n%s\nGenres:\n%s\nSeries:\n%s\nSeason:\n%s\nVideo:\n%s\nThumbnail:\n%s", %(str(name_en),str(name_jp),str(genre),str(series_type),str(season),str(video),str(image)))
```
