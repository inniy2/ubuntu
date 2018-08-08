## How to install zsh on ubuntu  

- - - -   
Reference: (Getting oh-my-zsh to work in Ubuntu )[https://gist.github.com/tsabat/1498393]  

- - - -  
1. Install zsh  
```bash
sudo apt-get install zsh
```

2. Install git-core  

```bash
sudo apt-get install git-core
```
> Note: In my kubutu the process was not neccesary   

3. Install oh-my-zsh  
```bash
sudo wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | zsh
```

4. Set default shell for the personal account  
```bash
sh -s `which zsh`
```

5. Change all changes before restart your pc  
```bash
sudo shutdown -r 0
```




