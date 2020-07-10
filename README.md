# electron-react
base project for react applications using electron configured with typescript.

Install dependencies:
```console
npm install
```

you should have a dist folder in app/public and app/src.

To run electron with react use: (see package.json)
```console
npm run start
```


Update project base with current electron-react:
Clone electron-react project (or pull from master if you currently have the clone):
```console
git clone https://github.com/plixxer/electron-react.git electron-react
```

Navigate to your project repository and add electron-react repository to your project repo:
```console
git remote add electron-react ../electron-react
git remote update
```

create seperate branch for updating electron-react:
```console
git checkout -b electron-react
```

merge electron-react/master into Your_Project_Repo:
```console
git merge --allow-unrelated-histories electron-react/master
```

push changes and set local branch:
```console
git push --set-upstream origin electron-react
```
