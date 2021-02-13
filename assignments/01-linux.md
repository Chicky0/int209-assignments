```bash
cd ..
sudo mkdir wipcamp12
cd wipcamp12
sudo mkdir programmer website network ux-ui
sudo touch slide01.txt
cp slide01.txt slide02.txt
cp slide01.txt slide03.txt
cd ..
sudo cp -r wipcamp12 wipcamp13
cd wipcamp13
sudo rm slide03.txt
cd ../wipcamp12/
sudo mv slide01.txt ../wipcamp12/newslide.txt
cd ..
sudo rm -r wipcamp12 wipcamp13
```