# reddit-video-downloader
A simple shell script that downloads reddit videos given a post url as an mp4. Only uses pure shell scripting, no python, javascript, etc.
<br/><br/>

## Example:


https://user-images.githubusercontent.com/55637354/162651375-33db68d6-26f5-4459-8e55-125fbebacc48.mp4


<br/>

## Example Usage:

### Save video as post title
```console
reddit-video-downloader https://www.reddit.com/r/nextfuckinglevel/comments/tzvak8/crazy_cat_challenge
```
<br/>

### Save video as file name
```console
reddit-video-downloader https://www.reddit.com/r/nextfuckinglevel/comments/tzvak8/crazy_cat_challenge output
```
```console
reddit-video-downloader https://www.reddit.com/r/nextfuckinglevel/comments/tzvak8/crazy_cat_challenge output.mp4
``` 
<br/>

### Save video as post title in directory
```console
reddit-video-downloader https://www.reddit.com/r/nextfuckinglevel/comments/tzvak8/crazy_cat_challenge ~/Downloads/
```
<br/>

### Save video as file name in directory
```console
reddit-video-downloader https://www.reddit.com/r/nextfuckinglevel/comments/tzvak8/crazy_cat_challenge ~/Downloads/output
```
```console
reddit-video-downloader https://www.reddit.com/r/nextfuckinglevel/comments/tzvak8/crazy_cat_challenge ~/Downloads/output.mp4
```


