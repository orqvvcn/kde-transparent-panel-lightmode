
![light-transparent-panel](https://github.com/user-attachments/assets/68d53d7c-e655-4765-8ff8-f5e99246ad58)


top panel is fully transparent and bottom panel transparent with no blur

you can use 'KDE control station' widget, it's what is next on the right of the search icon on top panel


https://github.com/user-attachments/assets/a0794b7f-2906-44d9-b84a-1a9f5a727aef

this is for the default theme panel kde plasma 



## install

 Clone the repo
 
```bash
git clone https://github.com/orqvvcn/kde-transparent-panel-lightmode.git
cd kde-transparent-panel-lightmode
```


Create needed folder
```bash
sudo mkdir -p /usr/local/share/plasma/plasmoids
```

Copy org.kde.panel folder

```bash
sudo cp -r org.kde.panel /usr/local/share/plasma/plasmoids/
```

Log out and log in


-------------------------------------------------------------------

## to uninstall
```bash
sudo rm -rf /usr/local/share/plasma/plasmoids/org.kde.panel
```

-------------------------------------------------------------------

the icons animation is not part of this if you want it, it's here

https://github.com/orqvvcn/kde-panel-tasks

https://github.com/orqvvcn/kde-panel-tasks-light
