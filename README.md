Instrucitons:

1. Clone this repo.
2. Initiate submodules:
```
git submodule update --init --recursive
```
3. Install hugo
4. Compile page
```
hugo
```
5. HTML files saved at the public folder.
6. Push files to public github pages repo
```
cd public
git commit -am "New deployment"
git push
```
