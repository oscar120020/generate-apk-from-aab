# Generate APK file from AAB file

## Step 1: Open a terminal from the same location of your bundletool, abb and keystore files and run the next comand.

```java -jar bundletool.jar build-apks --bundle=app-release.aab --output=app-release.aab.apks --ks=your-upload-key.keystore --ks-key-alias=your-key-alias --mode=universal```

This will generate a file named: app-release.aab.apks.

## Step 2: Run the next comand to generate a Zip with the final APK.

```ren app-release.aab.apks app-release.aab.apks.zip```

Finally decompress the Zip file which contains the apk file named: 'universal'
