## Drawable

##### Background drawable with shadow

```xml
<?xml version="1.0" encoding="utf-8"?>
<layer-list xmlns:android="http://schemas.android.com/apk/res/android">
    <item android:bottom="4dp">
        <shape android:shape="rectangle">
            <solid android:color="@color/colorPrimary"/>
        </shape>
    </item>
    <item android:gravity="bottom">
        <shape android:shape="rectangle">
            <size android:height="4dp"/>
            <gradient
                android:startColor="#36000000"
                android:angle="270"
                android:endColor="#0c000000"/>
        </shape>
    </item>
</layer-list>
```

