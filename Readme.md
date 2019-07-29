# Test Project CI/CD

## xcodebuild 

### Create archive
xcodebuild -workspace BubbleTea.xcworkspace  -scheme BubbleTea_release  
     -configuration Release archive -archivePath ~/Downloads/bubble_archives/BubbleTea.xcarchive

### Export archive
xcodebuild -exportArchive -archivePath ~/Downloads/bubble_archives/BubbleTea.xcarchive 
     -exportOptionsPlist exportOptions.plist -exportPath ~/Downloads/bubble_export/