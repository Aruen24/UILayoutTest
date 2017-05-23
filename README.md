# UILayoutTest
activity_main.xml
<?xml version="1.0" encoding="utf-8"?>
<android.support.percent.PercentRelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <Button
        android:id="@+id/button1"
        android:text="Button 1"
        android:layout_alignParentLeft="true"
        android:layout_alignParentTop="true"
        app:layout_widthPercent="50%"
        app:layout_heightPercent="50%"
        />

    <Button
        android:id="@+id/button2"
        android:text="Button 2"
        android:layout_alignParentRight="true"
        android:layout_alignParentTop="true"
        app:layout_widthPercent="50%"
        app:layout_heightPercent="50%"
        />

    <Button
        android:id="@+id/button3"
        android:text="Button 3"
        android:layout_alignParentLeft="true"
        android:layout_alignParentBottom="true"
        app:layout_widthPercent="50%"
        app:layout_heightPercent="50%"
        />

    <Button
        android:id="@+id/button4"
        android:text="Button 4"
        android:layout_alignParentRight="true"
        android:layout_alignParentBottom="true"
        app:layout_widthPercent="50%"
        app:layout_heightPercent="50%"
        />

</android.support.percent.PercentRelativeLayout>

