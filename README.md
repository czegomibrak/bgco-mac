# Black Gold Coin - Silicon Mac OS App
Build from source code:
1. Download from repository file named bgco-2.0.1.zip and unpack it
2. cd bgco-2.0.1
3. chmod +x contrib/macos/build.sh
CMAKE_OSX_ARCHITECTURES=arm64 DEPLOY=1 ./contrib/macos/build.sh

How add original icons to .app?
1. Download bgcoin.icns from repository
2. rm /Applications/BGCO.app/Contents/Resources/bgcoin.icns
3. mv YOUR_DOWNLOADED_FILE_PATH /Applications/BGCO.app/Contents/Resources/bgcoin.icns
