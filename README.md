## GeoHunt - Tools

This repository is a set of tools used to help with the development of [GeoHunt](https://github.com/SDP-GeoHunt/geo-hunt)

## Populate the database
A small python script is provided to populate the database with Point-Of-Interest using the open-street-map API along with a small web-scrapper script. To use it, have `python 3` installed along with the following libraries : `Pillow`, `firebase_admin`, `requests`, `tqdm`, `pickle`, `zlib`. You then need to generate the private admin key for firebase. Notice that with this key, anyone has an admin access to all features of firebase [check this tutorial](https://firebase.google.com/docs/admin/setup). Once done you can use this script with

```bash
python3 scrap-point-of-interrest.py <top-dd> <left-bbox> <bottom-bbox> <right-bbox> <path-to-auth-file>
```
Where `<...dd>` correspond to the degree notation of the top/left/bottom/right corner



