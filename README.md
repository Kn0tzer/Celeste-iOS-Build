# Celeste on iOS

## Download
<b>THIS BUILD IS NEARLY UNPLAYABLE ON PURPOSE. READ THE LEGAL SECTION BEFORE DOWNLOADING.</b><br>
<sub><a href="https://buzzheavier.com/fq71ykrors5f">Download</a></sub>

## Legal
Files contained in download links are not hosted on GitHub, nor were they upload by me. This build is for <b>Education Purposes Only!! I'm not saying that as a legal cop-out, I know that means nothing.</b> What I mean is that this build is borderline unusable, and shouldn't be tried to be used for playing the actual game. I've purposefully uploaded a version where the game itself runs in a tiny window intead of taking up the fullscreen, and the virtual controller takes up half the screen, covers important elements and isn't transparent. The controls themselves are purposefully bad, with it being almost impossible to move and climb at the same time, making it very, very difficult to pass even the tutorial.<br><br>
<b>IF YOU WANT ME TO TAKE DOWN THIS REPO</b>: Create a GitHub issue, OR email me at g4marchi@gmail.com, OR <a href="https://discordapp.com/users/506628717125304334">message me on discord @Kn0tzer</a>. I've tried to make it as easy possible for you to ask me to take this down to avoid any legal issues. Because the download was not uploaded by me I can't delete it, but I can delete this repo.

## Building

### what you'll need
- an **FNA** build of Celeste (this repo has been tested with the Steam version only, the itch.io version *should* work too)
- MacOS (if you don't have access to a MacOS machine, you can use a MacOS VM)
- XCode
- Visual Studio for Mac with the C#, .NET and Xamarin.iOS workloads
- patience

### how to build
- install the needed software mentioned above
- run `./build.sh`
- follow the instructions
- hope it works :3

these instructions might be slightly wrong or have missing information because i wrote this like 3 months ago and don't remember every detail - if you have issues feel free to open an issue :3

### installing
the script will tell you where the final .ipa file is located - just sideload it to your iOS device using something like TrollStore, AltStore or similar

### credits
- **@TheSpydog** for demonstrating this being possible and for developing the fnalibs-ios-builder
- **@r58Playz** for adding touch controls(!) and fixing building on newer Xcode versions
- my friends for being supportive <3
<br><sub>i might have forgotten some people here, so this list is not exhaustive!!</sub>
