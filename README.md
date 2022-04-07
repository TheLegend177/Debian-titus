

Use the following Debian ISO as the base <https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/weekly-builds/amd64/iso-cd/>

sudo apt update
sudo apt install git
git clone https://github.com/ChrisTitusTech/Debian-titus.git
ls
cd Debian-titus/
exit 
ls
./user.sh
systemctl enable sddm --now
