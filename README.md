# Utils

| Name   |URL      |Type |
|----------|-------------|-------------|
| Git Cloner|https://github.com/arun0808rana/git-cloner  | Server + Script |
| VS Code Bindings|https://github.com/arun0808rana/vs-code-bindings   | VS Code |
| Google Search Navigator|https://github.com/arun0808rana/Google-Navigator | ViolentMonkey Script |
| Youtube Navigator|https://github.com/arun0808rana/Youtube-Navigator | ViolentMonkey Script |
| Yellow Functions|https://github.com/arun0808rana/yellow-functions | VS Code Theme |
| Personal Servers|https://github.com/arun0808rana/personal_servers | Server |
| AirBnb Guidelines|https://github.com/airbnb/javascript | Repo |
| Post Format Instructions| https://github.com/arun0808rana/post_format_instructions | Nodejs Script |


### Components
|Name| URL|
|----------|-------------|
|Slider| https://codepen.io/tuesta/pen/QoMqBY|

### Youtube-dl Aria2c
Concurrent downloads via external client.
```bash
youtube-dl -f 140 --restrict-filenames --external-downloader aria2c --external-downloader-args "-c -j 16 -s 16 -x 16 -k 1M" -ciw "___________________________________"
```

### bashrc stupidity
```bash
# aliases list
# after pasting this shit enter . ~/.bashrc
# in terminal
alias 'gito'='gh repo create "${PWD##*/}" --public --source=. --remote=origin && git add . && git commit -m "init" && git branch -M main && git push -u origin main'	

function open() {
    #do things with parameters like $1 such
    codedirpath=/home/dev/Desktop/pro/"$1"
    code $codedirpath
}

function clone(){
	clonePath=/home/dev/Desktop/pro/clones
	git -C /$clonePath clone $1
}
```

### Themes

<details>
  <summary>VS Code</summary>
  
#### [Blueberry Dark Theme](https://marketplace.visualstudio.com/items?itemName=peymanslh.blueberry-dark-theme)
![image](https://user-images.githubusercontent.com/68982541/191875132-e79d8617-bc4b-4ca2-a0ed-3b1678830da2.png)

#### [Tokyo Night](https://marketplace.visualstudio.com/items?itemName=enkia.tokyo-night)
![image](https://user-images.githubusercontent.com/68982541/191868732-1f45ae28-c06d-49a5-832a-c36772ef3d9e.png)

#### [Tokyo Night Horizon](https://marketplace.visualstudio.com/items?itemName=eternal.tokyo-night-horizon)
![image](https://user-images.githubusercontent.com/68982541/191869322-c52beb89-10de-4048-b647-461011a4f26c.png)

#### [Tokyo Night Frameless](https://marketplace.visualstudio.com/items?itemName=MagdalenaLipka.tokyo-night-frameless)
![image](https://user-images.githubusercontent.com/68982541/191869429-591123c0-88e0-47f3-83bc-f5d100fae7fc.png)

#### [tokyo-night](https://marketplace.visualstudio.com/items?itemName=Avetis.tokyo-night)
![image](https://user-images.githubusercontent.com/68982541/191869570-36fca641-46e4-4cea-b771-9b7c5a0c97fc.png)

#### [Ayu](https://marketplace.visualstudio.com/items?itemName=teabyii.ayu)
![image](https://user-images.githubusercontent.com/68982541/191870824-63c2f48c-a9a9-4233-87fa-ca4621445957.png)
	
</details>



