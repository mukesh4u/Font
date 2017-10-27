# Font
Android 8.0 (API level 26) introduces a new feature, Fonts in XML, which lets you use fonts as resources. This means, there is no need to bundle fonts as assets. Fonts are compiled in R file and are automatically available in the system as a resource. You can then access these fonts with the help of a new resource type, font.  The Support Library 26 provides full support to this feature on devices running API versions 14 and higher.
## Steps:
# To add fonts as resources, perform the following steps in the Android Studio:
  1. Right-click the res folder and go to New > Android resource directory.
      ![logo](https://github.com/mukesh4u/Font/raw/master/font1.png)
  2. The New Resource Directory window appears.
  3. In the Resource type list, select font, and then click OK.
      ![logo](https://github.com/mukesh4u/Font/raw/master/font2.png)
      ![logo](https://github.com/mukesh4u/Font/raw/master/font3.png)

# Note: The name of the resource directory must be font.

### Using fonts in XML layouts
1. In the layout XML file, set the fontFamily attribute to the font file you want to access.
      ```
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/text_font"
        android:padding="10dp"
        android:gravity="center"
        android:fontFamily="@font/pacifico"
        android:textSize="20sp"/>
    ```
    
    
![logo](https://github.com/mukesh4u/Font/raw/master/font.png)

For more:
https://developer.android.com/guide/topics/ui/look-and-feel/fonts-in-xml.html
