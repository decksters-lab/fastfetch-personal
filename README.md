# fastfetch-personal
This is for nonsystemd systems. I use artix so this is mainly for that. I have additonal pngs in the subfolders of the png folder .

I also include a python script in case you want to add your own images and have them be in a somewhat uniform sizing. To use it: drop your png into the png folder and run the sq script, take note that the processed version will have sq_ appended to the file name... You can delete the source file afterwards... there is an ansi color key as well.

Installing:
Option 1: Clone straight into ~/.config
git clone https://github.com/decksters-lab/fastfetch-personal ~/.config/fastfetch

Option 2: Clone somewhere else then move it
git clone https://github.com/decksters-lab/fastfetch-personal
cp -r fastfetch-personal/* ~/.config/fastfetch/

Option 3: if you want to move (not copy) and remove the clone folder after:
git clone https://github.com/decksters-lab/fastfetch-personal
mv fastfetch-personal/* ~/.config/fastfetch/
rm -rf fastfetch-personal
