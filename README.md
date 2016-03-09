# mac-hacks

defaults write NSGlobalDomain NSAutomaticWindowAnimationsEnabled -bool NO

defaults write NSGlobalDomain NSAutomaticWindowAnimationsEnabled -bool YES 

http://osxdaily.com/2011/07/25/disable-the-new-window-animation-in-mac-os-x-lion/

To change the location of screenshots :
 defaults write com.apple.screencapture location ~/Desktop/Screenshots
 
In Yosemite , to have alias and set env variables

in ~/.profile \n
 export PATH=/Users/abch/Desktop/abhishek/Projects/hadoop/pig-0.15.0/bin:$M2_HOME/bin:$JRE_HOME/bin:$JAVA_HOME/bin:$JBOSS_HOME/bin:$PATH  \n
 alias qbuild='mvn clean install -e -Prelease -DskipTests'

  
