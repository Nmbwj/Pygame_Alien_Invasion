# Alien Invasion: Making a Game with Python

Alien Invasion is an interesting game for kids to learn Python while playing. It increase their creativity and problem solving skill in an ease steps of development.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
python -m pip install --user pygame 

```
or if you are using environment.
```bash
python -m pip install pygame 
```
## Requirements
Download the game [image](https://drive.google.com/drive/folders/1L_4pNwRiLritO3Xe7pY3N2tDudTr25Y8?usp=sharing) resources from my drive and put them in the game's folder. Make sure the name of the folder which contains the images should be `images` 

## Usage

```bash 
python alien_invasion.py
```

## Teaching Instructions

In order to teach students. There are a few things to notice!
You should start from the first building-block(scratch).
Developing together from the scratch is the best way of learning.

I have organized my `git-commits` in a way: that you can develop along from the first commit moving forward to the nexts!

follow the next steps:
 
Run this commands:

```bash
git checkout <checksum/SHA hash of the commit>
```

for example to start from the beigning run:

```bash
git checkout 3e925da72664c676a95e68246ed37dca5b990ef4
```

to go to the next development step run:

```bash
git checkout d313afde8868796fd67aa38ac633da580e18772e
```

to go to the latest development run:

```bash
git checkout 97a5b27c3b260c677705518827efe059a289c88c
```

while going through each development step understand the core change by reffering the commit messages!

All the checksum/SHA-commit hash and commit message are avialiable:

```bash
git log --pretty=oneline
```

After you finished teaching do not commit anything before you:

```bash
git checkout master
```
Then only, you can continue on your work!

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.


## License

[MIT](https://choosealicense.com/licenses/mit/)
