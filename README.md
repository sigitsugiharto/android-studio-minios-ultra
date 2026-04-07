# android-studio-minios-ultra
Install Android Studio on MiniOS Ultra
# download Android Studio Panda
https://edgedl.me.gvt1.com/android/studio/ide-zips/2025.3.3.6/android-studio-panda3-linux.tar.gz
# move to home
mv android-studio-panda3-linux.tar.gz ~/
# extract file
tar -xzvf android-studio-panda3-linux.tar.gz
# chage directory to android-studio
cd android-studio/bin
# run
./studio.sh
# FLUTTER
sudo apt install -y curl git unzip xz-utils zip libglu1-mesa

cd ~/

wget https://storage.googleapis.com/flutter_infra_release/releases/stable/linux/flutter_linux_3.41.6-stable.tar.xz

tar -xf flutter_linux_3.41.6-stable.tar.xz

echo 'export PATH=$HOME/flutter/bin:$PATH' >> ~/.bashrc

source .bashrc

flutter doctor


