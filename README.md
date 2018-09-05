## mp3
download music files


youtube-dl --extract-audio --audio-format mp3 http://youtube.com/?v=asdfasdfasdf


## Download from a file
while read -r LINE; do
    youtube-dl --extract-audio --audio-format mp3 "$LINE" 
done < "/mnt/d/musicas/playlist.txt"




